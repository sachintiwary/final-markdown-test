# Markdown Tabs Viewer

## Summary
This static web application allows users to view and switch between the rendered HTML output and the original Markdown source content. It features toggle tabs that keep the content in sync, providing an interactive way to see how Markdown translates into HTML.

## Setup
Since this is a static HTML file, you only need to open the file in any modern web browser to run the application. No additional installation or server setup is required.

## Code Explanation
The application consists of an HTML page with two main tabs: "Rendered HTML" and "Markdown Source". When the user types or edits Markdown in the source textarea, the application dynamically converts it into HTML using the `marked` library and displays the result. Tabs are implemented with clickable divs that toggle visibility between the Markdown source and the rendered HTML. Syntax highlighting for code blocks is handled with `highlight.js`. The content remains synchronized when switching tabs or editing the Markdown.

## License
This project is licensed under the MIT License. See the [LICENSE](LICENSE) file for more details.