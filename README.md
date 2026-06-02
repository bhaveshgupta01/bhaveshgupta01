<div align="center">

# Bhavesh Gupta

<a href="https://readme-typing-svg.demolab.com">
  <img src="https://readme-typing-svg.demolab.com?font=Fira+Code&size=18&duration=2800&pause=900&color=8BE9FD&center=true&vCenter=true&width=520&lines=I+build+agentic+AI+systems.;Most+weekends+I'm+at+a+hackathon.;Talk+to+my+AI+twin+→+libralpanda.vercel.app" alt="Typing SVG" />
</a>

**MS CS @ NYU Courant · NYC · Looking for Summer 2026**

<a href="https://libralpanda.vercel.app"><img src="https://img.shields.io/badge/🤖_Talk_to_my_AI_twin-2b2d31?style=for-the-badge" alt="AI Twin"/></a>
<a href="https://linkedin.com/in/bhaveshgupta01"><img src="https://img.shields.io/badge/LinkedIn-0a66c2?style=for-the-badge&logo=linkedin&logoColor=white" alt="LinkedIn"/></a>
<a href="mailto:bg2896@nyu.edu"><img src="https://img.shields.io/badge/Email-d44638?style=for-the-badge&logo=gmail&logoColor=white" alt="Email"/></a>

</div>

---

### 👋 The short version

I started writing Android apps. Wanted intelligent search, so I learned ML. Realized AI is just a thin wrapper around whether you can get the right data to the model at the right time, so now I work on agentic systems and the messy web-data side underneath them.

When I'm not at NYU I'm usually shipping something for a Saturday hackathon. The receipts are below.

---

### 🛠️ What I'm doing right now

