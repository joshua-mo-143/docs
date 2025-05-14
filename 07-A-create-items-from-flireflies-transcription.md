## Creating action items from Fireflies AI transcriptions
[Fireflies](https://fireflies.ai/) is a third-party service for transcribing your Google Meet, Zoom and Microsoft Teams calls by leveraging AI. By inviting the Fireflies transcriber to your call, you can record the audio captured from any speaker within a given call and create action items. Fireflies also provides an API that Arc Studio provides an MCP server for through Ryzome. This allows our workflow agents to directly interact with Fireflies.

In this short guide, we'll get into how you can create an effective workflow on your canvas for visualising what the outcome of a meeting was and potentially create documents from it.

### Pre-requisites
Before you get started, make sure you have the Fireflies AI MCP server registered. Check out [our guide to using MCP](/Model Context protocol(MCP).md) if you're not sure how to register an MCP server. You will also additionally need some API key credentials for whatever model provider you would like to use.

This will also additionally require an API key from your Fireflies account which should have some pre-existing transcriptions. If you don't have any yet, try using Fireflies in your next meeting.

### Getting started
To get started, create a new workflow or ensure you already have a workflow created that you want to use. Open it and navigate to the Nodes menu on the left hand side of the screen.

### Building our workflow
Add an AI agent node by clicking the AI Node type menu, then dragging the relevant icon onto your canvas with your mouse. This will create an AI agent ready to work for you.

Once done, you can then edit the node by clicking the gearbox on top right of the node. This will bring up a number of options:
- The model you want to use (just use whichever one you want)
- The API key for the model provider of your choice
- System prompt
- MCP servers/tools

The model to be used and API keys are relatively simple: the model can be selected from a drop-down list, and assuming you've already stored an API key in Arc Studio you should be able to select it from the credentials drop-down list.

In terms of MCP servers, you will need to enable the Fireflies AI server capability by ticking the box and then it'll show a list of tools that you can enable or disable. We should enable the `get-transcript` and `get-user-transcripts` functions.

Once done, save the settings by clicking the Save button at the bottom of the settings menu and then it should be ready to go. Try sending your AI agent a message and it should return a response!

## Extending this use case
Once we're done, there's actually a lot more we can do here to be able to make our workflow even more effective.

While Fireflies is great for creating action items from meetings, there's more that we can do here. A couple of niche but immediately useful things that we can solve:
- Generating a list of pain points from a meeting with a user
- (assisting with) Generating a draft of a Product Requirements Document
