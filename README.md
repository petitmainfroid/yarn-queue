# 织线工坊（Yarn Queue）

一个可玩的手机竖屏休闲解谜游戏：布面是一幅彩色针织图案，点击左侧同色线轴把同色针脚拆成线球送入底部 3 格加工队列，队列按节拍消化线球并清空针脚；队列满或线轴用完即败。

- 玩法规格来源：Yarn Flow（拆织供给）× Food Hunt（消化队列）的核心机制融合
- 生成方式：RecursiveGameCreator（Designer→Builder）+ DeepSeek 作为编码 Agent
- 技术：单文件 HTML + Canvas 2D，无外部依赖、无网络请求，可离线运行
- 操作：点击线轴或按键盘 1 / 2 / 3；R 键重置
