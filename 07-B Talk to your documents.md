## Talk to your documents
An extremely popular use case for AI is "talking to your documents" - essentially putting the entire document into a context window and then asking it questions, setting the system prompt and regular prompt accordingly. This allows your model to use the information provided from your document as a data source to provide the answer.

## Pre-requisites
Before we get started, you'll need a document to upload to Arc Studio. Unsure what document types we support? Check out [our documentation page on input nodes](/02-A Input Nodes.md) which should have you covered. You will also additionally need some API key credentials for whatever model provider you would like to use.

## Getting Started
To get started, create a new workflow or ensure you already have a workflow created that you want to use. Open it and navigate to the Nodes menu on the left hand side of the screen.

## Building our workflow
If you click into the Input Nodes, you should have an option to add a file input node. Drag it onto the canvas to add it to your workflow, then upload the file into it.

Next, create an AI node by navigating to the node bar on the left hand side of the screen, clicking "AI Nodes" and then dragging an AI agent node onto your canvas. Connect the input node to your AI node by dragging the right-hand connector of your input node to the left-hand connector of your AI node.

Set up your AI node by clicking the gear icon on the top right of the node, then set your model and API key for whichever model provider you want to use.

Once you're done, simply go to the bottom right of your AI node where there will be a message box to send questions to your AI agent node and you can ask it any questions you'd like!

## Extending this example
Of course, there is always more that we can do. One simple way to extend this is to connect the input of an output node to the output of an AI node and have the display in rich text format. This is particularly useful for reports and tables, where you might want better text formatting.
