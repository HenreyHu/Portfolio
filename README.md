# Henrey Hu — Portfolio

Software engineer with game programming, data analysis and RAG projects.
Currently looking for an internship in software engineering, game programming, or data analytics.

📄 [Resume](Henrey_Hu_Resume.pdf) 

## About

I'm a Computer Science student at Singapore Institute of Technology, studying Interactive Media and
Game Development jointly with DigiPen Institute of Technology Singapore.

Most of my work is systems programming in C++. I build state machines that drive runtime
behaviour, save and restore systems that persist application state across sessions, and the
internal debugging tools a team uses day to day. I work on engines written from scratch rather
than off the shelf frameworks, which keeps me close to the architecture instead of sitting on
top of it.
I also use SQL and Python to dig into datasets and back my answers with evidence rather than
assumptions, and I have built a retrieval-augmented question answering agent over SEC filings.

## Table of Contents

- [Skills](#-skills)
- [Game Development](#-game-development)
- [Data & AI](#-data--ai)
- [Education](#-education)
- [Links](#-links)

## 🛠 Skills

| Area | Tools |
|---|---|
| Languages | C++, C#, Python, SQL |
| Systems & tooling | Custom C++ engines, state machines, serialization, debug tooling (ImGui), Unity |
| Data & analytics | DuckDB, pandas, matplotlib, Tableau, Jupyter |
| Applied AI | Retrieval-augmented generation (RAG), hybrid search (BM25 + vector), embeddings (sentence-transformers), ChromaDB |

## 🎮 Game Development

| Project | Role | Tools | Timeframe | Description |
|---|---|---|---|---|
| [STRETCH](https://github.com/HenreyHu/stretch-writeup) | Programmer — AI & UI Champion | C++, Custom Engine, ImGui | Year 2 | 2D platformer built by a team of eight on a custom C++ engine with an entity component system. As AI and UI champion I owned the enemy AI, built as a four state machine of idle, patrol, spot and charge with behaviours registered against a shared context object. I also built the JSON serialisation layer that persists scenes, levels, entities, prefabs and system configuration, the checkpoint and respawn system, the interface system covering buttons, sliders and menu routing, and the undo history behind the level editor. |
| [Wave Maze](https://github.com/HenreyHu/waves-writeup) | Programmer | C++ | Year 1 | Top-down stealth maze game built by a team of five in C++ on a 2D engine. I owned the game state architecture, a shared state interface and a manager that every screen in the game runs through, then implemented the screens and the transitions between them, covering the menus, level select, three playable levels, and the pause, settings and exit overlays. I also built the shared interface layer used across all of them for button input, text rendering and font management. |

## 📊 Data & AI

| Project | Tools | Description |
|---|---|---|
| [Olist Revenue vs Freight & Delivery Performance](https://github.com/HenreyHu/olist-portfolio) | DuckDB, SQL, Python (pandas, matplotlib), Tableau Public | Solo analytics project on about 96,000 delivered Olist e-commerce orders, ranking product categories by revenue against freight cost and delivery reliability. I cleaned and modelled the data in DuckDB and SQL, answered eleven business questions, charted the results in Python, and published an interactive Tableau dashboard, with recommendations on which categories to promote, which to renegotiate freight for, and where to fix delivery first. |
| [RAG Question Answering Agent](https://github.com/HenreyHu/rag-qa-agent) | Python, Claude API, ChromaDB, BM25, BeautifulSoup | Solo agent that answers questions about SEC 20-F annual reports from Sea Limited and Grab with page citations, including comparisons across companies and years. I built it from scratch without LangChain or LlamaIndex, covering the filing parser, chunking, a hand-written BM25 index fused with vector search, and a tool-using Claude agent with a calculator. |

## 🎓 Education

**BSc (Hons) Computer Science, Interactive Media & Game Development**
Singapore Institute of Technology, joint degree with DigiPen Institute of Technology Singapore
Expected 2028

## 🔗 Links

- Portfolio site: [HenreyHu.github.io](https://HenreyHu.github.io)
- GitHub: [@HenreyHu](https://github.com/HenreyHu)
- LinkedIn: [linkedin.com/in/henrey-hu](https://www.linkedin.com/in/henrey-hu)
- Email: `henrey.hu@gmail.com`
