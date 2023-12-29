# GraphGPT
<div id="top" align="center">

   | [English](README.md) | [中文](docs/README-zh-Hans.md) |

</div>

### 自然语言 → 知识图谱

![demo](demo.gif)

GraphGPT将非结构化的自然语言转换为知识图。输入你最喜欢的电影的概要，一个令人困惑的维基百科页面的段落，或者一个视频的文字记录来生成实体及其关系的图形可视化。

连续的查询可以更新图的现有状态或创建一个全新的结构。例如，更新当前状态可能涉及通过节点和边缘注入新信息或更改某些节点的颜色。

查看完整的提示词`public/prompts/main.prompt`和`public/prompts/main-zh.prompt`。

## 提示词

提示符位于`public/prompts`文件夹。阅读这些 [推特帖子](https://twitter.com/varunshenoy_/status/1625224544561819648?s=20) ，以了解更多关于这些提示是如何设计的。

## 安装与运行

1. 运行 `npm install` 下载所需的依赖项 (目前只依赖 [react-graph-vis](https://github.com/crubier/react-graph-vis)) 。
2. 运行 `npm run start`后， GraphGPT可以在一个新的浏览器选项卡中打开。
