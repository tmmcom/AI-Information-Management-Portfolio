# Wikipedia Children’s Book EPUB Generator

Generate easy-to-read 4th-grade children’s books using Wikipedia as a source, output as EPUB 3.

This is an open-source educational project to create children’s books about historical topics, fully compliant with Wikipedia’s Creative Commons licensing.

---

## Project Overview

This project uses a prompt-based approach to generate:

- 32-page children’s books
- Simple language suitable for 4th-grade readers
- Illustration placeholders for teacher or student customization
- Proper copyright and attribution for Wikipedia content

The default example topic is “The Invention of the Automobile.”

---

## Features

- Fully open-source content using Wikipedia articles
- Automatic EPUB 3 generation
- Cover page, legal page, title page, marketing description
- Every third page includes a blank half for illustrations
- Source list included at the end of the book
- 4th-grade vocabulary, chronological storytelling, and neutral tone

---

## How It Works

1. The prompt defines book structure,

Teacher note: You can edit `prompt.md` to change topics, reading level, page count, or fonts.

---

## Adding Illustrations

Replace the illustration placeholders with public-domain images from Wikimedia Commons. Include captions with attribution, for example:

```html
<img src="URL" alt="Description" />
<p style="font-style:italic;">Description (Public Domain, Wikimedia Commons)</p>

