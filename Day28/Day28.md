🏥 Day 24 of #60DayClaudeChallenge

Today I built a Hospital Admission Readiness Simulator with Claude — and it taught me something I didn't expect about healthcare admin work: it's almost never pass/fail.

I stepped into the role of a Hospital Admission Coordinator and had Claude help me model the real workflow:
→ Prior Authorization that branches three different ways (Approved / Pending / Denied — including an appeal path) 
→ A live Readiness Score weighted across PA, documentation, physician orders, insurance, consent, and bed status 
→ CMS 2-Midnight Rule logic for Observation admissions 
→ InterQual/Milliman medical necessity criteria for Acute MI and CHF cases → A full care coordination view — Attending, Case Manager, Nursing, Utilization Review, Discharge Planning 
→ A milestone rail tracking the case from PA Review all the way to Admission Complete

The most interesting constraint: a denied PA on an ICU admission can never cross 70% readiness from admin tasks alone — no amount of paperwork substitutes for clinical authorization. Building that rule in was a good reminder that not every gap can be closed by "doing more tasks."

This is the part of prompt engineering I keep coming back to: the value isn't the UI, it's forcing yourself to encode the actual logic of a domain — the branches, the caps, the exceptions — before you ever touch the design.
Task-first, no dashboard, real workflow logic. That's the build today.

#60DayClaudeChallenge #Claude #PromptEngineering #HealthcareIT #BuildInPublic #DataAnalytics #ABTalks

— in collaboration with ABTalksOnAI Anthropic Anil Bajpai
