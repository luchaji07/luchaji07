# Luc Haji

**AI-native systems & product engineer.** I architect and ship deployed systems by directing agentic coding tools — I own the architecture, the debugging, the verification, and the product calls; the agents do the typing. Part of that judgment is deciding *where compute lives*: frontier cloud when it's right, local when latency and privacy demand it.

📍 Berkeley, CA · Incoming first-year @ Tufts University (Class of 2030)

🛠️ **Software Development Intern @ Famlyn** (Denver-metro startup) — I own the internal KPI dashboard (Python/Flask · Firebase Firestore · AWS), working directly with the CEO. Shipped production fixes in week one.

---

### What I'm building

**♟️ gambit — a deployed chess-improvement product** · [live demo](https://gambit-670883285901.us-central1.run.app)
Pulls your Chess.com games, runs them through Stockfish, and returns an honest diagnosis of your recurring mistakes plus a focused training plan. **Live on GCP Cloud Run**, multi-user, built under commercial authorization from Chess.com. Architecture: Hono API + React/Vite front end, Supabase/Postgres, Stockfish analysis, Gemini for the coaching layer, durable async jobs on Cloud Tasks. Started as a tool to fix my own game — 645 of my own rapid games analyzed — and grew into a product. *(Free diagnosis live now; a $9/mo Pro tier is built and verified end-to-end — public launch pending.)*

**🧠 edgebox — local inference, frontier engineering** · *building, summer 2026*
A 24/7 local AI server built from a repurposed gaming PC: real-time object detection on PoE camera streams (Frigate + TensorRT), a local vision-language model that turns events into plain-English alerts (Ollama), and anonymous street-traffic counting that feeds my own dataset for stats/econ analysis. **Privacy by architecture:** no frame leaves the box, no identities, aggregates only. Benchmarks (tokens/sec, FPS, power draw) land as each phase ships. Continues at Tufts this fall, fused with MBTA real-time + Boston open data.

**✈️ overhead — a live labeled sky feed** · *in design*
Outdoor camera + ADS-B radio (RTL-SDR) sensor fusion that labels every plane overhead — flight #, airline, route, altitude — with a one-line Gemini narration, on a Next.js dashboard. The hard problem is camera↔radio calibration: mapping GPS coordinates onto camera pixels.

**🌍 geo-game — shipped** · [live](https://atlas-three-iota.vercel.app/)
A minimalist, Sporcle-style world-geography quiz: 197 countries, three modes, interactive d3-geo vector map, no framework. Live on Vercel.

---

### How I build
I architect and build by directing agentic coding tools (Claude Code power user — custom MCP servers, skills, hooks, subagents), with live research wired into every design decision and a coding agent that can run on the server itself. The judgment is mine: which architecture, which trade-offs, which bugs matter, what the numbers say. Agents accelerate the typing, not the thinking.

### Tech I reach for
`Python` · `Flask` · `LLM integration (Ollama · Gemini · API)` · `Firebase / Firestore` · `Supabase / Postgres` · `AWS (Lightsail · nginx/gunicorn/systemd)` · `GCP (Cloud Run · Cloud Tasks · Vertex)` · `JavaScript / React / Vite` · `computer vision (YOLO · Frigate · TensorRT)` · `agentic dev workflows (Claude Code · MCP)`

📫 hajiluc30@gmail.com
