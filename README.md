### Hi there, I'm Christopher – aka @computerguycj 👋

I'm a .NET engineer who fixes weird, slow, legacy systems and makes them behave again. These days I'm also figuring out what real engineering looks like when AI agents write a big share of the code. I still own the design, the integration, and what happens in production.

I think about software from the product side - why we're building it, who it affects, and what breaks when it ships.

### What I'm tinkering with right now

- 🤖 **Agent-first workflows.** I run Claude Code as an agent across my repos, sometimes several sessions at once in the cloud, not just as autocomplete. My repos have `CLAUDE.md` / `AGENTS.md` files so any agent that shows up knows the house rules.
- 🧠 **Giving agents a memory.** Context windows forget things, so my repos keep an append-only `DECISIONS.md` log. The agent reads it at the start of a session and asks me to log a decision when we pick one approach over another. It's plain markdown for now; I'll reach for something like Beads if decisions ever need a real dependency graph.
- ✅ **Context hygiene.** [SessionChecklist](https://github.com/computerguycj/SessionChecklist) is a tiny always-on-top widget that nags me to scope a session up front, hand over before the context gets noisy, and save state at the end. It's about 200 lines of PowerShell with no dependencies.
- 🗃️ **[caniusesql.com](https://www.caniusesql.com).** It's like caniuse.com, but for SQL features across PostgreSQL, MySQL, SQLite, SQL Server, and Oracle. It's a static-site generator on Vercel, and the data is maintained with agents under a human-reviewed PR flow.
- 🦙 **Local LLMs.** [blog-monitor](https://github.com/computerguycj/blog-monitor) is written in Go and uses a local Ollama model to analyze my blog for free, falling back to a hosted model in CI.
- ⚡ **Homelab stuff.** [power-monitor](https://github.com/computerguycj/power-monitor) is a Raspberry Pi that texts my phone when the power goes out, using a Kasa smart plug and ntfy.

A ground rule for all of it: I only ship code I clearly own the rights to. No "clean room" AI reimplementations of other people's work, and open source licenses count in both spirit and letter.

### Off the keyboard

- 📫 Find me on LinkedIn: https://www.linkedin.com/in/computerguycj/
- 🎲 I love strategic board games (Power Grid is my favorite).
- 🚲 I ride a bicycle for exercise and for fun.
- 📘 One of my favorite books is [Debugging by David J. Agans](https://www.oreilly.com/library/view/debugging/9780814474570/) — it's dated in all the right ways, which is exactly why I love it.

### Languages and Tools

- C#, ASP.NET, .NET (Framework & Core), SQL
- JavaScript/TypeScript, React, Angular, HTML, CSS
- Go, Python, PowerShell
- Claude Code (agents, cloud sessions, `CLAUDE.md`/`AGENTS.md` conventions), GitHub Copilot, Ollama
