Day 40/60 — I built an AI Assistant Builder that interviews itself before writing a single line of code 🛠️

Today's build was different from the rest. Instead of building one app, I built the *process* of building an app.

The idea: give Claude a one-line brief for an assistant, and have it interview you (one MCQ question at a time — domain, audience, inputs, output format, tone) before generating anything. Only after that quiz is done does it write:

→ The system prompt ("the brain") — role, scope, output schema, and explicit edge-case handling
→ The interface — a single self-contained HTML file calling the Claude API live
→ A "How this was built" documentation panel explaining every design decision

I used it to build ScanPass, an ATS Resume Checker for students and freshers. Paste your resume, get a score dial, a parsing/keywords/structure/impact breakdown, and specific fixes — not just a pass/fail number.

The uncomfortable finding: the interview step is what actually separates a toy demo from something usable. Skip straight to "build me a resume checker" and you get a generic scorer. Force the domain, audience, and edge cases to be named out loud first, and the system prompt writes itself — the edge cases (non-resume text, missing job description, abusive input) stopped being afterthoughts and became requirements.

Structure > style, again. The scanning animation and score dial look nice, but the real work happened in forcing strict JSON output and calibrating scoring for freshers (projects over work history) before any UI was touched.

Tech: Claude API (system prompt + fetch), vanilla HTML/CSS/JS, no dependencies.

Anthropic ABTalksOnAI Anil Bajpai
