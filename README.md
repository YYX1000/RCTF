# Robotics CTF (RCTF) (Maintenance Branch)
> **Original Project Declaration**  
> This project is built based on RCTF, following the GNU General Public License v3.0.  
> Original project author: [aliasrobotics], original repository: [https://github.com/aliasrobotics/RCTF](https://github.com/aliasrobotics/RCTF)
> **The original project is no longer maintained.**

> **Maintenance Declaration**  
> Since 2026, this project has been maintained by YYX1000, focusing on security updates and feature improvements.  
> Maintenance branch address: `https://github.com/YYX1000/RCTF`

## 📄 License
This project is released under the GNU GPL v3 license. See the [LICENSE](LICENSE) file for details.

**Important**: As a GPL v3 project:
1. You are free to use, modify, and distribute this software
2. **But any derivative work based on this project must also be open source under GPL v3**
3. You must retain the complete copyright and license notices

中文: [中文文档](README-zh.md)

<a href="http://www.aliasrobotics.com"><img src="./image/alias.png" align="left" hspace="8" vspace="2" width="200"></a>



The [Robotics Capture the Flag](https://aliasrobotics.com/ctf.htm) (Robotics CTF or RCTF) is a locally deployed CTF range built using Docker, which can be launched via Docker. and designed to learn robot hacking step by step while competing with other security researchers. In an attempt to facilitate reproduction of results and further customization (common when researching vulnerabilities), this repository provides a list with open source reference scenarios that run in our Robotics CTF.

This repository contains a list of the scenarios available in the Robotics CTF

| Scenario | Short description | Author/s | Status |
|-----|-----|------|------|
| [rctf-scenario1](https://github.com/YYX1000/rctf-scenario1) | Unprotected topics show a lot of interesting information. Search on them to get your answer. Useful tools: rostopic  | [aliasrobotics](https://github.com/aliasrobotics)  | Active |
| [rctf-scenario2](https://github.com/YYX1000/rctf-scenario2) | In ROS2, even if security measures are available, not configuring them leverages to the same results as in ROS1. Useful tools: ros2 topic | [aliasrobotics](https://github.com/aliasrobotics) | Active |
| [rctf-scenario3](https://github.com/aliasrobotics/rctf-scenario3) |  The dinosaurs are out of control, and the node that controls the gates is not letting us in. Try to guess what the node wants so you can access the next scenario. | [aliasrobotics](https://github.com/aliasrobotics) | Active |
| [rctf-scenario4](https://github.com/aliasrobotics/rctf-scenario4) | Even if collaborative robots are fun to play with, if they are out of control, they can be dangerous too! Try to hit our friend, Pruden, with the robot in order to get the flag. | [aliasrobotics](https://github.com/aliasrobotics) | Active |
| [rctf-scenario5](https://github.com/aliasrobotics/rctf-scenario5) | There is a topic that has the flag, but rostopic has been disabled. Try to use alternative methods in order to get it. | [aliasrobotics](https://github.com/aliasrobotics) | Active |
| [rctf-scenario6](https://github.com/aliasrobotics/rctf-scenario6) | To know more about the topics and the communications between the nodes, use our footprinting tool, called Aztarna. | [aliasrobotics](https://github.com/aliasrobotics) | Active |

## Contributing
We invite security researchers to create their own robotics security scenarios and share them with the community. We accept such contributions through [Pull Request](https://github.com/aliasrobotics/rctf/pulls). To create your own scenario, start from [this simple template](https://github.com/aliasrobotics/rctf-scenario1).

## Cite our work

[![Article](https://img.shields.io/badge/article-arxiv%3A1812.09490-red.svg)](https://arxiv.org/pdf/1810.02690.pdf)

If you're using our work for your research, please cite us as:
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
