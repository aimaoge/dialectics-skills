# 实用辩证法 Skills 套件

一套源自《毛泽东选集》方法论的大众问题解决技能包，含 3 个可独立使用、互相配合的 Skill。

| Skill | 版本 | 用途 | 形态 |
|---|---|---|---|
| practical-dialectics | 7.0.0 | 复杂难题完整六步分析：对齐 → 摸事实 → 找矛盾 → 定方案 → 迈一步 → 看结果 → 握主动；含完成前自检、技能自评 | 完整版（SKILL.md + references + assets） |
| three-thoughts | 1.1.0 | 做事前 30 秒–2 分钟快速三思：值不值得 / 怎么做 / 后果与退路 | 单文件 2KB |
| mao-examples | 1.1.0 | 《毛泽东选集》一至四卷可复用例证资源库，任何 Skill / AI 对话可引用 | 单文件 |

## 三者关系
- **小事先三思**（three-thoughts），**大事走六步**（practical-dialectics），两个 skill 互相提示切换。
- 需要引毛选原文支撑时用 **mao-examples**；practical-dialectics 内置例证副本，与独立库保持同步（独立库为正式源）。

## 安装
把对应 skill 目录放进你的 AI 工具 skills 目录（例如 `~/.claude/skills/`、Cursor 的 `.cursor/rules/`），或在对话中引用其内容即可。

## 触发
三个 skill 均为自然触发（无需记忆关键词）：用户陈述困境、求分析、要做决定、说"三思"即自动启用。

## 版本记录
- **v7.0.0 / v1.1.0（当前）**：新增版本号与 MIT LICENSE、mao-examples 引文"原文/大意"格式规范、practical-dialectics 补 AI 侧自评、description 精简、内部例证副本加一致性声明。

## 许可
MIT License，可自由使用、修改、分发。
