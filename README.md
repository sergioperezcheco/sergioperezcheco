<picture>
  <source media="(max-width: 680px)" srcset="./assets/profile-mobile.svg">
  <img src="./assets/profile-light.svg" alt="Checo — security research, open source, and systems" width="100%">
</picture>

<br>

I investigate software vulnerabilities, contribute fixes to open-source projects, and build tools for the systems I use. My interests meet at **application security, developer tooling, infrastructure, and ML on Apple Silicon**.

[Security research](#security-research) · [Merged contributions](#merged-contributions) · [Projects](#projects) · [Writing](https://blog.checo.cc)

---

## Security research

### CVE-2026-78847 · Code execution in `gray-matter`

**The issue.** The parser’s built-in JavaScript front-matter engine evaluates code supplied by a document. I reproduced the behavior in `gray-matter` 4.0.3, traced why explicitly setting the language to YAML does not prevent it, and verified mitigations.

**The outcome.** I requested a CVE for the library where the flaw lives, rather than only its downstream consumers. The CVE is published. The record does not yet list finder credit. An [earlier upstream PR](https://github.com/jonschlinkert/gray-matter/pull/182) had already reported the issue; this is independent validation and CVE coordination, **not a claim of first discovery**.

[Read the investigation ↗](https://blog.checo.cc/en/posts/Security/1) &nbsp; · &nbsp; [CVE record ↗](https://www.cve.org/CVERecord?id=CVE-2026-78847) &nbsp; · &nbsp; [GitHub advisory ↗](https://github.com/advisories/GHSA-j9gx-vjm3-jpmm)

## Merged contributions

Bug fixes and implementation work accepted into upstream repositories. Every entry links to the merged pull request.

| Repository | What landed |
| :--- | :--- |
| **[Keycloak ↗](https://github.com/keycloak/keycloak/pull/51217)** | Fixed an exception when Base64URL input consists only of padding. |
| **[Dify ↗](https://github.com/langgenius/dify/pull/38280)** | Replaced `db.paginate` with plain SQLAlchemy pagination. |
| **[LocalSend ↗](https://github.com/localsend/localsend/pull/3212)** | Corrected the WebRTC selection-publish failure path. |
| **[browser-use ↗](https://github.com/browser-use/browser-use/pull/5264)** | Restored completion callbacks for remote-browser downloads. |
| **[Composio ↗](https://github.com/ComposioHQ/composio/pull/3890)** | Fixed a trigger shutdown deadlock and subscription timeout leak. |
| **[yuque-dl ↗](https://github.com/gxr404/yuque-dl/pull/102)** | Added a command to download all books in one run. |

[Browse all merged pull requests →](https://github.com/pulls?q=is%3Apr+author%3Asergioperezcheco+is%3Amerged)

## Projects

| | |
| :--- | :--- |
| **[CodexQuota](https://github.com/sergioperezcheco/CodexQuota)** | A macOS menu-bar monitor for AI coding subscription usage. |
| **[DeDeBayer](https://github.com/sergioperezcheco/DeDeBayer)** | Explore Bayer CFA and demosaicing algorithms, including RAW files. [Live demo ↗](https://dedebayer.pages.dev) |
| **[llm-from-scratch](https://github.com/sergioperezcheco/llm-from-scratch)** | Train a tiny GPT from scratch using MLX on Apple Silicon. |
| **[PR Dashboard](https://github.com/sergioperezcheco/pr-dashboard)** | Track open-source PRs and reviews. [Live dashboard ↗](https://home.checo.cc/pr-dashboard/) |

## GitHub activity

<img src="https://github-stats-extended.vercel.app/api?username=sergioperezcheco&amp;show_icons=true&amp;hide_title=true&amp;rank_icon=github&amp;bg_color=ffffff&amp;title_color=24292f&amp;text_color=57606a&amp;icon_color=57606a&amp;border_color=d8dce0" alt="Checo's GitHub statistics" width="495">

<sub>Live third-party data; counts may lag behind GitHub or omit private activity.</sub>

---

[Home](https://home.checo.cc) &nbsp; · &nbsp; [Blog](https://blog.checo.cc) &nbsp; · &nbsp; [Docs](https://docs.checo.cc) &nbsp; · &nbsp; [Telegram](https://t.me/iiiiiikun)
