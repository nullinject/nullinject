# nullinject · Void Prompt

**AI 安全研究 · 取证自动化 · 安全工具开发**

关注 Prompt Injection、Agent 信任边界与数字取证，记录可核查的实验、证据和工具实现。

[个人网站](https://nullinject.github.io/) · [研究文章](https://nullinject.github.io/articles.html) · [项目目录](https://nullinject.github.io/projects.html)

## 代表作品 · MemoryAI Forensics

将 LangGraph 工作流、Volatility 与 YARA 整合为内存取证调查流程，串联镜像分析、证据交叉验证、案件管理与报告输出。

[![MemoryAI Forensics 分析过程：实时日志、阶段进度与证据调查工作台](https://raw.githubusercontent.com/nullinject/MemoryAI-Forensics-Showcase/main/assets/demo-analysis.png)](https://github.com/nullinject/MemoryAI-Forensics-Showcase#product-preview)

[查看项目与界面](https://github.com/nullinject/MemoryAI-Forensics-Showcase#product-preview) · [阅读技术设计](https://github.com/nullinject/MemoryAI-Forensics-Showcase/blob/main/Technical_Design.md)

公开仓库用于展示系统能力、界面与技术方案；完整工程实现位于私有研发仓库。

## 研究与工具

| 项目 | 关注的问题 | 从这里开始 |
| --- | --- | --- |
| [LLM Security Research](https://github.com/nullinject/llm-security-research) | 提示注入、RAG 文档投毒、Skill 供应链与模型输出误导。 | [研究案例索引](https://github.com/nullinject/llm-security-research/blob/main/README.md) |
| [ShadowProbe](https://github.com/nullinject/shadowprobe) | 从主机快照识别安全产品，展示匹配置信度与证据。 | [功能与启动说明](https://github.com/nullinject/shadowprobe/blob/main/README.md) |
| [Xiaomi Photo Recovery](https://github.com/nullinject/xiaomi-photo-recovery) | 从可访问的 Android 缓存、缩略图和回收站提取媒体，生成结果清单。 | [合成数据演示](https://github.com/nullinject/xiaomi-photo-recovery/blob/main/examples/synthetic_demo.py) |
| [CTF AWD Toolkit](https://github.com/nullinject/ctf-awd-toolkit) | 比赛环境的服务巡检、文件基线、备份恢复与提交队列。 | [离线练习](https://github.com/nullinject/ctf-awd-toolkit/blob/main/OFFLINE.md) |
| [CPR Excel Companion](https://github.com/nullinject/cpr-excel-companion) | CPR 插件中的协议适配、附件上传、路由管理与请求监控。 | [安装与兼容说明](https://github.com/nullinject/cpr-excel-companion/blob/main/README.md) · [发布记录](https://github.com/nullinject/cpr-excel-companion/releases) |

CPR Excel Companion 当前为实验性候选版本，兼容范围与已知边界以对应版本文档为准。Xiaomi Photo Recovery 的定位是缓存媒体提取，不能恢复已覆盖数据。

## 研究笔记

- [角色诱导、虚构证据与安全边界漂移](https://github.com/nullinject/llm-security-research/blob/main/DeepSeek-Role-Induction-and-Evidence-Fabrication.md)
- [RAG 文档投毒与间接提示注入](https://github.com/nullinject/llm-security-research/blob/main/RAG-Indirect-Prompt-Injection.md)
- [Agent Skill 供应链安全](https://github.com/nullinject/llm-security-research/blob/main/OpenClaw-Skill-Supply-Chain-Attack.md)

## 其他作品与交流

[ShiftPaw · 班次喵](https://github.com/nullinject/ShiftPaw)：macOS 桌面排班提醒工具，用桌宠、班次倒计时与系统通知跟踪交接。

欢迎通过相关项目的 Issues 交流使用反馈、研究问题与改进建议。
