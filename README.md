# Pankaj Baid

**AI + backend engineer.** B.Tech in Computer Science & AI at Newton School of Technology, Rishihood University (2024 – 2028, CGPA 8.618 / 10). Open to 2027 internships.

I build retrieval, agent and backend systems, deploy them, and measure them. Every project below has its numbers, its limits and the command that reproduces them in its README.

## Experience

**Founding Software Engineer (AI & Backend), in.culcate**, Sep 2024 – Mar 2026
- Built a 5+ agent content pipeline (scripting, voice selection, ElevenLabs narration) that cut production time by 40%.
- Built 20+ REST endpoints in Node.js, Express and MongoDB for auth and content in a 2,000-user app.
- Automated 5+ publishing workflows with a central CMS, cutting content turnaround by 30%; ran backend services on AWS EC2.

## AI projects

| Project | What it is | Evidence |
|---|---|---|
| [Codicil](https://github.com/pankajbaid567/codicil) | Cited, abstaining RAG over 17 RBI Directions in English, Hindi and Hinglish. Hybrid BM25 + dense retrieval, RRF, cross-encoder rerank. [Live](https://codicil.onrender.com) | Held-out nDCG@10 0.787 vs 0.663 for BM25, R@10 0.957; 63 tests, mutation check 15/15 |
| [HireFlow AI](https://github.com/pankajbaid567/hireflow) | Career assistant built by a 5-person team (I maintained the repo, reviewed PRs and integrated modules): Python agents for job discovery, resume tailoring and interview prep, plus Cloudflare Workers, D1 and Queues. [Live](https://hireflow-dashboard.pages.dev) | Hybrid BGE matching: nDCG@3 0.70 to 0.95 on a 120-case author-labelled benchmark; 39 tenant-isolation probes, 0 leaks |
| [VITRAM](https://github.com/pankajbaid567/vitram) | Financial companion for salaried users in India. A Gemini tool-calling assistant can only narrate verified calculations; any amount that doesn't match a tool result is replaced. [Live](https://vitram.baidpankaj567.workers.dev) | 129-operation FastAPI API, 656 tests (88% coverage), k6 213 req/s per process (synthetic) |
| [Warrantgate](https://github.com/pankajbaid567/warrantgate) | Gateway for MCP agent tool calls: policy engine, human approvals, hash-chained audit log | 374-trace synthetic attack suite, 78.9% held-out recall; 8/8 injected bugs caught |

## Backend and systems projects

| Project | What it is | Evidence |
|---|---|---|
| [Pitbook](https://github.com/pankajbaid567/pitbook) | Crash-safe price-time matching engine in Go with a live order book | 1,000 SIGKILL runs, 0 failures; 1M-command property test |
| [Counterfoil](https://github.com/pankajbaid567/counterfoil) | Double-entry ledger and payment orchestration in Java 21 / Spring Boot / Postgres. [Live](https://counterfoil-demo-m5wl.onrender.com) | 1,000 SIGKILL runs, 0 violations; 7/7 injected bugs caught |
| [Resilient TaskFlow](https://github.com/pankajbaid567/Resilient_Taskflow) | Crash-safe job queue: Postgres outbox, fenced leases, Redis Streams | 0 of 10,000 jobs lost on SIGKILL; 300+ tests |
| [Drumlin](https://github.com/pankajbaid567/drumlin) | LSM-tree key-value store in Go (single node) | 1,000 SIGKILL runs, 0 violations |

## Open source
- [Hugging Face Transformers #42373](https://github.com/huggingface/transformers/pull/42373): fixed a TensorDict padding regression.
- [AOSSIE Ell-ena #76](https://github.com/AOSSIE-Org/Ell-ena/pull/76), [#78](https://github.com/AOSSIE-Org/Ell-ena/pull/78): PostgreSQL row-level-security fixes.

## Achievements
- Team rank 8 on the public leaderboard, Amazon ML Challenge 2026 (about 80,000 registered).
- CodeChef 3-star (rating 1638); 600+ DSA problems solved across platforms.
- Winner, LMNIT-AOSSIE Unstoppable Hackathon; 2nd place, app-development hackathon at IIT Roorkee Cognizance.

## Stack
**Languages:** Python, TypeScript, JavaScript, Go, Java, C++, SQL
**AI:** RAG, hybrid retrieval, embeddings (e5, BGE), cross-encoder reranking, Qdrant, FAISS, Gemini, MCP, LangGraph, evaluation (nDCG, recall, abstention)
**Backend and data:** FastAPI, Node.js, Express, Fastify, Spring Boot, PostgreSQL, Redis, MongoDB
**Cloud and tools:** Cloudflare Workers / D1 / Queues, Render, Neon, AWS EC2, Docker, GitHub Actions, k6

## Contact
[LinkedIn](https://www.linkedin.com/in/pankaj-baid/) · [LeetCode](https://leetcode.com/u/baidpankaj567/) · [CodeChef](https://www.codechef.com/users/baidpankaj567) · pankaj.baid2024@nst.rishihood.edu.in
