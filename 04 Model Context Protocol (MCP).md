---
created: 2025-05-08T13:59
updated: 2025-05-08T14:57
---
## What is MCP?
Model Context Protocol (which we'll refer to as MCP from hereon in this page) by Anthropic is an open standard for web servers to be able to provide a list of tools that AI agents can call to be executed by the server.

Anthropic wrote a blog post [introducing Model Context Protocol](https://www.anthropic.com/news/model-context-protocol) if you'd like to dive more deeply into the specification.

## Registering an MCP server
To register an MCP server, follow the steps below:
- Click the "MCP" tab on the top right hand corner of your page.
- On the page will be a button called "Register" and then below that will be a list of MCP servers you can add. Click the "Add" button on any of the servers listed to add them.
- Once you've made all the changes you need to the list of MCP servers you want to use, click Register and it'll register all of them for usage.

## Using registered MCP servers with Arc Studio
Currently there are two main ways we support MCP usage - see the links provided for more information:
- [Add it](/02-D MCP nodes.md) as a standalone tool to your workflow
- [Pass it](/02-B AI nodes.md) to an agent and let AI do the work for you
