### 王楠 Nan Wang

大连理工大学管理科学与工程博士（2027 年 3 月毕业），曾在加拿大 McMaster 大学联合培养 15 个月。研究方向是**联邦因果推断**、**运筹优化**和**大模型 Agent 应用**：数据分散在多家机构、不能集中时，如何估计干预效果、如何协同优化。

正在寻找 2027 届因果推断 / 策略算法、大模型 Agent 应用、运筹优化算法相关岗位。

PhD candidate in Management Science and Engineering at Dalian University of Technology (graduating March 2027), with a 15-month joint PhD stay at McMaster University. I work on federated causal inference, operations research and LLM agents.

#### 项目 Projects

| 项目 | 做什么 | 技术 |
|---|---|---|
| **联邦断点回归** federated-rdd | 多家机构不共享个体数据，联合完成精确 / 模糊断点回归；各方只上传求和统计量，联邦估计与合并数据上的估计逐位相同，结果与 rdrobust 一致 | Python · NumPy · SciPy |
| **联邦分支定价** federated-branch-and-price | 多家工厂不暴露设备参数，协同完成一份下料订单；Dantzig–Wolfe 分解 + 联邦列生成 + 三阶段分支。270 个合成实例上平均 gap 1.03%，各厂独立求解为 48.42% | Python · Gurobi |
| **多智能体科研系统** | 基于 Claude Code 的科研流水线：29 个 agent、5 个阶段、8 个人工检查点、4 个自动质量门，12 个 JSON Schema 校验每次交接 | Claude Code · Python |
| **联邦倾向得分匹配** | 用联邦随机森林估计倾向得分，再做联邦匹配，估计平均处理效应；另有面板数据版本 FPSM-DID | Python · scikit-learn |

前三个项目的相关论文尚未发表，代码暂为私有仓库，可应邀查看。
The first three projects are in private repositories until the related papers are published; access is available on request.

#### 已发表 Publications

- Yang Liu, **Nan Wang**\*, Xin Ye. Federated propensity score matching: a method for estimating average treatment effect based on data in islands. *Annals of Operations Research*, 2025. [DOI: 10.1007/s10479-025-06823-1](https://doi.org/10.1007/s10479-025-06823-1)

#### 技能 Skills

Python（NumPy、pandas、SciPy、scikit-learn）· 因果推断（PSM、DID、RDD、因果森林）· 运筹优化（Gurobi、OR-Tools、Pyomo、cvxpy、列生成）· Claude Code 多智能体编排 · LaTeX

#### 联系 Contact

wnan66@mail.dlut.edu.cn
