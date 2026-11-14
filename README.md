### Hi there

Backend engineer. I build CLI tools and skills that let AI coding agents (Claude Code, Codex, Cursor) do real work on a laptop: read the web, translate, send email, type into a browser, and write English that reads like a person wrote it.

I prefer a small CLI plus a skill file over an MCP server: less setup, fewer moving parts, and any agent with a shell can use it.

#### Tools I wrote

| Project | What it does | Stack |
|---|---|---|
| [not-a-bot](https://github.com/w21180239/not-a-bot) | Makes AI-written English read like a person wrote it, with every fact kept. CLI, agent skill and offline lint. On npm as [`not-a-bot-cli`](https://www.npmjs.com/package/not-a-bot-cli). | Rust |
| [translatex](https://github.com/w21180239/translatex) | Free translation CLI for agents and scripts. No API key, no signup, no config: 15 keyless engines raced in parallel, DeepL and other keyed APIs when you want them, JSON output, one 6 MB binary. | Rust |
| [claude-code-self-compact](https://github.com/w21180239/claude-code-self-compact) | Claude Code plugin that lets Claude compact its own context at task milestones, then carry on from its own notes. | TypeScript |
| [human-typing](https://github.com/w21180239/human-typing) | Lets an agent type into Chrome like a person: uneven keystrokes, typos fixed with Backspace, code pasted from the editor. | JavaScript |
| [outlook-cli-skill](https://github.com/w21180239/outlook-cli-skill) | Outlook email as agent skills, no MCP server needed. A small OAuth CLI plus curl-based skill files. | TypeScript |

#### Upstream contributions

17 merged pull requests into open-source agent tooling:

| Repository | Merged PRs | Examples |
|---|---|---|
| [tashfeenahmed/freellmapi](https://github.com/tashfeenahmed/freellmapi) | 7 | per-engine search test endpoint, key rotation for custom endpoints, boot-time encryption-key check |
| [Panniantong/Agent-Reach](https://github.com/Panniantong/Agent-Reach) | 4 | `skill unlink`, yt-dlp behind TLS proxies, Bilibili login hint |
| [career-ops-hq/career-ops](https://github.com/career-ops-hq/career-ops) | 3 | Avature job-link parsing, Windows test fixes |
| [CloakHQ/CloakBrowser](https://github.com/CloakHQ/CloakBrowser) | 1 | Playwright-compatible `context.close(reason=...)` |
| [NanmiCoder/MediaCrawler](https://github.com/NanmiCoder/MediaCrawler) | 1 | proxy/VPN SSL option |
| [T-Auto/dsh-ops](https://github.com/T-Auto/dsh-ops) | 1 | native root-listener fix |
