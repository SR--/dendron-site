---
id: hEDGu1KqxTsSUASO2gW6U
title: Prune
desc: ''
updated: 1623699891291
created: 1623699719673
---

## Legacy Note Graph
- [[Pruning ✂️|dendron.ref.status#pruning-️]]

Dendron provides support for graph view using a fork of the [markdown-links](https://marketplace.visualstudio.com/items?itemName=tchayen.markdown-links) extension.

The Dendron graph view is generated using our hierarchical index. It also shows different relationships than most of the graph views you're probably used to.

Instead of showing edges as links between nodes, Dendron edges are the hierarchical relationships between your notes. Think of it as a 20,000 foot view of the structure of your knowledge base.

Note that this command is not optimized for performance and you might notice slowdowns if you have more than a few hundred notes. If you are running into performance issues, please upvote this [issue](https://github.com/dendronhq/dendron/issues/107) to prioritize the performance work!

### Commands

#### Dendron: Show Note Graph

Launch the command bar (see [link](https://www.dendron.so/notes/401c5889-20ae-4b3a-8468-269def4b4865.html#launch-the-command-bar) for info): `> Dendron: Show Note Graph`

Show your note hierarchies visually in a graph.

![](https://foundation-prod-assetspublic53c57cce-8cpvgjldwysl.s3-us-west-2.amazonaws.com/assets/images/graph.show-notes.gif)

#### Dendron: Show Schema Graph

Launch the command bar (see [link](https://www.dendron.so/notes/401c5889-20ae-4b3a-8468-269def4b4865.html#launch-the-command-bar) for info): `> Dendron: Show Schema Graph`

Show your note schemas visually in a graph. Schemas will be labelled by their `title` attribute. If `title` is not set, default to its `id`.

![](https://foundation-prod-assetspublic53c57cce-8cpvgjldwysl.s3-us-west-2.amazonaws.com/assets/images/graphs.show-schema.gif)

#### Dendron: Sync Note Graph

Updates the note graph with most recent changes

#### Dendron: Sync Schema Graph

Updates the schema graph with most recent changes
