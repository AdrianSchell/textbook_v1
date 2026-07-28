# Online Textbook Starter

This folder contains the first two setup steps:

- `sample-chapter.html` demonstrates the visual language for a chapter.
- `book.css` is the master stylesheet every chapter should link to.
- `figures/platform-stack.svg` is a sample figure asset used by the chapter.

The visual direction follows the supplied Gallaugher formatting examples: Georgia-style body text, blue chapter headings with thin rules, flat colored section headers, pale section bodies, bold figure titles, small source/caption text, accessible long descriptions, and clean table/list formatting.

Every future chapter should include this line in the `<head>`:

```html
<link rel="stylesheet" href="book.css">
```

To create a new chapter, copy `sample-chapter.html`, rename it, replace the sample content, and keep the same element classes for recurring items such as learning objectives, figures, manager tips, AI insights, case studies, exercises, summaries, and references.
