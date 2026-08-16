# agent-flow-site

Website for [AgentFlow](https://github.com/kanghelyu/agent-flow) — a single hand-written `index.html` (no framework, no build step) with bilingual EN/中文 UI, a typing terminal hero, screenshot gallery and copyable install commands.

Served via GitHub Pages at <https://agentflow.kanghelyu.org>.

- `index.html` — the whole site (CSS + JS inline, zero dependencies)
- `shots/` — product screenshots exported from the AgentFlow Studio
- `CNAME` — custom domain

## Update screenshots

Run the Studio locally (`af studio`), switch language/theme in the top bar, take 1440×900 shots, save as `shots/{en,zh}-{light,dark,logic}.png` plus a 360×400 `shots/pet-dark.png`.
