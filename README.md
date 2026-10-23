# 🏓 PickleBase Open Biomechanics & 3D Tactical Specification (2026)

> 🌐 **Language / Ngôn ngữ:** [**🇺🇸 English (Current)**](./README.md) | [**🇻🇳 Tiếng Việt (Vietnamese)**](./README.vi.md)  
> 🚀 **Live Documentation Portal (GitHub Pages):** [**English Portal (`/en/`)**](https://aizaloapp.github.io/picklebase-open-spec/en/) | [**Vietnamese Portal (`/`)**](https://aizaloapp.github.io/picklebase-open-spec/)  
> 🏟️ **Official Web Platform:** [**https://picklebase.app/en/**](https://picklebase.app/en/) ([Vietnamese Edition](https://picklebase.app/))  
> 🏛️ **Canonical Entity & Scientific DOI:** [**Wikidata (Q141814048)**](https://www.wikidata.org/wiki/Q141814048) | [**DOI: 10.5281/zenodo.23582848**](https://doi.org/10.5281/zenodo.23582848) | [**Hugging Face Dataset**](https://huggingface.co/datasets/lekhoa288/picklebase-open-biomechanics)  
> 📦 **Official MCP SDK & AI Registry:** [**npm (`picklebase-mcp`)**](https://www.npmjs.com/package/picklebase-mcp) | [**PyPI (`picklebase-mcp`)**](https://pypi.org/project/picklebase-mcp/) | [**ClawHub Skill**](https://clawhub.ai/aizaloapp/skills/picklebase-biomechanics-coach) | [**Chrome Web Store**](https://chromewebstore.google.com/detail/picklebase/fodnbhemeinhfbeomholngiakpbkicjg)

---

## 🎯 1. Overview & Open Specification Purpose

**PickleBase Tactical Academy** ([picklebase.app](https://picklebase.app/en/)) publishes this open specification repository to standardize **Pickleball shot biomechanics**, **3D parabolic trajectory parameters**, **doubles tactical formations**, and **Model Context Protocol (MCP) / OpenAPI schemas** for athletes, coaches, sports-analytics researchers, and autonomous AI agents.

All parameters are calibrated against the **USA Pickleball Official Rulebook 2026** (`6.10m × 13.41m` court, `2.13m / 7ft` Non-Volley Zone, `86.4cm / 34in` center net cord) and verified by **Head Coach Nguyen Van Khoa (DUPR 5.5)** alongside 3-angle pro video breakdowns from **Ben Johns, Tyson McGuffin, Zane Navratil, and Jordan Briones**.

---

## 📐 2. Complete 18 Core Shots Biomechanics Matrix

Click any shot below to open the interactive **3D Paddle Angle & Ball Clock Lab (`<paddle-3d-lab>`)** and **3 Pro Coach Video Angles** on PickleBase:

| # | Shot Guide (Clean URL) | 3D Paddle Face & Swing Path | Contact Point | Grip Tension & COR | DUPR |
| :--- | :--- | :--- | :--- | :--- | :--- |
| 1 | [**Cross-Court Dink (4 Variants)**](https://picklebase.app/en/shot-dink) | `Lift +20° (4h00) • Push +10° (3h20) • Slice +26° (3h45➔5h) • Topspin +4° (3h15➔2h45)` | `+30–34cm ahead of toes • 45–65cm height` | `3.0–4.5/10 (Soft Hands • COR 0.48)` | `2.0–5.5+` |
| 2 | [**Third Shot Drop**](https://picklebase.app/en/shot-third-drop) | `Open +6° to +12° (Pro +8° • 3h30➔2h45) • +38° shoulder lift` | `+36cm ahead of lead foot • 55–70cm height` | `4.0/10 (85% Shoulder • 15% Wrist • COR 0.49)` | `3.0+` |
| 3 | [**Third Shot Drive**](https://picklebase.app/en/shot-drive) | `Near-vertical 0° to +4° (Pro +2° • 3h15➔2h30) • +30° brush to shoulder` | `+42cm ahead of lead foot • 85cm hip peak` | `6.0/10 (85% Shoulder • 15% Wrist • COR 0.53)` | `3.5+` |
| 4 | [**The Drip Hybrid Shot**](https://picklebase.app/en/shot-drip) | `0° to +5° face (Pro +3° • 3h30➔2h30) • +50° brush to shoulder` | `+28cm ahead of lead foot • 45–55cm low height` | `5.0/10 (85% Shoulder • 15% Wrist • COR 0.50)` | `4.0+` |
| 5 | [**Defensive Reset**](https://picklebase.app/en/shot-reset) | `Static +12° to +20° (Pro +16° • 3h30➔3h45) • +5° quiet block` | `+28cm in front • 50–75cm core height` | `3.0/10 (Sponge hands • COR 0.45)` | `3.5+` |
| 6 | [**Roll Volley**](https://picklebase.app/en/shot-roll-volley) | `Slightly Open +4° (0°➔+6° at 3h15) • Vertical back-brush 3h15➔2h45 pulling up to shoulder (+42°)` | `+42cm ahead of toes • 60–78cm below net` | `5.0/10 (85% Shoulder • 15% Wrist • COR 0.51)` | `4.0+` |
| 7 | [**Backhand & Forehand Wrist Flick**](https://picklebase.app/en/shot-flick) | `Closed -8° (82° • Pro -10°➔-5°) • +18° frisbee snap (2h45➔1h40)` | `+45cm out in front • 86–95cm net height` | `Loose 3.5/10 coil ➔ 8.0/10 snap (<15cm • COR 0.56)` | `4.0+` |
| 8 | [**Punch Volley**](https://picklebase.app/en/shot-punch-volley) | `Slightly closed -6° to -2° (Pro -4° • 2h50) • Flat 0° punch (15cm)` | `+40cm in front • 95–115cm chest height` | `7.0/10 (Firm punch • COR 0.57)` | `3.5+` |
| 9 | [**Scorpion Shot**](https://picklebase.app/en/shot-scorpion) | `Closed -14° to -6° (Pro -10° • 2h40➔2h15) • -5° downward press` | `+34cm in front of forehead • 140–170cm height` | `6.5/10 (Firm overhead snap • COR 0.56)` | `4.5+` |
| 10 | [**The Tomahawk Shot**](https://picklebase.app/en/shot-tomahawk) | `Closed -12° to -20° (2h28) • -24° axe strike` | `+34cm in front of forehead • 175–205cm height` | `7.5/10 (Continental grip • COR 0.57)` | `4.0+` |
| 11 | [**Overhead Smash**](https://picklebase.app/en/shot-smash) | `Closed -15° to -25° (Pro -20° • 2h20➔1h50) • -25° downward strike` | `+32cm in front of forehead • 215–245cm peak reach` | `8.0/10 (Explosive pronation snap • COR 0.58)` | `3.0+` |
| 12 | [**Disguised Topspin Offensive Lob**](https://picklebase.app/en/shot-lob) | `Open +8° to +15° (Pro +10° • 3h30➔2h45) • +68° vertical lift to shoulder` | `+35cm ahead of lead foot • 50–65cm height` | `4.5/10 (85% Shoulder & Legs • 15% Wrist • COR 0.51)` | `3.5+` |
| 13 | [**Aggressive Deep Serve**](https://picklebase.app/en/shot-serve) | `Slightly open 0° to +5° (Pro +3° • 3h15➔2h30) • +35° brush to shoulder (Rule 4.A.4)` | `+40cm ahead of lead foot • 60–72cm below navel` | `6.0/10 (85% Shoulder • 15% Wrist • COR 0.52)` | `2.5+` |
| 14 | [**Deep Return of Serve**](https://picklebase.app/en/shot-return) | `Slightly open 0° to +6° (Pro +3° • 3h15➔2h30) • +28° brush to shoulder` | `+36cm ahead • 75–90cm height stepping forward` | `5.5/10 (85% Shoulder • 15% Wrist • COR 0.51)` | `2.5+` |
| 15 | [**Combo Drive-Drop Playbook**](https://picklebase.app/en/shot-combo-drive-drop) | `Shot 3 Drive (+2°) ➔ Open +8° to +14° (Pro +10° • 3h30➔2h50) on Shot 5` | `+35cm out front • After midcourt Split-Step` | `Dynamic: 6.0/10 (Shot 3 Drive) ➔ 4.0/10 (Shot 5 Drop)` | `4.0+` |
| 16 | [**Erne Shot**](https://picklebase.app/en/shot-erne) | `Closed -20° to -10° (Pro -15° • 2h30➔2h00) • -20° downward punch` | `+38cm early reach • 95–125cm near net post` | `7.0/10 (Decisive kill snap • COR 0.55)` | `4.5+` |
| 17 | [**Bert Shot**](https://picklebase.app/en/shot-bert) | `Closed -22° to -12° (Pro -18° • 2h25➔1h55) • -22° downward strike` | `+40cm airborne reach • 105–135cm apex` | `7.5/10 (Maximum acceleration • COR 0.57)` | `5.0+` |
| 18 | [**Around The Post (ATP)**](https://picklebase.app/en/shot-atp) | `Near-vertical 0° to +5° (Pro +2° • 3h15➔2h45) • +18° side-topspin` | `+32cm ahead • 25–42cm ankle height outside post` | `6.0/10 (85% Shoulder • 15% Wrist • COR 0.52)` | `4.5+` |

---

## ♟️ 3. Pro Doubles Tactical Formations (11 Playbooks)

| # | Tactical Playbook (Clean URL) | DUPR | Core Biomechanical & Geometric Rule |
| :--- | :--- | :--- | :--- |
| 1 | [**Stacking & Switching Doubles Strategy**](https://picklebase.app/en/tactic-stacking) | `3.5+` | Keeps both dominant forehands sealing 90% of the middle seam |
| 2 | [**Shake & Bake (3rd Shot Drive & 5th Shot Crash)**](https://picklebase.app/en/tactic-shake-and-bake) | `4.0+` | Partner 1 fires dipping 3rd drive while Partner 2 crashes NVZ for 5th ball putaway |
| 3 | [**T1 & T2 Transition Zones Mastery**](https://picklebase.app/en/tactic-transition-zones) | `3.5+` | Low-paddle short-hop at T1 ➔ Sprint past Dead Zone ➔ High-paddle counter at T2 |
| 4 | [**The Freezer (Target Isolation Strategy)**](https://picklebase.app/en/tactic-the-freezer) | `4.0+` | Direct 85–90% of balls to weaker player outer sideline, starving the poacher |
| 5 | [**Anti-Smash Defensive Split-Step Wall**](https://picklebase.app/en/tactic-anti-smash) | `3.5+` | Retreat 2 steps ➔ Land split-step 0.1s early ➔ 2.5/10 grip (COR 0.45) |
| 6 | [**Smart Speed-Up Combos & Counter Anticipation**](https://picklebase.app/en/tactic-speedup-combos) | `4.0+` | Initiate 1st speed-up jam ➔ Pre-aim for 85% predictable 2nd-ball rebound |
| 7 | [**Chicken Wing Body-Jam Attack**](https://picklebase.app/en/tactic-chicken-wing) | `4.0+` | Target paddle-side armpit and hip (6in from torso) to jam elbow rotation |
| 8 | [**Off-The-Bounce Banana Roll Curve**](https://picklebase.app/en/tactic-banana-roll) | `4.5+` | Drop knees to net level ➔ Crescent brush 7-to-1 o-clock dipping at shoelaces |
| 9 | [**Aggressive Hip Push Dink**](https://picklebase.app/en/tactic-push-dink) | `4.0+` | Intercept bounce apex ➔ Linear +10° shoulder push deep into 1ft indecision zone |
| 10 | [**Deep Slice Return & Net Sprint**](https://picklebase.app/en/tactic-deep-return) | `3.5+` | Open +10°➔+18° slice buying 1.8–2.0s hangtime to complete 4-stride net rush |
| 11 | [**Breaking the 4.0 Barrier to 4.5+ (3-5-7-9 & Disguise)**](https://picklebase.app/en/tactic-breaking-4-0) | `4.0➔4.5+` | 3-5-7-9 progression + 18–24in safety margin + NVZ disguise + Backhand counter |

---

## 🚀 4. Interactive Training & Diagnostic Tools

- [**3D Pickleball Tactical Board & Trajectory Lab**](https://picklebase.app/en/) — Real-time 3D parabolic flight simulator, net clearance calculator, and dynamic court coverage HUD.
- [**2.5D Tactical Reflex Rally Simulator**](https://picklebase.app/en/trainer) — 60 FPS Isometric simulator featuring 4 modes + 8 specialized drills (Kitchen 2.0 Traffic Light, T1-T2 Transition, Threat Arcs & Swing Cam).
- [**DUPR Tactical IQ Diagnostic Quiz**](https://picklebase.app/en/dupr-quiz) — 20 pro match scenarios measuring a 5-axis tactical radar, diagnosing positional flaws, and generating personalized training roadmaps.
- [**35+ Pro Pickleball Biomechanics & Rules Glossary**](https://picklebase.app/en/glossary) — Standardized biomechanical definitions and official USA Pickleball 2026 Rulebook citations across 35+ competitive terms.
- [**Curated PPA & MLP Pro Match Video Breakdown**](https://picklebase.app/en/matches) — Point-by-point tactical breakdowns of world-class PPA and MLP Tour matches with interactive timestamp bookmarks.
- [**PickleBase Chrome AI Coach Extension (Manifest V3)**](https://picklebase.app/en/extension) — Official Chrome Web Store Side Panel AI Coach (DUPR 5.5) for real-time YouTube match and technique analysis.

---

## 🤖 5. Open Data Schemas, MCP Server & AI Agent Discovery

| Resource | Path / Endpoint | Description |
| :--- | :--- | :--- |
| **English Biomechanics JSON** | [`biomechanics-index.en.json`](./biomechanics-index.en.json) | Machine-readable dataset for all 18 shots, 11 tactics, and physical constants (EN) |
| **Vietnamese Biomechanics JSON** | [`biomechanics-index.vi.json`](./biomechanics-index.vi.json) | Machine-readable dataset for all 18 shots, 11 tactics, and physical constants (VI) |
| **OpenAPI 3.1.0 Specification** | [`openapi.json`](./openapi.json) | Production API specification for `https://picklebase.app` |
| **Agent Skill Definition** | [`SKILL.md`](./SKILL.md) | OpenClaw / ClawHub compatible skill for AI coaching agents |
| **Live MCP JSON-RPC Endpoint** | `https://picklebase.app/api/mcp` | Stateless Streamable HTTP Model Context Protocol server |
| **LLMs Context Index** | [`https://picklebase.app/llms.txt`](https://picklebase.app/llms.txt) | RFC 8288 Markdown knowledge base index for AI search engines |
| **Wikidata Knowledge Graph** | [`Q141814048`](https://www.wikidata.org/wiki/Q141814048) | Canonical Wikidata entity for PickleBase Tactical Academy |
| **DataCite Persistent DOI** | [`https://doi.org/10.5281/zenodo.23582848`](https://doi.org/10.5281/zenodo.23582848) | Official Digital Object Identifier (`10.5281/zenodo.23582848`) |
| **Zenodo — CERN Research Record** | [`https://zenodo.org/records/23582848`](https://zenodo.org/records/23582848) | Open-access scientific record archived at CERN Data Centre |
| **Hugging Face Biomechanics Dataset** | [`lekhoa288/picklebase-open-biomechanics`](https://huggingface.co/datasets/lekhoa288/picklebase-open-biomechanics) | Open Pickleball biomechanics & 3D trajectory dataset on Hugging Face |
| **npm Official MCP SDK** | [`picklebase-mcp` (v2.3.0)](https://www.npmjs.com/package/picklebase-mcp) | Official Node.js Model Context Protocol SDK on npm Registry |
| **PyPI Official MCP SDK** | [`picklebase-mcp`](https://pypi.org/project/picklebase-mcp/) | Official Python Model Context Protocol SDK on PyPI |
| **ClawHub AI Skill Registry** | [`picklebase-biomechanics-coach`](https://clawhub.ai/aizaloapp/skills/picklebase-biomechanics-coach) | Verified AI Agent Skill on ClawHub Registry |
| **Chrome Web Store Extension** | [**PickleBase AI Coach Side Panel**](https://chromewebstore.google.com/detail/picklebase/fodnbhemeinhfbeomholngiakpbkicjg) | Official Manifest V3 Chrome Extension (`fodnbhemeinhfbeomholngiakpbkicjg`) |
| **DEV.to Engineering Architecture** | [**Zero-Server 3D Pickleball Biomechanics & MediaPipe Pose on the Edge**](https://dev.to/aizaloapp/building-a-zero-server-3d-pickleball-biomechanics-mediapipe-pose-coach-on-the-edge-webgl-mcp-a3n) | Engineering deep dive on WebGL, MediaPipe Pose & Edge MCP |
| **Viblo Engineering Case Study** | [**3D WebGL Biomechanics & Edge MCP Architecture**](https://viblo.asia/p/giai-bai-toan-phan-tich-co-sinh-hoc-biomechanics-pickleball-3d-cham-diem-dong-tac-bang-mediapipe-pose-ngay-tren-trinh-duyet-webgl-edge-mcp-XP4WEZ3kL7G) | Technical case study on 3D biomechanics scoring & Edge MCP |

---

## 📄 License

Released under the [MIT License](./LICENSE). Attribution required: **PickleBase Tactical Academy (https://picklebase.app)**.
