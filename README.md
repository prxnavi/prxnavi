## Pranavi Sammidi

I build AI agent systems grounded in real data, along with the software around them: mixed-reality interfaces, real-time backends and privacy controls.

📫 pranavisammidi@gmail.com

---

### Selected work

**[ForeSite](https://github.com/prxnavi/ForeSite)**: an AI digital twin of a building that you walk inside on Meta Quest  
Eight NVIDIA Nemotron agents investigate equipment risk and structural changes, simulate cascading failures, price the impact from lease terms, and verify the fix. The entire backend is a single SpacetimeDB module that holds the knowledge graph, the structural engine, the simulator, the agent runtime and multiplayer sync.
- **15/15** answers correct with the system's tools, vs 11/15 for the same model without them; **4× faster** per question
- **58 → 11** model calls per investigation; **100%** of spoken answers fact-checked against the data
- **~38 ms** median sync across headsets; **~1,700** 24-hour failure simulations per second inside the database

`Unity 6` `C#` `OpenXR` `TypeScript` `SpacetimeDB` `NVIDIA Nemotron` `Whisper`

**[AgentPrivacy](https://github.com/prxnavi/agentprivacy)**: an AI assistant for nonprofit clinics that never sees personal data · [live demo](https://agentprivacy-run-replay-1.vercel.app/)  
Sensitive values are swapped for placeholders before the model sees anything, and every tool call is checked against the user's role before it runs. It all runs on a local LLM on an IBM z17, so data never leaves the machine.
- **0 of 12** attacks got data out, vs 2 of 12 for an unprotected agent, with **0** normal tasks wrongly blocked

`Python` `IBM LinuxONE` `local LLM`

**[Academic Warfare](https://github.com/prxnavi/academic-warfare)**: competitive trivia generated from university syllabi  
It ingests a course syllabus and generates questions with Gemini (grounded by web search). Classmates then play live battles that feed a course leaderboard.

`TypeScript` `React` `Express` `MongoDB` `Redis` `Socket.io` `Gemini`

**[Pochi](https://github.com/prxnavi/pochi)**: peer-to-peer trading for blind-box collectibles  
Users can list figures, browse, and propose 1-for-1 trades, with Google sign-in. It's built on Supabase with row-level security.

`TypeScript` `Next.js` `Supabase`

**[HealthBuddy](https://github.com/prxnavi/HealthBuddy)**: a health literacy app for women, built in Swift.

---

### Also

- I created and taught a [Git and GitHub workshop](https://github.com/prxnavi/Github-Workshop) for students.
- Right now I'm going deeper on ML: neural networks and agent evaluation.
