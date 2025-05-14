---
created: 2025-05-08T13:59
updated: 2025-05-12T13:37
---
## Input nodes
Input nodes are the entrypoint of a workflow and can take several forms: text input, files (both audio and text), images and web pages. See below for more information.

## Currently supported types
The following input nodes are supported:

| Name        | Description                                                               |
| ----------- | ------------------------------------------------------------------------- |
| Text input  | Provides raw text for a given workflow                                    |
| Notepad     | A rich text editor for notes and content                                  |
| Web page    | Browse web pages and extract content as markdown                          |
| File input  | Upload a file and pass it to your agent (see below)                       |
| Audio input | Upload audio files and pass them to an AI agent or Whisper for processing |


In terms of file input, the following file extensions are supported:
- PDF (`.pdf`)
- Markdown (`.md`)
- Plain text (`.txt`)
- Comma-Separated Values `csv`
- Excel Spreadsheet (`.xlsx`)
- Word Document (`.doc`, `.docx`)

To add one to your workflow, simply drag it onto your canvas and one will be added for you where you dragged it.

There is only one node connector on the right hand side of an input node which will be to connect the output from this node to the input of the next node.
