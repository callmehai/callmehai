<div align="center">

<img src="assets/hero.svg?v=3" alt="Problem V. Hải — input: messy real-world workflows, output: software people can trust" width="760" />

</div>

### Statement

**Hải** is a backend developer and competitive programmer from Hanoi, and a 🥇 **First Prize** winner of the Vietnam Student Olympiad in Informatics 2024 (specialized IT division).
He builds the backend side of AI products: LLM agents, speech features, and the APIs, data and security that keep them correct in production.

Given a product idea, find the simplest system that still survives real users. Tests first, small steps, fail safely.

### Input

A product idea, a pile of half-written requirements, and a language model that is confident about everything.

### Output

A backend that stays correct: clear APIs, sound data models, access control, and tests that say why.

### Example

```text
input                                    output
──────────────────────────────────────   ──────────────────────────────────────────
an assistant that sells over chat        streaming LLM agent + orders + payments
two hours of meeting audio               transcript → AI-drafted minutes → PDF/DOCX
a UI that "looks AI-generated"           sloplint
```

### Constraints

```text
1 ≤ languages ≤ { Go, Python, C#, TypeScript, C++ }
backend      ∈ { net/http, FastAPI, ASP.NET Core, LangGraph }
data         ∈ { PostgreSQL, Redis, MongoDB, NATS }
ships with     Docker · CI · TDD
```

### Submissions

| # | Problem | Verdict | Lang |
| --- | --- | --- | --- |
| 1 | [sloplint](https://github.com/callmehai/sloplint): catch the UI patterns that make a front-end look AI-generated | ✅ Accepted | JavaScript |
| 2 | [Workspace Hub](https://github.com/callmehai/workspace-hub): Gmail, Calendar, Drive & Jira in one Kanban, two-way sync | ✅ Accepted | C#, TypeScript |
| 3 | [ScanGo](https://github.com/callmehai/scango): snap a product label, get OCR + an AI explanation | ✅ Accepted | JavaScript, C# |
| 4 | [Violympic Mini Games](https://github.com/callmehai/violympic-game): real-time quiz games for ~50 players with a live leaderboard | ✅ Accepted | JavaScript |
| 5 | [Template-ICPC](https://github.com/callmehai/Template-ICPC): my contest notebook (HLD, Li Chao, CHT, geometry…) | ✅ Accepted | C++ |

### Note

🥇 First Prize, [Vietnam Student Olympiad in Informatics 2024](https://www.facebook.com/FPTU.HCM/posts/1049116450591528/), specialized IT division. Started out at the Vietnam Olympiad in Informatics in high school, still solves a hard problem for fun.
Reach him on [LinkedIn](https://www.linkedin.com/in/hai-tran-viet-54273239a/).
