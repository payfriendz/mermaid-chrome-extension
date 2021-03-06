# GitHub Mermaid Chart - Chrome Extension

## What is it?

This Chrome extension autodetects GitHub Flavored Markdown code blocks with the mermaid language (http://knsv.github.io/mermaid/), and automatically renders the resulting chart.

## Installation

- Clone repo
- Go to manage Chrome Extentions: chrome://extensions/
- Tick to enable Developer mode
- Load unpacked extension
* Select the repo folder

```mermaid
sequenceDiagram
  A->>B: Hello
	Note right of B: B stares at A awkwardly for a moment
	B-->>A: Oh, hello!
```

## Change the theme
Just edit `manifest.json`, change the `css` value to one of these:
- mermaid.css
- mermaid.dark.css
- mermaid.forest.css
