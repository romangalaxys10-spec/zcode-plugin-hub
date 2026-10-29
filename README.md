# ZCode Plugin Hub

Index of every public ZCode plugin we publish. Each entry is its own repo,
self-installable: clone it, add it as a plugin marketplace in ZCode
(**Plugin Marketplace -> Add -> Add Plugin Marketplace**, paste the folder path),
and install from there.

Built for and tested with [ZCode](https://zcode.z.ai), the desktop AI coding agent.
New here? [Try ZCode free](https://zcode.z.ai/invite/ALWM9JUA) or grab a
[coding plan with 10% off](https://z.ai/subscribe?ic=R0K78RJKNW).

## Productivity

| Plugin | What it does |
|--------|--------------|
| [last-mile](https://github.com/romangalaxys10-spec/zcode-last-mile) | Kills the "last 20%": scans an almost-finished project for unfinished edges and closes them, one commit per item |
| [context-forge](https://github.com/romangalaxys10-spec/zcode-context-forge) | Session hygiene for long builds: handoff briefs, codebase-derived conventions, refreshable state |
| [beginner-pilot](https://github.com/romangalaxys10-spec/zcode-beginner-pilot) | Guided mode for beginners: the agent narrates every step in plain language and builds a re-readable notebook |
| [skill-curator](https://github.com/romangalaxys10-spec/zcode-skill-curator) | Discover, search, audit, dedupe, install and remove skills and plugins from a local catalog |
| [phone-bridge](https://github.com/romangalaxys10-spec/zcode-phone-bridge) | Task completion pings to your phone over your own Telegram bot; outbound-only, no inbound control channel |
| [launchpad](https://github.com/romangalaxys10-spec/zcode-launchpad) | Turns recent commits into launch content: changelog, blog draft, X thread, LinkedIn, Reddit, Product Hunt copy |

## Vibe coding

| Plugin | What it does |
|--------|--------------|
| [mcp-doctor](https://github.com/romangalaxys10-spec/zcode-mcp-doctor) | Diagnoses and fixes MCP configs across clients; probes every server with a real handshake |
| [usage-dashboard](https://github.com/romangalaxys10-spec/zcode-usage-dashboard) | Token and cost dashboard from ZCode's own rollout logs, per day, session and model |
| [ui-polish](https://github.com/romangalaxys10-spec/zcode-ui-polish) | Design-mirror pass that fixes bad AI frontend output against a real design system |
| [pixel-review](https://github.com/romangalaxys10-spec/zcode-pixel-review) | Visual regression gate: pixel-diffs before/after screenshots and blocks broken "done" claims |
| [root-cause](https://github.com/romangalaxys10-spec/zcode-root-cause) | Debug-loop breaker: falsifiable repro, bisection, hypothesis-tested root cause, max 3 fix attempts |
| [ship-audit](https://github.com/romangalaxys10-spec/zcode-ship-audit) | Pre-launch gate: secrets, env completeness, debug flags, leaks; FAIL/WARN/PASS report |
| [dep-pin](https://github.com/romangalaxys10-spec/zcode-dep-pin) | Dependency honesty gate: verifies packages exist on npm/PyPI and versions are real before imports land |
| [git-story](https://github.com/romangalaxys10-spec/zcode-git-story) | Conventional commits with real intent, PR descriptions, weekly "what I built" digest |
| [prompt-lab](https://github.com/romangalaxys10-spec/zcode-prompt-lab) | A/B harness for prompts and skills: fixtures, fresh subagents per variant, rubric-scored verdict |

## More from us

| Plugin | What it does |
|--------|--------------|
| [memecoin-kill-relay](https://github.com/romangalaxys10-spec/memecoin-kill-relay) | Kill-first memecoin screening relay, five stages, one veto kills. Based on an X.com post, not verified or personally tested |
| [zcode-discord-research-agent](https://github.com/romangalaxys10-spec/zcode-discord-research-agent) | Research Discord servers with your own logged-in Firefox session; reports plus approval-gated replies |

## Recommended official plugin

| Plugin | What it does |
|--------|--------------|
| [chatgpt-headless](https://github.com/romangalaxys10-spec/zcode-chatgpt-headless) | Consults ChatGPT on your behalf from inside ZCode: second opinions, multi-model panels and silent auto-review of big edits, through headless calls to the official Codex backend using your own ChatGPT plan's tokens. Supported automation of your own account, not a workaround; also on the official ZCode marketplace |

## Install any of these in 3 steps

1. Clone or download the plugin repo to a folder on your machine.
2. In ZCode: **Plugin Marketplace -> Add -> Add Plugin Marketplace**, paste that folder path.
3. Open the market and click **Install** on the plugin.

Every repo has a root `marketplace.json`, so the folder itself is the marketplace.

## License

Each plugin is MIT licensed in its own repo. This index: MIT.

---

<p align="center">
  <a href="https://z.ai/subscribe?ic=R0K78RJKNW"><img alt="z.ai coding plans - 10% OFF coupon" src="https://img.shields.io/badge/z.ai%20coding%20plans-10%25%20OFF%20coupon-blueviolet" /></a>
  <a href="https://zcode.z.ai/invite/ALWM9JUA"><img alt="Try ZCode free" src="https://img.shields.io/badge/Try%20ZCode-free%20invite-0969da" /></a>
</p>
