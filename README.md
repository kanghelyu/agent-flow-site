# AgentFlow website

Modern, dependency-free static website for [AgentFlow](https://github.com/kanghelyu/agent-flow).

## What is included

- `index.html` — full site, with CSS and JavaScript inline
- `assets/shots/` — AgentFlow Studio screenshots and artwork used by the PixelPets desktop-pet integration
- `favicon.svg`
- `CNAME`
- `.nojekyll`

## Features

- Responsive layout for desktop, tablet and mobile
- English / 简体中文 UI (auto-detects browser language and remembers the choice)
- Dark / light appearance with local preference persistence
- Smooth reveal, cursor spotlight, workflow motion, parallax and status micro-interactions
- `prefers-reduced-motion` accessibility fallback
- Live Studio screenshot switcher (dark / light / logic, English / Chinese) and full-size lightbox
- Recommended agent-driven install flow plus macOS/Linux, Windows and desktop-pet commands
- No framework, no external JavaScript, no external CSS, no font downloads, no analytics and no build step

## Deploy

Push the files in this directory to the root of `kanghelyu/agent-flow-site` and serve the repository with GitHub Pages.

The included `CNAME` keeps the custom domain:

`agentflow.kanghelyu.org`

## Desktop pet credit

The optional desktop-pet experience is powered by [PixelPets](https://github.com/JOhnsonKC201/pixelpets), created by [JOhnsonKC201](https://github.com/JOhnsonKC201) and released under the MIT License.

AgentFlow provides the workflow-status integration. The PixelPets project and pet artwork are not original AgentFlow work.

See `THIRD_PARTY_NOTICES.md` for the upstream license notice.
