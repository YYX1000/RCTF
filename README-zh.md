# Robotics CTF (RCTF)（维护分支）
> **原项目声明**  
> 本项目基于 RCTF 构建，遵循 GNU General Public License v3.0。  
> 原项目作者：[aliasrobotics]，原仓库：[https://github.com/aliasrobotics/RCTF](https://github.com/aliasrobotics/RCTF)
> **原项目已停止维护。**

> **维护声明**  
> 自 2026 年起，本项目由YYX1000维护，专注于安全更新和功能改进。  
> 维护分支地址：`https://github.com/YYX1000/RCTF`

## 📄 许可证
本项目在 GNU GPL v3 许可证下发布。详见 [LICENSE](LICENSE) 文件。

**重要**：作为 GPL v3 项目：
1. 您可以自由使用、修改和分发本软件
2. **但任何基于本项目的衍生作品也必须使用 GPL v3 开源**
3. 您必须保留完整的版权和许可证声明

<a href="http://www.aliasrobotics.com"><img src="./image/alias.png" align="left" hspace="8" vspace="2" width="200"></a>



机器人CTF [Robotics Capture the Flag](https://aliasrobotics.com/ctf.htm) 是使用docker搭建的一个ctf本地靶场，可通过docker启动，并旨在通过与其他安全研究人员竞争的方式逐步学习机器人黑客技术。为了便于结果的复制和进一步定制(这在研究漏洞时很常见)，该存储库提供了一份包含开源参考场景的列表，这些场景在我们的机器人CTF中运行。

此仓库包含机器人CTF中可用的场景列表

| Scenario | Short description | Author/s | Status |
|-----|-----|------|------|
| [rctf-scenario1](https://github.com/aliasrobotics/rctf-scenario1) | 未加密 / 未受保护的话题会暴露大量敏感信息，对这些话题进行检索即可获取答案。实用工具：rostopic  | [aliasrobotics](https://github.com/aliasrobotics)  | Active |
| [rctf-scenario2](https://github.com/aliasrobotics/rctf-scenario2) | 在 ROS2环境下, 即便存在对应的安全防护机制，未对其进行配置，最终导致的后果也会和 ROS1 中（无防护）的情况完全一致。实用工具：ros2 topic | [aliasrobotics](https://github.com/aliasrobotics) | Active |
| [rctf-scenario3](https://github.com/aliasrobotics/rctf-scenario3) |  恐龙已经失控，控制闸门的节点拒绝让我们进入。试着猜一猜这个节点想要什么，你就能解锁进入下一个场景。 | [aliasrobotics](https://github.com/aliasrobotics) | Active |
| [rctf-scenario4](https://github.com/aliasrobotics/rctf-scenario4) | 就算协作机器人玩起来很有趣，可一旦失控，它们也会变得十分危险！试着操控机器人去撞击我们的朋友普鲁登，以此拿到旗帜。 | [aliasrobotics](https://github.com/aliasrobotics) | Active |
| [rctf-scenario5](https://github.com/aliasrobotics/rctf-scenario5) | 有一个话题中存放着旗帜（flag），但rostopic工具已被禁用，请尝试使用其他替代方法来获取它。 | [aliasrobotics](https://github.com/aliasrobotics) | Active |
| [rctf-scenario6](https://github.com/aliasrobotics/rctf-scenario6) | ROS 安全靶场 / CTF 的工具使用提示，指引你用 Aztarna 工具完成信息搜集，获取话题与节点通信信息。 | [aliasrobotics](https://github.com/aliasrobotics) | Active |

## 贡献
我们诚挚邀请安全研究人员创建属于他们自己的机器人安全实验场景，并与社区共享。我们将通过 [拉取请求](https://github.com/aliasrobotics/rctf/pulls)渠道接收此类投稿. 若要创建你自己的实验场景， [简易模板](https://github.com/aliasrobotics/rctf-scenario1).请从这个开始。

## Cite our work

[![Article](https://img.shields.io/badge/article-arxiv%3A1812.09490-red.svg)](https://arxiv.org/pdf/1810.02690.pdf)

如果你的研究工作中使用了我们的成果，请按以下方式引用我们:
```
@ARTICLE{rctf,
   author = {{Olalde Mendia}, G. and {Usategui San Juan}, L. and {Perez Bascaran}, X. and
    {Bilbao Calvo}, A. and {Hern{\'a}ndez Cordero}, A. and {Zamalloa Ugarte}, I. and
    {Mu{\~n}iz Rosas}, A. and {Mayoral Vilches}, D. and {Ayucar Carbajo}, U. and
    {Alzola Kirschgens}, L. and {Mayoral Vilches}, V. and {Gil-Uriarte}, E.
    },
    title = "{Robotics CTF (RCTF), a playground for robot hacking}",
  journal = {ArXiv e-prints},
archivePrefix = "arXiv",
   eprint = {1810.02690},
 primaryClass = "cs.CY",
 keywords = {Computer Science - Computers and Society, Computer Science - Robotics},
     year = 2018,
    month = oct,
   adsurl = {http://adsabs.harvard.edu/abs/2018arXiv181002690O},
  adsnote = {Provided by the SAO/NASA Astrophysics Data System}
}
```
