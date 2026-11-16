# 公开知识资源的按需使用

核心研究与写作流程可独立使用。需要具体训练、可视化或排版工具时，在当前环境中发现对应资源，再阅读其说明。公开包不记录任何个人计算机上的安装位置，也不携带外部库、课程或作业原件。

## 科研与深度学习

| 任务 | 可检索的技能/资源名称 | 使用重点 |
|---|---|---|
| 研究选题 | brainstorming-research-ideas | 可验证问题、候选比较与可行性 |
| 问题重述 | creative-thinking-for-research | 隐藏假设、替代表示与机制设计 |
| 证据评价 | scientific-critical-thinking | 事实、假设、偏差及实验依据 |
| 研究记录 | scientific-brainstorming | 假设、反证条件和候选登记 |
| 网络训练 | ml-training-recipes | 优化器、训练循环、表示和调试 |
| 经典单智能体RL | stable-baselines3 | 环境接口、训练、评估与模型保存 |
| RL环境吞吐 | pufferlib | 在明确存在性能瓶颈时研究并行与吞吐 |
| 学术写作 | ml-paper-writing、scientific-writing | 论证结构、引用核验与证据一致性 |

公开资源入口：[AI-Research-SKILLs](https://github.com/Orchestra-Research/AI-Research-SKILLs)、[Scientific Agent Skills](https://github.com/K-Dense-AI/scientific-agent-skills)。实际使用时核查维护状态、许可证、版本及具体实现。

LLM微调、RLHF和GRPO资源服务于特定训练任务，不自动适用于供应链物流控制。先按研究问题选择方法，再判断是否需要相应工具。

## 绘图与文档

- 可用的nature-figure：图形问题定义、风格和导出检查。
- [Academic Figure Skill](https://github.com/TingxiYu/academic-figure-skill)：图形类型、布局与模板参考。
- [AgentFigureGallery](https://github.com/Dsadd4/AgentFigureGallery)：视觉参考检索与构图参考。
- academic-plotting、scientific-visualization：定量绘图、配色和出版参数。

根据用户选择使用MATLAB、Python或R。已有参考图、配色和后端选择时直接继承当前要求。只绘图无需额外建立Simulink仿真。DOCX、PDF或LaTeX按实际交付需求选择工具并检查最终页面。

外部技能缺失时仍可使用本包的通用指导；仅在实现确有需要时查阅官方文档或原始论文。不要批量安装无关依赖，不把工具默认参数当作业务事实。
