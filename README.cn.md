# claude_code_src

[English version](./README.md)

2026.3.31 claude code 意外把包含源码的文件上传到 npm 仓库，版本号是 2.1.88，其中 cli.js.map 文件有 57MB 的体积，claude code 的源码在该文件的 sourcesContent 字段里面，解压还原后有 70w 行代码

![claude_code_src](https://repo.x-cmd.io/claude_code_src.svg?lang=zh)

## 安装

```sh
x install claude_code_src
```

## 代码洞察

合计: **757,653** 行代码（覆盖前 5 种语言、共 **4757** 个文件）。

| 语言 | 代码 | 注释 | 空行 | 文件数 |
|------|-----:|-----:|-----:|------:|
| JavaScript | 352,421 | 83,733 | 25,708 | 2850 |
| TypeScript | 288,021 | 71,157 | 30,683 | 1354 |
| Tsx | 117,211 | 12,994 | 3,014 | 552 |
| Markdown | 0 | 70 | 44 | 1 |

## 源代码

- **上游仓库**: <https://github.com/ponponon/claude_code_src>
- **许可证**: NOASSERTION

## 发布

- **最新版本**: `2.1.88` (2026-04-01)
- **最近提交**: 2026-04-15
- **Release 含资产**: 1 个

## 流行度

- **Star**: 2,337 · **Fork**: 3,527 · **开放 issue**: 6 · **贡献者**: 1

## 累计统计

- **发布数**: 1 · **已合并 PR**: 0 · **开放 PR**: 1 · **已关闭 issue**: 1 · **开放 issue**: 5 · **提交数**: 21

## 最近活动

| 时间窗口 | 起始 | 发布 | 已合并 PR | 开放 PR | 已关闭 issue | 开放 issue | 提交 |
|---|---|---:|---:|---:|---:|---:|---:|
| 30d | 2026-08-13 | 0 | 0 | 0 | 0 | 0 | 0 |
| last60d | 2026-07-14 | 0 | 0 | 1 | 0 | 0 | 0 |
| 90d | 2026-06-14 | 0 | 0 | 1 | 0 | 0 | 0 |
| last180d | 2026-03-16 | 1 | 0 | 1 | 1 | 5 | 21 |
| 360d | 2025-09-17 | 1 | 0 | 1 | 1 | 5 | 21 |
| last720d | 2024-09-22 | 1 | 0 | 1 | 1 | 5 | 21 |

## Release 资产

| 资产 | 大小 | 目标平台 |
|------|-----:|----------|
| [claude-code-2.1.88.tgz](https://github.com/ponponon/claude_code_src/releases/download/2.1.88/claude-code-2.1.88.tgz) | 29.8 MiB | `native/unknown` |

## 改进这些数据

claude_code_src 的安装元数据由 [x-cmd/install](https://github.com/x-cmd/install) 索引维护——这是一份由 x-cmd 在安装时读取的精选 YAML 包列表。如果 `claude_code_src` 缺失、过期，或安装行为有问题，欢迎在该 repo 提 issue 或 PR：

- **提交 issue**: <https://github.com/x-cmd/install/issues/new>
- **编辑包条目**: <https://github.com/x-cmd/install/edit/main/claude_code_src.yml>（或索引实际使用的路径）

本页面的数据（card / loc / scorecard / release）由 [x-cmd-install-action](https://github.com/x-cmd-install/x-cmd-install-action) 自动采集，每日重新生成。**安装行为**（版本选择、平台差异、依赖处理）的改进应提交到上游索引。

_数据快照: `data/card/260912.yml` · 2026-09-12T04:48:18Z._
