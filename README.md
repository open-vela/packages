# Packages Overview

\[ English | [简体中文](README_zh-cn.md) \]

This project is organized by managing multiple sub-repositories within a top-level repository (also known as a super repository). This approach allows for better management and maintenance of different parts of the codebase while ensuring the independence and flexibility of each sub-repository.The sub-repositories are prefixed with the packages field.

## Sub-repository list

| Sub-repository link | Description |
| ------------------------------------------------------------ | ------------------------------------------------------------ |
| [packages_ai_agent](../../../../open-vela/packages_ai_agent) | An on-device AI Agent framework running on openvela, supporting multiple LLM backends, 35+ built-in tools, a Skills system, proactive tasks, and multi-channel access. It runs with around 256KB of RAM and serves as the core foundation for AI hardware application development. |
| [packages_demos](../../../../open-vela/packages_demos) | This repository contains code examples for `openvela native` applications, mainly including: <ul><li>Music Player</li><li>Smart Band</li><li>Bicycle Computer</li></ul> |
| [packages_fe_examples](../../../../open-vela/packages_fe_examples) | This repository contains basic `openvela quickapp` code examples, mainly including: <ul><li>Calendar</li><li>Calculator UI</li><li>Player</li><li>Todolist</li><li>Chart</li><li>Settings UI</li></ul>They run in the **AIoT IDE built-in emulator**, for learning reference only (contest code is not submitted here). |
| [packages_apps](../../../../open-vela/packages_apps) | Quick App (JS application) example projects built on openvela, organized by device form factor (speaker, wearable, etc.), running on the **openvela emulator**. **Contest Quick App track submissions are committed to this repository.** |
