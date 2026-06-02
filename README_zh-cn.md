# packages 简介

\[ [English](README.md) | 简体中文 \]

本项目采用顶层仓库（super repository）管理多个子仓库的方式进行组织。通过这种方式，可以更好地管理和维护不同部分的代码库，同时确保每个子仓库的独立性和灵活性。子仓库以 `packages` 字段开头。

## 子仓库列表

| 子仓库链接                                                   | 描述                                                         |
| ------------------------------------------------------------ | ------------------------------------------------------------ |
| [packages_ai_agent](../../../../open-vela/packages_ai_agent) | 运行在 openvela 上的端侧 AI Agent 框架，支持多 LLM 后端、35+ 内置工具、Skills 技能系统、主动任务与多渠道接入，约 256KB RAM 即可运行，是 AI 硬件应用开发的核心基座。 |
| [packages_demos](../../../../open-vela/packages_demos)       | 该仓库实现了 `openvela native` 应用代码示例，主要包括：<ul><li>音乐播放器</li><li>智能手环</li><li>自行车码表</li></ul> |
| [packages_fe_examples](../../../../open-vela/packages_fe_examples) | 该仓库实现了简单的 `openvela quickapp` 代码示例，主要包括：<ul><li>日历</li><li>计算器UI</li><li>播放器</li><li>任务清单</li><li>图表</li><li>设置UI</li></ul>在 **AIoT IDE 内置模拟器**中运行，仅供学习参考（参赛代码不提交至此）。 |
| [packages_apps](../../../../open-vela/packages_apps)         | 基于 openvela 的快应用（JS 应用）示例工程，按设备形态（音箱、穿戴等）组织，在 **openvela 模拟器**上运行。**大赛快应用赛道的参赛代码提交至此仓库。** |
