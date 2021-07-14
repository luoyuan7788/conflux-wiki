# 简介



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

## Material color palette 颜色主题

### Color Scheme 配色方案

根据浏览器与系统设置自动切换明暗主题，也可手动切换
<div class="tx-switch">
<button data-md-color-scheme="default"><code>Default</code></button>
<button data-md-color-scheme="slate"><code>Slate</code></button>
</div>
<script>
  var buttons = document.querySelectorAll("button[data-md-color-scheme]")
  Array.prototype.forEach.call(buttons, function(button) {
    button.addEventListener("click", function() {
      document.body.dataset.mdColorScheme = this.dataset.mdColorScheme;
      localStorage.setItem("data-md-color-scheme",this.dataset.mdColorScheme);
    })
  })
</script>

### Primary colors 主色

点击色块可更换主题的主色
<div class="tx-switch">
<button data-md-color-primary="red"><code>Red</code></button>
<button data-md-color-primary="pink"><code>Pink</code></button>
<button data-md-color-primary="purple"><code>Purple</code></button>
<button data-md-color-primary="deep-purple"><code>Deep Purple</code></button>
<button data-md-color-primary="indigo"><code>Indigo</code></button>
<button data-md-color-primary="blue"><code>Blue</code></button>
<button data-md-color-primary="light-blue"><code>Light Blue</code></button>
<button data-md-color-primary="cyan"><code>Cyan</code></button>
<button data-md-color-primary="teal"><code>Teal</code></button>
<button data-md-color-primary="green"><code>Green</code></button>
<button data-md-color-primary="light-green"><code>Light Green</code></button>
<button data-md-color-primary="lime"><code>Lime</code></button>
<button data-md-color-primary="yellow"><code>Yellow</code></button>
<button data-md-color-primary="amber"><code>Amber</code></button>
<button data-md-color-primary="orange"><code>Orange</code></button>
<button data-md-color-primary="deep-orange"><code>Deep Orange</code></button>
<button data-md-color-primary="brown"><code>Brown</code></button>
<button data-md-color-primary="grey"><code>Grey</code></button>
<button data-md-color-primary="blue-grey"><code>Blue Grey</code></button>
<button data-md-color-primary="white"><code>White</code></button>
</div>
<script>
  var buttons = document.querySelectorAll("button[data-md-color-primary]");
  Array.prototype.forEach.call(buttons, function(button) {
    button.addEventListener("click", function() {
      document.body.dataset.mdColorPrimary = this.dataset.mdColorPrimary;
      localStorage.setItem("data-md-color-primary",this.dataset.mdColorPrimary);
    })
  })
</script>

### Accent colors 辅助色

点击色块更换主题的辅助色
<div class="tx-switch">
<button data-md-color-accent="red"><code>Red</code></button>
<button data-md-color-accent="pink"><code>Pink</code></button>
<button data-md-color-accent="purple"><code>Purple</code></button>
<button data-md-color-accent="deep-purple"><code>Deep Purple</code></button>
<button data-md-color-accent="indigo"><code>Indigo</code></button>
<button data-md-color-accent="blue"><code>Blue</code></button>
<button data-md-color-accent="light-blue"><code>Light Blue</code></button>
<button data-md-color-accent="cyan"><code>Cyan</code></button>
<button data-md-color-accent="teal"><code>Teal</code></button>
<button data-md-color-accent="green"><code>Green</code></button>
<button data-md-color-accent="light-green"><code>Light Green</code></button>
<button data-md-color-accent="lime"><code>Lime</code></button>
<button data-md-color-accent="yellow"><code>Yellow</code></button>
<button data-md-color-accent="amber"><code>Amber</code></button>
<button data-md-color-accent="orange"><code>Orange</code></button>
<button data-md-color-accent="deep-orange"><code>Deep Orange</code></button>
</div>
<script>
  var buttons = document.querySelectorAll("button[data-md-color-accent]");
  Array.prototype.forEach.call(buttons, function(button) {
    button.addEventListener("click", function() {
      document.body.dataset.mdColorAccent = this.dataset.mdColorAccent;
      localStorage.setItem("data-md-color-accent",this.dataset.mdColorAccent);
    })
  })
</script>

<style>
button[data-md-color-accent]> code {
    background-color: var(--md-code-bg-color);
    color: var(--md-accent-fg-color);
  }
button[data-md-color-primary] > code {
    background-color: var(--md-code-bg-color);
    color: var(--md-primary-fg-color);
  }
button[data-md-color-primary='white'] > code {
    background-color: var(--md-primary-bg-color);
    color: var(--md-primary-fg-color);
  }
button[data-md-color-accent],button[data-md-color-primary],button[data-md-color-scheme]{
    width: 8.4rem;
    margin-bottom: .4rem;
    padding: 2.4rem .4rem .4rem;
    transition: background-color .25s,opacity .25s;
    border-radius: .2rem;
    color: #fff;
    font-size: .8rem;
    text-align: left;
    cursor: pointer;
}
button[data-md-color-accent]{
  background-color: var(--md-accent-fg-color);
}
button[data-md-color-primary]{
  background-color: var(--md-primary-fg-color);
}
button[data-md-color-scheme='default']{
  background-color: hsla(0, 0%, 100%, 1);
}
button[data-md-color-scheme='slate']{
  background-color: var(--md-default-bg-color);
}
button[data-md-color-accent]:hover, button[data-md-color-primary]:hover {
    opacity: .75;
}
</style>