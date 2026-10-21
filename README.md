# 织线工坊（Yarn Queue）

一个可玩的手机竖屏休闲解谜游戏。布面是一幅彩色针织图案，点击左侧同色线轴，把同色针脚拆成线球送进底部 **3 格加工队列**；队列每 2 秒消化一个线球并清空对应针脚。

- **在线玩**：https://petitmainfroid.github.io/yarn-queue/
- **下载离线玩**：本仓库的 `index.html`（约 46 KB，单文件，右键另存为即可用浏览器打开；也可在 Pages 页面按 Ctrl/Cmd+S 保存）
- 操作：点击线轴，或按键盘 `1` / `2` / `3`；`R` 重置

## 玩法来源
- 机制融合：**Yarn Flow**（拆织供给）× **Food Hunt**（等待队列消化）
- 生成方式：RecursiveGameCreator（Designer → Builder）+ DeepSeek 作为编码 Agent
- 技术：单文件 HTML + Canvas 2D，零外部依赖、零网络请求、零数据上报，可完全离线运行
