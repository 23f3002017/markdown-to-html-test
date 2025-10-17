# markdown-to-html-test

## Overview
Publish a static page that converts input.md from attachments to HTML with marked, renders it inside #markdown-output, and loads highlight.js for code blocks.

## Requirements Checklist
- [ ] !!document.querySelector("script[src*='marked']")
- [ ] !!document.querySelector("script[src*='highlight.js']")
- [ ] document.querySelector("#markdown-output").innerHTML.includes("<h")

## Setup
1. Clone this repository:
   ```bash
   git clone https://github.com/23f3002017/markdown-to-html-test.git
   cd markdown-to-html-test
   ```

2. Open `index.html` in your web browser

## Usage
Live demo: https://23f3002017.github.io/markdown-to-html-test/

Open the page and interact with the application. All functionality is contained in the single HTML file.

## File Structure
- `index.html` - Complete application with inline CSS and JavaScript
- `LICENSE` - MIT License
- `README.md` - This file

## Code Explanation
This is a single-file HTML application auto-generated using OpenRouter LLMs via AIpipe.

**Key Features:**
- Fully self-contained (no build step needed)
- Responsive design
- Accessible markup (ARIA labels)
- Error handling
- Browser-compatible (no external dependencies beyond CDN resources)

## Technology Stack
- HTML5
- CSS3
- Vanilla JavaScript (ES6+)
- CDN resources (Bootstrap, etc. as needed)

## Browser Compatibility
Works in all modern browsers (Chrome, Firefox, Safari, Edge)

## License
MIT License - See LICENSE file for full details

---
*Generated automatically*