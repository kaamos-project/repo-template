# Project name wiki

One paragraph on what the project is, who it is for and how it fits in Kaamos Project.

> **Status**: not started. These pages are the skeleton of the wiki: each one says what it will contain. Fill them in as the project takes shape.

## Pages

| Page | What you will find |
|---|---|
| [Getting started](getting-started.md) | Requirements, how to run it, the checks CI runs, repo layout |
| [Architecture](architecture.md) | Layers and modules, with a diagram |
| [Decisions](decisions.md) | The key choices and their trade-offs |

Add one page per important flow and link it here. Start new pages from [the page template](page-template.md).

## Writing these pages

- One page per topic, in English, linked with relative links only (they work on GitHub, offline and on any other forge).
- Every page starts with a `[Home](README.md) › Page` breadcrumb and ends with "See also".
- Prefer a Mermaid diagram to a long paragraph when you explain a flow: GitHub renders it.
- Explain the **why**, not only the what. Choices with trade-offs go in [Decisions](decisions.md).
- A pull request that changes behaviour also updates the page that describes it.
