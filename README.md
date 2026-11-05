<p align="center">
  <img src="./assets/profile-hero.svg" alt="XuYingJie · AI Agent Engineering" width="100%" />
</p>

<p align="center">
  <strong>AI Agent 开发 · 计算机视觉</strong><br />
  AI 方向研究生，使用 Java、Python 和 Node.js 实现 Agent 与生成式 AI 应用。<br />
  关注工具调用、任务状态、失败处理，以及如何验证任务确实完成。
</p>

<p align="center">
  <a href="#精选项目">精选项目</a> &nbsp; / &nbsp;
  <a href="#实现与验证">实现与验证</a> &nbsp; / &nbsp;
  <a href="https://github.com/vanishValley?tab=repositories">全部仓库</a>
</p>

## 精选项目

<table>
<tr>
<td width="50%" valign="top">
<a href="https://github.com/vanishValley/Xcode"><img src="./assets/xcode-cover.svg" alt="Xcode Agent：规划、工具调用与验收" width="100%" /></a>
<h3><a href="https://github.com/vanishValley/Xcode">Xcode Agent</a></h3>
<p>Java 17 终端编程助手，包含模型执行循环、任务规划、工具系统和自动化评测。</p>
<ul>
  <li>ReAct、DAG 任务规划与多 Agent 协作</li>
  <li>会话与长期记忆、Skills、MCP 工具接入</li>
  <li>人工审批、取消恢复、OpenTelemetry 观测与独立验收</li>
</ul>
<p><code>Java 17</code> <code>Maven</code> <code>MCP</code> <code>OpenTelemetry</code></p>
<p><a href="https://github.com/vanishValley/Xcode#快速开始">运行指南</a> &nbsp; · &nbsp; <a href="https://github.com/vanishValley/Xcode/blob/main/docs/agent-evaluation-verification.md">验证记录</a></p>
</td>
<td width="50%" valign="top">
<a href="https://github.com/vanishValley/content-scheduling-agent"><img src="./assets/scheduling-cover.svg" alt="素材审核与发布排期 Agent：审核、时段查询与草稿确认" width="100%" /></a>
<h3><a href="https://github.com/vanishValley/content-scheduling-agent">素材审核与发布排期 Agent</a></h3>
<p>校招题目实践：模型依据工具结果处理素材风险与时段冲突，保存可供人工确认的排期草稿。</p>
<ul>
  <li>缺资料时补查或追问，冲突时选择备选时段</li>
  <li>硬性改期保留待确认，重复请求复用草稿</li>
  <li>29 项测试、12 组真实模型用例，以及误判后的修订记录</li>
</ul>
<p><code>Node.js</code> <code>Tool Calling</code> <code>Kimi</code> <code>Evaluation</code></p>
<p><a href="https://github.com/vanishValley/content-scheduling-agent/blob/main/docs/03-evaluation.md">实际输出与 Trace</a> &nbsp; · &nbsp; <a href="https://github.com/vanishValley/content-scheduling-agent/blob/main/docs/04-ai-usage.md">AI 辅助范围</a></p>
</td>
</tr>
</table>

### 相关应用：SpriteForge

[SpriteForge](https://github.com/vanishValley/SpriteForge) 是一个 Python / FastAPI 的 2D 游戏素材生成工具。它将提示词优化、图像与视频生成、抽帧、背景移除和精灵表导出串成工作流。

[运行指南](https://github.com/vanishValley/SpriteForge#快速开始) · [视频抽帧实现](https://github.com/vanishValley/SpriteForge/blob/master/frame_extractor.py) · [素材后处理](https://github.com/vanishValley/SpriteForge/blob/master/postprocess.py)

## 实现与验证

| 想了解的内容 | 代码与文档入口 |
| --- | --- |
| 多 Agent 如何分工和交付 | [Xcode Team 协作设计](https://github.com/vanishValley/Xcode/blob/main/docs/team-mode-implementation.md) |
| 上下文与长期记忆如何配合 | [Xcode 记忆设计](https://github.com/vanishValley/Xcode/blob/main/docs/memory_design.md) |
| 如何独立检查 Agent 的执行结果 | [Xcode 评测设计](https://github.com/vanishValley/Xcode/blob/main/docs/agent-evaluation-design.md) |
| 模型如何根据不同结果改变动作 | [排期 Agent 的真实执行记录](https://github.com/vanishValley/content-scheduling-agent/tree/main/examples/live) |
| 一次真实误判如何被发现和修正 | [缺资料场景的回归记录](https://github.com/vanishValley/content-scheduling-agent/tree/main/examples/regressions/missing-before-clarification) |

项目的运行条件、验证方式和限制写在各自 README 中。欢迎通过 [GitHub Issues](https://github.com/vanishValley/Xcode/issues) 交流实现细节。
