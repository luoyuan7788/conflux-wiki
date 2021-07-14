# Conflux Wiki


[中文](./README-zh_CN.md)  [English](./README.md)

欢迎来到 **Conflux Wiki**。

**Conflux**（树图）缘起清华大学，经大量学术研究提出了区块链“不可能三角”的最优解：树图（Tree-Graph）共识机制，有效平衡了安全性、延展性和去中心化程度。

2018 年，**Conflux** 基金会成立并完成融资。2019 年第二季度，Conflux 测试网上线。

作为中国区块链基础设施的先行者，**Conflux** 网络始终坚持推动区块链开发及教育等相关工作。2019 年 9 月 25 日，**Conflux** 杭州运营中心正式揭牌。2020 年 1 月 9 日，上海树图区块链研究院正式揭牌。2020 年 8 月 19 日，湖南湘江树图区块链创新中心暨区块链底层技术及应用湖南省重点实验室揭牌。

**Conflux** 网络团队由来自四个大洲的超过 50 名成员构成，不同化的文化让 **Conflux** 始终保持多元化，其办公室设立在加拿大多伦多、尼日利亚拉各斯等地。

在**Conflux** 上进行智能合约开发，体验生态涉及众多领域，内容繁杂。与此同时，区块链技术的发展速度越来越快，**Conflux** 初学者面对的门槛越来越高。而网上资料大都零散琐碎，初学者往往并不知道该如何系统性地学习 与**Conflux** 相关领域知识，常需要花费大量时间，苦不堪言。

受到 [ctf-wiki](https://github.com/ctf-wiki/ctf-wiki) 项目成功的鼓舞，为了使得热爱 **Conflux** 的小伙伴们更好地入门 **Conflux**，2021 年 7 月份，**Conflux Wiki** 在 Github 有了第一次 commit。

作为一个自由的站点，围绕 **Conflux** 这一基础网络设施近几年的发展，**Conflux Wiki** 对 **Conflux** 中的各个方向的知识和技术进行介绍，以便于初学者更好地学习 **Conflux** 网络相关的知识。

目前，**Conflux Wiki** 主要包含构建 **Conflux** 区块链各大范畴的基础知识，生态体验教程，并正在着力完善以下内容

- 区块链智能合约安全知识
- Conflux 底层机制解析
- 智能合约开发

关于上述部分待完善内容，请参见 Conflux Wiki 的 [Projects](https://github.com/Conflux-wiki/Conflux-wiki/projects)，详细列出了正在做的事项以及待做事项。

当然，**Conflux Wiki** 基于 **Conflux**，却不会局限于 **Conflux**。在未来，**Conflux Wiki** 将会

- 介绍更多基于Conflux开发的生态
- 并更多地与区块链开发实战结合

此外，鉴于以下两点

- 技术应该以开放的方式共享。
- 技术总是在不断演进，旧的技术在面对新的技术时可能失效。

因此，**Conflux Wiki** 永远不会出版书籍。

最后，**Conflux Wiki** 源于社区，作为**独立的组织**，提倡**知识自由**，在未来也绝不会商业化，将始终保持**独立自由**的性质。

## How to build？

本文档目前采用 [mkdocs](https://github.com/mkdocs/mkdocs) 部署在 [https://ctf-wiki.org](https://ctf-wiki.org)。

本项目可以直接部署在本地，具体方式如下：

```shell
# 1. clone
git clone https://github.com/ctf-wiki/ctf-wiki.git
# 2. requirements
pip install -r requirements.txt
# generate static file in site/
python3 scripts/docs.py build-all
# deploy at http://127.0.0.1:8008
python3 scripts/docs.py serve
```

**mkdocs 本地部署的网站是动态更新的，即当你修改并保存 md 文件后，刷新页面就能随之动态更新。**

> 注意：在使用 mkdocs-material 的 insiders 版本后，暂时不支持 docker 构建。

如果你只是想本地浏览，并不想修改文档？试试 Docker 把！

```
docker run -d --name=ctf-wiki -p 4100:80 ctfwiki/ctf-wiki
```
随后即可在浏览器中访问 [http://localhost:4100/](http://localhost:4100/) 阅读 CTF Wiki 。

## How to practice？

首先，通过在线阅读来学习一些基本的安全知识。

其次，CTF Wiki 还有两个姊妹项目

- CTF Wiki 中涉及的题目在 [ctf-challenges](https://github.com/ctf-wiki/ctf-challenges) 仓库中，请根据对应的分类自行寻找。
- CTF Wiki 中涉及的工具会不断补充到 [ctf-tools](https://github.com/ctf-wiki/ctf-tools) 仓库中。

## How to make CTF Wiki Better？

我们非常欢迎你为 Wiki 编写内容，将自己的所学所得与大家分享。我们期待着你的加入！

**在你决定要贡献内容之前，请你务必看完 [CONTRIBUTING](https://ctf-wiki.org/en/contribute/before-contributing/)**。其中包含了详细的贡献方式。 

非常感谢一起完善 CTF Wiki 的小伙伴们

<a href="https://github.com/ctf-wiki/ctf-wiki/graphs/contributors"><img src="https://opencollective.com/ctf-wiki/contributors.svg?width=890&button=false" /></a>

## What can you get?

- 快速学习新事物的能力
- 不一样的思考方式
- 乐于解决问题的心
- 有趣的安全技术
- 充实奋斗的时光

在阅读 Wiki 之前，我们希望能给予你几点建议：

- 学习 [提问的智慧](https://github.com/ryanhanwu/How-To-Ask-Questions-The-Smart-Way)
- 善用 Google 搜索能帮助你更好地提升自己
- 至少掌握一门编程语言，比如 Python
- 动手实践比什么都要管用
- 保持对技术的好奇与渴望并坚持下去

> 世界很大，互联网让世界变小，真的黑客们应该去思考并创造，无论当下是在破坏还是在创造，记住，未来，那条主线是创造的就对了。 ——by 余弦

安全圈很小，安全的海洋很深。安全之路的探险，不如就从 **CTF Wiki** 开始！

## Copyleft
<a rel="license" href="http://creativecommons.org/licenses/by-nc-sa/4.0/"><img alt="知识共享许可协议" style="border-width:0" src="https://i.creativecommons.org/l/by-nc-sa/4.0/88x31.png" /></a><br />本作品采用<a rel="license" href="http://creativecommons.org/licenses/by-nc-sa/4.0/">知识共享署名-非商业性使用-相同方式共享 4.0 国际许可协议</a>进行许可。

