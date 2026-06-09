# isheng-mind — 八字命理分析 (BaZi Destiny Analysis)

以《滴天髓》思想为核心的 Claude Code 技能包，分析八字命盘的内在能量体验与自我感受。

## 这是什么？

如果说人生是一趟旅行，那八字就是这趟旅行的地图和天气预报。借此工具了解把握自己的地图和天气预报，找到自己人生的最优道路。

`isheng-mind` 是一个 Claude Code 自定义技能（Skill），严格遵循《滴天髓》理法，分析命主的内在能量体验：
- 日主强弱判定
- 五行气势与结构需求
- 通关之法（最优五行调和方案）
- 大运流年的内在感受变化

**不论外在人事，直言结论，按能量等级排序。**

## 前置要求

需要为 Claude Code 部署 MCP 工具 `mingpan`：
```
请为我部署mingpan这个mcp
```

## 安装

将本仓库克隆到 Claude Code 的 skills 目录：

```bash
cd ~/.claude/skills/
git clone https://github.com/isheng-eqi/isheng-mind.git
```

或直接下载整个文件夹放到 `~/.claude/skills/isheng-mind/`。

## 使用

在 Claude Code 对话中输入：
```
/isheng-mind
```
或直接说"帮我分析这个八字"，Claude 会自动触发此技能。

## 古籍参考

本技能包含 7 本古籍全文作为分析参考：

| 古籍 | 说明 |
|------|------|
| 《滴天髓》原文 | 核心理论框架 |
| 《滴天髓阐微》 | 任铁樵注解 |
| 《三命通会》 | 万民英著 |
| 《子平真诠》 | 沈孝瞻著 |
| 《渊海子平》 | 徐大升编 |
| 《神峰通考》 | 张楠著 |
| 《穷通宝鉴》 | 余春台著 |

## 许可证

MIT
