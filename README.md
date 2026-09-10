# claude_code_src

[中文版本](./README.cn.md)

2026.3.31 claude code 意外把包含源码的文件上传到 npm 仓库，版本号是 2.1.88，其中 cli.js.map 文件有 57MB 的体积，claude code 的源码在该文件的 sourcesContent 字段里面，解压还原后有 70w 行代码

![claude_code_src](https://repo.x-cmd.io/claude_code_src.svg)

## Install

```sh
x install claude_code_src
```

## Source

- **Upstream**: <https://github.com/ponponon/claude_code_src>
- **License**: NOASSERTION

## Release

- **Latest**: `2.1.88` (2026-04-01)
- **Last commit**: 2026-04-15
- **Assets in release**: 1

## Release assets

| Asset | Size | Target |
|-------|-----:|--------|
| [claude-code-2.1.88.tgz](https://github.com/ponponon/claude_code_src/releases/download/2.1.88/claude-code-2.1.88.tgz) | 29.8 MiB | `native/unknown` |

## Popularity

- **Stars**: 2,337 · **Forks**: 3,527 · **Open issues**: 6 · **Contributors**: 1

## Totals (cumulative)

- **Releases**: 1 · **Merged PRs**: 0 · **Open PRs**: 1 · **Closed issues**: 1 · **Open issues**: 5 · **Commits**: 21

## Recent activity

| Window | Since | Releases | Merged PRs | Open PRs | Closed issues | Open issues | Commits |
|---|---|---:|---:|---:|---:|---:|---:|
| 30d | 2026-08-11 | 0 | 0 | 0 | 0 | 0 | 0 |
| 90d | 2026-06-12 | 0 | 0 | 1 | 0 | 0 | 0 |
| 360d | 2025-09-15 | 1 | 0 | 1 | 1 | 5 | 21 |

## Code size

Total: **757,653** lines of code across **4757** files in the top 5 languages.

| Language | Code | Comments | Blanks | Files |
|----------|-----:|---------:|-------:|------:|
| JavaScript | 352,421 | 83,733 | 25,708 | 2850 |
| TypeScript | 288,021 | 71,157 | 30,683 | 1354 |
| Tsx | 117,211 | 12,994 | 3,014 | 552 |
| Markdown | 0 | 70 | 44 | 1 |

## Improve this data

Install metadata for claude_code_src lives in the [x-cmd/install](https://github.com/x-cmd/install) index — a curated YAML package list that x-cmd consumes at install time. If `claude_code_src` is missing, out of date, or installs incorrectly, please open an issue or PR there:

- **Open an issue**: <https://github.com/x-cmd/install/issues/new>
- **Edit the package entry**: <https://github.com/x-cmd/install/edit/main/claude_code_src.yml> (or whichever path the index uses)

The data on this page (card / loc / scorecard / release) is auto-collected by [x-cmd-install-action](https://github.com/x-cmd-install/x-cmd-install-action) and is regenerated daily. Improvements to *install behaviour* (which version gets installed, platform-specific quirks, dependencies) belong upstream in the index.

_Snapshot: `data/card/260910.yml` · 2026-09-10T16:47:18Z._
