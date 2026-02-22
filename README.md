# TUI-HTML-Editor
TUI HTML Editor
A text microprocessor for HTML that works everywhere

TUI HTML Editor is a lightweight, completely standalone WYSIWYG editor built to work under any conditions. Its code is a single HTML file with no external dependencies that can be opened in any browser or embedded into any application supporting HTML page rendering.

The project's core philosophy: "Write once, run forever". The editor requires no updates, never breaks with browser version changes, and remains fully functional in the most exotic environments — from Windows 3.1 with Internet Explorer 4.0 to future quantum computers with DOM emulation.

✨ Key Features
📝 Text Formatting
Full formatting command set: bold, italic, underline, strikethrough
Alignment (left, right, center, justify)
Font family and size selection (1–7)
Text and background colors (216 web-safe palette)
Indent control, format clearing

📊 Advanced Table Management
Table creation with customizable parameters
Add/remove rows and columns with intelligent integrity protection (rowSpan/colSpan validation)
Merge and split cells (horizontal and vertical)
Table attribute editor
Automatic prevention of row/column deletion that would break merged cell structure

🔗 Document Structuring
Create anchors for H1-H6 headings, tables, images, formulas, listings
Insert links to created anchors (internal document navigation)
Meta tags and page title management

📋 Lists
Ordered and unordered lists
Marker type selection (disc, circle, square)
Numbering type selection (1, A, a, I, i)
Multi-level list creation (hierarchy management)

🧹 HTML Cleaning (3 levels)
Attributes — remove classes, styles, language tags
Office tags — clean MS Word/Outlook garbage, VML graphics
Deep cleaning — remove empty tags, office comments

🔧 Technical Highlights
Marker tag insertion system — always see cursor position, prevents HTML breakage
Undo/Redo — 20-step history, command undo/redo, auto-save
Attribute editing:
For legacy browsers (IE4+) — 13 key attributes
For modern browsers (DOM1+) — full access to all attributes
Support for legacy but useful tags: <listing>, <xmp>, <marquee>, <center>, <plaintext>, <code>, <samp> and others

🌐 Browser Support (and anything based on them)
Internet Explorer — 4.0 and newer (including 16-bit versions)
Gecko — Netscape 7.1, Mozilla 0.8 and newer (Firefox, SeaMonkey)
Presto — Opera 9.0 – 12.18
KHTML — Konqueror 4.1 and newer
WebKit/Blink — Safari 1.3 and newer, Chrome (all versions), Edge (all versions)
WebView2 and .NET/CLR embedded browsers — full support
HTML document fields in applications using embedded browser engines

🎯 Who Is This For
Developers needing a reliable editor for legacy systems and embedded solutions

Creators of offline documentation, e-books, help systems

Retro-computing enthusiasts restoring old projects

Anyone who values minimalism, independence, and code longevity

📦 Distribution Package
editor.html — monolithic editor file (all-in-one: HTML, CSS, JavaScript)

demo/ — embedding and usage examples (optional)

README.md — this file

🚀 Quick Start
Download editor.html

Open it in any browser

Start editing!

For embedding in your application:

Use an <iframe> tag pointing to editor.html

Or load the file content as a string and insert into your app's HTML container

Interact with the editor via JavaScript (DOM access, function calls)

⚖️ License
Free to use. Open source. You may modify, distribute, and use the editor for any purpose — both personal and commercial.

Crafted with care for those who value reliability and independence from trends.
