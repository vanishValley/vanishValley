# Hi, I'm XuYingJie

**AI Agents · Computer Vision · Developer Tools**

AI 方向研究生，关注深度学习、计算机视觉，以及把模型接入实际工作流的工程实践。

这里记录我的项目与技术探索：用 **Java** 构建编程 Agent，用 **Python** 串联生成模型、图像处理和应用服务。

[Xcode Agent](https://github.com/vanishValley/Xcode) · [sevenCow](https://github.com/vanishValley/sevenCow) · [All repositories](https://github.com/vanishValley?tab=repositories)

## 代表项目

### [Xcode Agent](https://github.com/vanishValley/Xcode)

**一个用 Java 17 实现的终端编程助手。** 从读取代码、调用工具，到规划任务、多 Agent 协作和结果验收，探索编程 Agent 的完整执行过程。

| 方向 | 项目中的实现 |
| --- | --- |
| 执行与协作 | ReAct 工具循环、DAG 任务规划、并行 Worker 与 Reviewer、独立上下文的 Team 协作 |
| 上下文与扩展 | 会话持久化、上下文压缩、长期记忆、按需加载 Skills、MCP 工具接入 |
| 可靠性与验证 | 人工审批、任务取消与恢复、OpenTelemetry 观测、独立编译与行为验收 |

`Java 17` `Maven` `JUnit` `MCP` `OpenTelemetry`

[快速开始](https://github.com/vanishValley/Xcode#快速开始) · [Team 设计](https://github.com/vanishValley/Xcode/blob/main/docs/team-mode-implementation.md) · [记忆设计](https://github.com/vanishValley/Xcode/blob/main/docs/memory_design.md) · [评测设计](https://github.com/vanishValley/Xcode/blob/main/docs/agent-evaluation-design.md)

### [sevenCow · 2D 游戏素材生成器](https://github.com/vanishValley/sevenCow)

**把文字描述转成可以下载的游戏素材。** 支持角色、场景、道具、UI 和特效，串联提示词优化、图像与视频生成、背景移除、抽帧和精灵表导出。

| 方向 | 项目中的实现 |
| --- | --- |
| 生成流程 | DeepSeek 提示词优化，接入通义万象图像与视频生成 |
| 图像处理 | OpenCV 抽帧、rembg 去背、Pillow 裁剪与精灵表拼接 |
| 应用交付 | FastAPI 服务、生成任务状态查询、会话素材管理、PNG 与 JSON 元数据打包下载 |

`Python` `FastAPI` `OpenCV` `Pillow` `rembg`

[运行说明](https://github.com/vanishValley/sevenCow#快速开始) · [生成流程](https://github.com/vanishValley/sevenCow/blob/master/main.py) · [抽帧与精灵表](https://github.com/vanishValley/sevenCow/blob/master/frame_extractor.py)

## 我关注的工程问题

- **Agent 怎么持续完成任务？** 让工具调用、上下文管理、协作和失败恢复形成完整流程。
- **怎么判断一次修改真的有效？** 用可复现的任务、独立验收和运行记录检查结果。
- **生成结果怎么进入实际应用？** 把模型输出继续处理为可下载、有格式约定的素材。

## 技术与工具

| 领域 | 当前项目使用的技术 |
| --- | --- |
| Agent 与开发工具 | Java、Maven、JUnit、MCP、OpenTelemetry |
| AI 应用与视觉处理 | Python、FastAPI、OpenCV、Pillow、rembg |
| 模型接入 | DeepSeek、通义万象 |

欢迎通过项目 Issues 交流实现思路、使用反馈和改进建议。
