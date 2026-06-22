# 太吾绘卷百晓册本地知识库

这个仓库保存用于查询《太吾绘卷》(The Scroll of Taiwu) 游戏内「百晓册」Markdown 导出的公开说明文件。

本仓库不分发游戏原始导出内容。带有原作者版权的百晓册导出应只保存在本地的 `EncyclopediaExporter_Output/` 目录中；该目录已被 `.gitignore` 排除，不会进入公开仓库。

## 本地目录约定

把百晓册 Markdown 导出放在：

```text
EncyclopediaExporter_Output/
```

导出目录通常包含：

- 12 个章节目录：`主页`、`启程`、`世界`、`门派`、`人物`、`交互`、`修习`、`战斗`、`产业`、`物品`、`游历`、`扩展`
- `词条/`
- `章节大纲.md`

## Agent 使用

- [AGENTS.md](AGENTS.md) 是 Codex / agent 的仓库工作说明。
- [CLAUDE.md](CLAUDE.md) 是 Claude Code 和其他 agent 的检索说明。
- 回答游戏机制、物品、门派、武学、数值等问题时，应以本地 `EncyclopediaExporter_Output/` 的文件为依据，不要凭记忆编造。

## 许可证

本仓库公开文件使用 [MIT License](LICENSE)。

MIT License 仅覆盖本仓库实际提交的说明文件，不覆盖本地忽略的游戏原始导出内容，也不授予《太吾绘卷》或其百晓册内容的任何权利。