- **Shipping:** [WAGE.md](https://github.com/bhaveshgupta01/Wage_MD), a federal salary index that turns DOL filings into a queryable agentic API
- **Looking for:** Summer 2026 internship at an agentic-AI or web-data startup
- **Reading:** too many MCP tool registries, Anthropic's agent safety papers, and "Designing Data-Intensive Applications" (again)
- **Open to a coffee:** if you're building anything where the answer has to be true *right now*

---

### 🏆 Recent receipts

| When | What | Where | Result |
|---|---|---|---|
| May 2026 | [**WAGE.md**](https://github.com/bhaveshgupta01/Wage_MD) | DataDog Agentic Eng. Hackathon (NYC) | 🏆 Best Use of Nimble's API |
| Feb 2026 | **PulseNYC** | Pulse NYC SuperBowl LX Hackathon | 🥇 1st Place |
| Jan 2026 | **Virtual War Room** | Google × Columbia (50+ teams) | 🏆 Strongest Technical Build |
| Mar 2024 | [Mammography Transfer Learning](https://doi.org/10.24874/PES.SI.25.03A.007) | ICAIA '24 | 🎙️ Best Presenter + peer-reviewed publication (98% accuracy) |

---

### 🚀 Featured

<table>
<tr>
<td width="50%" valign="top">

#### [WAGE.md](https://github.com/bhaveshgupta01/Wage_MD)
*Federal salary index from US DOL filings*

Solo 8-hour build at DataDog NYC. Three Gemini agents (Scout, Investigator, Counselor) ingest ~19K filings + 1,428 CA WARN notices into ClickHouse for sub-100ms percentile queries. The hard part wasn't the agents, it was getting past Akamai on the DOL site. Nimble did that.

`Nimble` `ClickHouse` `Gemini 2.5 Pro+Flash` `FastAPI` `Next.js 14` `Datadog APM`

</td>
<td width="50%" valign="top">

#### [SignalFlow](https://github.com/bhaveshgupta01/signalflow)
*Autonomous AI trading agent*

Six async triggers feeding a Gemini agent loop (Polymarket 40s, KOL whales 50s, funding 75s, discovery 100s, cross-chain 150s, portfolio 240s). 5-layer risk engine (drawdown breaker, margin, liquidity gate, ATR-based SL/TP, fill tracking). Overnight result: **+5.6% at 78% win rate**.

`Python asyncio` `Gemini 2.5 Flash` `Boba Agents MCP (85+ tools / 9 chains)` `Hyperliquid` `Next.js 16`

</td>
</tr>
<tr>
<td width="50%" valign="top">

#### [Bhavesh.ai](https://libralpanda.vercel.app)
*First-person AI twin portfolio*

The chat IS the navigation. A LangGraph ReAct agent with two tools (role-filtered ChromaDB RAG over 12 markdowns + DuckDuckGo live search) answers in first-person, scrolls the page, and renders inline stat cards in under a second.

`React 19` `FastAPI` `LangGraph ReAct` `Gemini 2.5 Flash` `ChromaDB` `Railway`

</td>
<td width="50%" valign="top">

#### [VoiceGraph](https://voicegraph-802587268683.us-central1.run.app)
*Voice-first knowledge graph*

569-node / 882-edge live graph from a 3-phase extraction pipeline. Gemini Live bidirectional audio (16 kHz in, 24 kHz out) multiplexed with graph mutations over one WebSocket. 8 query/ranking tools including Text2Cypher. Built at Google × NYU Tandon.

`React` `TypeScript` `Three.js` `Neo4j AuraDB` `Gemini Live` `LangChain`

</td>
</tr>
<tr>
<td width="50%" valign="top">

#### [Healthcare Agentic RAG](https://github.com/bhaveshgupta01/healthcare-agentic-rag)
*Self-correcting medical RAG*

6-node LangGraph pipeline: retrieve → grade → route → web fallback → generate → cite. LLaVA for medical images, Mistral for reasoning. 3-tier hallucination grading.

`LangGraph` `LLaVA` `Mistral 7B (Ollama)` `ChromaDB` `FastAPI`

</td>
<td width="50%" valign="top">

#### [Securing the Edge](https://github.com/bhaveshgupta01/efficient-split-dnn-privacy)
*Quantization as privacy defense*

NYU Efficient AI coursework. INT8 quantization is dual-purpose: **4× edge-model shrink (6 MB → 1.6 MB)** AND breaks adversarial feature inversion on Split-DNN, at <1% accuracy drop.

`PyTorch FX Quantization` `MobileNetV3-Small` `CIFAR-100` `Split-DNN`

</td>
</tr>
</table>

<sub>Also worth a look: [BunKey](https://github.com/bhaveshgupta01/BunKey) (Android dual-key encryption) · [CrossCloud / QuantIAN](https://github.com/bhaveshgupta01/CrossCloudAnalyser) (multi-cloud P2P analytics across AWS + Azure + GCP) · GyBuddy (Google AI Hackathon, real-time fitness coaching agent with 10 function-calling tools)</sub>

---

### 🧰 Stack I actually reach for

| | |
|---|---|
| **Languages** | Python · TypeScript · JavaScript · Java · Kotlin · SQL · C/C++ · Bash |
| **AI / Agentic** | LangChain · LangGraph (ReAct) · MCP · Gemini 2.5 · GPT-4 · Claude · PyTorch · ChromaDB · Neo4j AuraDB · RAG |
| **Backend / Full-Stack** | FastAPI · asyncio · aiohttp · Spring Boot · Node.js · REST · WebSocket · PostgreSQL · ClickHouse |
| **Frontend / Mobile** | React 19 · Next.js 14 · Tailwind · Vite · React Native (Expo) · Jetpack Compose · Flutter |
| **Cloud / Infra** | AWS (EC2 / S3 / Bedrock) · GCP (Cloud Run, Vertex AI) · Azure · Docker · GitHub Actions · Datadog APM (ddtrace) · Firebase |
| **Web Data** | Nimble Web API · Playwright · Puppeteer · ETL |

---

### 📊 GitHub

<div align="center">

<img src="https://github-readme-stats.vercel.app/api?username=bhaveshgupta01&show_icons=true&theme=tokyonight&count_private=true&hide_border=true&include_all_commits=true" width="48%"/>
<img src="https://github-readme-stats.vercel.app/api/top-langs/?username=bhaveshgupta01&layout=compact&theme=tokyonight&hide_border=true&langs_count=10" width="48%"/>

<img src="https://github-readme-streak-stats.herokuapp.com?user=bhaveshgupta01&theme=tokyonight&hide_border=true" width="60%"/>

<!-- Optional: snake animation eating contributions. Requires the snake GH Action set up in this repo (.github/workflows/snake.yml). -->
<img src="https://raw.githubusercontent.com/bhaveshgupta01/bhaveshgupta01/output/github-contribution-grid-snake.svg" alt="Snake animation"/>

</div>

---

<div align="center">

If you're building agentic systems, web-data infra, or anything where the answer has to be true *right now*, let's talk.

<a href="https://libralpanda.vercel.app"><img src="https://img.shields.io/badge/🤖_Talk_to_my_AI_twin_first-2b2d31?style=for-the-badge" alt="AI Twin"/></a>

<sub>This README is a living thing. Last updated: 2026-06-01.</sub>

</div>
