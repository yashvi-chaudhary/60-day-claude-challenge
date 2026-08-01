🚀 Day 39/60 — #60DayClaudeChallenge

Today I built a PDF Splitter & Merger — a premium, fully offline PDF toolkit that runs entirely in the browser. No backend. No uploads. No file ever leaves your device.

🔧 What it does:
✂️ Splitter — Upload a PDF and instantly see every page as a thumbnail. Split by custom ranges, every N pages, "split after" specific pages, or hand-pick pages to extract. Every input is validated live, with clear error states before you ever click "Split."

🧩 Merger — Drag and drop multiple PDFs, reorder them visually with page thumbnails, and watch live stats (files, total pages, estimated size) update as you go. One click merges everything into a single document.

🎨 On the UX side: dark mode, keyboard shortcuts, accessible ARIA roles, smooth micro-interactions, and a processing overlay so the app never feels like it's stalling — all wrapped in a single self-contained HTML file powered by pdf-lib and pdf.js.

💡 The honest finding: The hardest part of this build wasn't rendering thumbnails or wiring up drag-and-drop — it was validating page ranges against real document boundaries. Overlapping ranges, out-of-bounds numbers, empty selections... a PDF tool is only as trustworthy as its edge-case handling. Good UX here turned out to be 80% guarding against bad input, not building features.

Building tools people would actually choose over existing PDF utilities means sweating the parts nobody notices until they break.

🛠️ Tech: pdf-lib · pdf.js · Vanilla JS · HTML5 Drag & Drop · CSS Glassmorphism

Anthropic ABTalksOnAI Anil Bajpai
#60DayClaudeChallenge #BuildInPublic #ClaudeAI #ABTalks #AnthropicAI #PDFTools #WebDevelopment  #FrontendDevelopment #JavaScript #ProductivityTools
