Day 38/60 — #60DayClaudeChallenge

Today I built a Typing Speed Studio. Not a basic typing test — a full adaptive typing platform with 7 categories (General, Programming, Academic, Business, Medical, Legal, Creative Writing) and 7 modes (Time, Words, Quote, Custom, Adaptive, Focus, Zen).

𝗪𝗵𝗮𝘁 𝗜 𝗯𝘂𝗶𝗹𝘁 → Live WPM, Raw WPM, CPM, Accuracy, Streak, and Completion tracking, updating in real time → A Monkeytype-style analytics dashboard after every session — consistency score, error heatmap, WPM/accuracy graphs, percentile estimate, and earned badges → Adaptive Mode that raises or lowers passage difficulty based on your own live WPM and accuracy → Local-storage session history, personal bests, and streaks — zero backend, zero account

𝗧𝗵𝗲 𝘂𝗻𝗰𝗼𝗺𝗳𝗼𝗿𝘁𝗮𝗯𝗹𝗲 𝗳𝗶𝗻𝗱𝗶𝗻𝗴 Generating "realistic" text per category is easy to fake and hard to do well. A hardcoded paragraph per category looks fine for exactly one run — the moment you restart the test, the illusion breaks. I had to build category-aware sentence generators (subject/verb/object banks + connectors) instead of static strings, or "Medical Mode" and "General English Mode" would've quietly been the same test wearing a different label.

Real variation, not the appearance of it — that's the difference between a demo and a tool people actually come back to.

Built solo in one sitting with Claude. Single HTML file, no frameworks, fully offline-capable.

Anthropic Anil Bajpai ABTalksOnAI
#60DayClaudeChallenge #BuildInPublic #ClaudeAI #ABTalks #AnthropicAI #WebDevelopment #JavaScript #EdTech
