# Checo

Security research, open source, and systems engineering.

I investigate software vulnerabilities, contribute fixes to projects I use, and build practical tools for developers and infrastructure. [Blog](https://blog.checo.cc) · [Home](https://home.checo.cc)

## Security research

**[CVE-2026-78847](https://www.cve.org/CVERecord?id=CVE-2026-78847)** · `gray-matter` · JavaScript front-matter code execution

I independently reproduced the issue in `gray-matter` 4.0.3, traced the vulnerable parsing path, tested mitigations, and requested a CVE for the library itself. An earlier [upstream PR](https://github.com/jonschlinkert/gray-matter/pull/182) had already documented the issue; I do not claim first discovery. The CVE record is published, but its finder credit has not yet been added.

[Technical write-up](https://blog.checo.cc/en/posts/Security/1) · [GitHub advisory](https://github.com/advisories/GHSA-j9gx-vjm3-jpmm)

## Open-source contributions

Selected merged pull requests:

| Project | What changed |
| --- | --- |
| [Keycloak](https://github.com/keycloak/keycloak/pull/51217) | Fixed `Base64Url` crashing on padding-only input. |
| [Dify](https://github.com/langgenius/dify/pull/38280) | Replaced `db.paginate` with plain SQLAlchemy pagination. |
| [LocalSend](https://github.com/localsend/localsend/pull/3212) | Fixed WebRTC error handling during selection publishing. |
| [browser-use](https://github.com/browser-use/browser-use/pull/5264) | Restored completion callbacks for remote-browser downloads. |
| [Composio](https://github.com/ComposioHQ/composio/pull/3890) | Fixed a trigger shutdown deadlock and subscription timeout leak. |
| [yuque-dl](https://github.com/gxr404/yuque-dl/pull/102) | Added a command to download all books in one run. |

[All merged pull requests](https://github.com/pulls?q=is%3Apr+author%3Asergioperezcheco+is%3Amerged)

## Projects

- [CodexQuota](https://github.com/sergioperezcheco/CodexQuota) — macOS menu-bar monitor for AI coding subscription usage.
- [DeDeBayer](https://github.com/sergioperezcheco/DeDeBayer) — interactive Bayer CFA and demosaicing visualizer with RAW support. [Live demo](https://dedebayer.pages.dev)
- [llm-from-scratch](https://github.com/sergioperezcheco/llm-from-scratch) — train a tiny GPT with MLX on Apple Silicon.
- [PR Dashboard](https://github.com/sergioperezcheco/pr-dashboard) — track my open-source pull requests. [Live dashboard](https://home.checo.cc/pr-dashboard/)

---

[Blog](https://blog.checo.cc) · [Docs](https://docs.checo.cc) · [Telegram](https://t.me/iiiiiikun)
