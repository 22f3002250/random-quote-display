# Random Quote (Single-Page Web App)

## Overview
This is a lightweight single-page web app that fetches a random quote from a local quotes.json file and displays it inside the #quote element. It includes a “New Quote” button to cycle through quotes without reloading the page.

## Setup
1. Ensure the following files are in the same directory:
   - index.html
   - quotes.json (array of strings; e.g. ["This is a random quote.", "Share your knowledge.", "Create little just for fun."])

2. Serve the directory with a local static web server (required for fetch to work):
   - Python 3: python -m http.server 8000
   - Node.js (serve): npx serve .
   - PHP: php -S localhost:8000

3. Open your browser at:
   - http://localhost:8000 (or the port your server reports)

## Usage
- On load, the app fetches quotes.json and displays a random quote inside the #quote element.
- Click “New Quote” to display another random quote from the same dataset.
- If quotes.json cannot be loaded, the app will display a clear hint and use a small built-in fallback list so the page still shows a quote.

## License
MIT License

Copyright (c) 2025

Permission is hereby granted, free of charge, to any person obtaining a copy
of this software and associated documentation files (the “Software”), to deal
in the Software without restriction, including without limitation the rights
to use, copy, modify, merge, publish, distribute, sublicense, and/or sell
copies of the Software, and to permit persons to whom the Software is
furnished to do so, subject to the following conditions:

The above copyright notice and this permission notice shall be included in
all copies or substantial portions of the Software.

THE SOFTWARE IS PROVIDED “AS IS”, WITHOUT WARRANTY OF ANY KIND, EXPRESS OR
IMPLIED, INCLUDING BUT NOT LIMITED TO THE WARRANTIES OF MERCHANTABILITY,
FITNESS FOR A PARTICULAR PURPOSE AND NONINFRINGEMENT. IN NO EVENT SHALL THE
AUTHORS OR COPYRIGHT HOLDERS BE LIABLE FOR ANY CLAIM, DAMAGES OR OTHER
LIABILITY, WHETHER IN AN ACTION OF CONTRACT, TORT OR OTHERWISE, ARISING FROM,
OUT OF OR IN CONNECTION WITH THE SOFTWARE OR THE USE OR OTHER DEALINGS IN
THE SOFTWARE.