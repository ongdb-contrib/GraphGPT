# GraphGPT
<div id="top" align="center">

   | [English](README.md) | [中文](docs/README-zh-Hans.md) |

</div>

### Natural Language → Knowledge Graph

![demo](demo.gif)

GraphGPT converts unstructured natural language into a knowledge graph. Pass in the synopsis of your favorite movie, a passage from a confusing Wikipedia page, or transcript from a video to generate a graph visualization of entities and their relationships. 

Successive queries can update the existing state of the graph or create an entirely new structure. For example, updating the current state could involve injecting new information through nodes and edges or changing the color of certain nodes.

The current few-shot prompt guides GPT-3 in accurately understanding the JSON formatting GraphGPT requires for proper rendering. You can see the entire prompt in `public/prompts/main.prompt` & `public/prompts/main-zh.prompt`.

## Prompts

Prompts are located in the `public/prompts` folder. Read [this](https://twitter.com/varunshenoy_/status/1625224544561819648?s=20) Twitter thread I put together to learn more about how these prompts were designed.

## Setup

1. Run `npm install` to download required dependencies (currently just [react-graph-vis](https://github.com/crubier/react-graph-vis)).
2. Run `npm run start`. GraphGPT should open up in a new browser tab.
