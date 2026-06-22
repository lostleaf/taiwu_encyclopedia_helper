# 太吾绘卷百晓册本地知识库

这个仓库保存用于查询《太吾绘卷》(The Scroll of Taiwu) 游戏内「百晓册」Markdown 导出的公开说明文件。

本仓库不分发游戏原始导出内容。带有原作者版权的百晓册导出应只保存在本地的 `EncyclopediaExporter_Output/` 目录中；该目录已被 `.gitignore` 排除，不会进入公开仓库。

## 来源链接

- 游戏：[Steam 页面](https://store.steampowered.com/app/838350/) / [维基百科](https://zh.wikipedia.org/wiki/%E5%A4%AA%E5%90%BE%E7%BB%98%E5%8D%B7%EF%BC%9A%E5%A4%A9%E5%B9%95%E5%BF%83%E5%B8%B7)
- 百晓册导出工具：[Steam 创意工坊](https://steamcommunity.com/sharedfiles/filedetails/?id=3746603173) / [GitHub 仓库](https://github.com/l9metapod/TaiwuEncyclopediaExporter)

## 本地目录约定

把百晓册 Markdown 导出放在：

```text
EncyclopediaExporter_Output/
```

该目录中的数据由游戏 mod “百晓册导出 · AI攻略助手” 导出。

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
