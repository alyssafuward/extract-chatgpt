# ChatGPT Me

Turn your ChatGPT export into a Claude-ready working profile — in your browser, with no data leaving your computer.

## What it does

ChatGPT builds up a lot of implicit context about how you work: your topics, your style, how you phrase things. When you switch to Claude, that context is lost.

This tool reads your ChatGPT export, strips out all the AI responses, and produces a clean file of just your messages — plus a ready-made prompt that asks Claude to analyze how you work and generate a personal system prompt you can reuse in every future conversation.

## How to use

1. [Download `chatgpt-me.html`](https://github.com/alyssafuward/chatgpt-me/releases/latest) from the latest release
2. Open it in any browser — no install, no internet required
3. Export your ChatGPT data: **ChatGPT → Settings → Data Controls → Export Data**
4. Drop your export (ZIP or JSON files) into the tool
5. Set a size limit if you want (default is 10 MB)
6. Edit the analysis prompt if you want to customize what Claude looks for, then download both output files: your extracted data and the prompt
7. Open Claude, attach both files, and paste the cover message the tool provides

Claude will analyze your history and return a working profile plus a system prompt tailored to you.

## Privacy

Everything runs locally in your browser. No data is uploaded anywhere. The tool works fully offline once the HTML file is open.

## License

MIT
