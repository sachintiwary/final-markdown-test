# Markdown to HTML Converter

## Summary
This is a simple static web page that converts a predefined Markdown file (`input.md`) into styled HTML. It utilizes the `marked` library to parse Markdown and `highlight.js` to syntax-highlight any code blocks. The rendered HTML is displayed inside a designated container on the page.

## Setup
Since this project is a static webpage, you can run it locally by simply opening the HTML file in your web browser:
1. Download or clone the project files to your local machine.
2. Open the `index.html` file directly in your preferred web browser.
3. You will see the converted Markdown content displayed with syntax highlighting applied to code blocks.

Note: This implementation uses a hardcoded Markdown string within the JavaScript. To work with your own `input.md` file, replace the `inputMD` variable content with your desired Markdown or modify the implementation to load an external file as needed.

## Code Explanation
- The webpage is structured with an `<h1>` title and a `<div>` with the ID `#markdown-output` where the converted content will appear.
- External stylesheets for `highlight.js` are loaded for code highlighting styles.
- The `marked` library is included via CDN to parse Markdown into HTML.
- The JavaScript takes a Markdown string (`inputMD`), converts it into HTML using `marked.parse()`, and injects it into the `#markdown-output` div.
- It then finds all `<pre><code>` blocks within the output and applies syntax highlighting using `highlight.js`.

## License
This project is licensed under the MIT License. See the LICENSE file for details.