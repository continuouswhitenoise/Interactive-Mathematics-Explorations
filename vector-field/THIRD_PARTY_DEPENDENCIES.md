# Third-Party Dependencies

This document records the third-party libraries loaded by the current WorkFlux HTML file. Both are loaded from public CDNs at runtime; they are not bundled locally in the HTML file.

## 1. MathJax

- **Purpose:** Renders TeX-style mathematical notation in the page.
- **Reference in HTML:** `https://cdn.jsdelivr.net/npm/mathjax@3/es5/tex-chtml.js`
- **Version selection:** Major version 3 (`@3`); the URL does not pin a specific patch release.
- **Project:** https://www.mathjax.org/
- **Source repository:** https://github.com/mathjax/MathJax
- **License:** Apache License 2.0.
- **License text:** https://www.apache.org/licenses/LICENSE-2.0

## 2. math.js

- **Purpose:** Parses and evaluates mathematical expressions entered into the interactive controls.
- **Reference in HTML:** `https://cdnjs.cloudflare.com/ajax/libs/mathjs/13.2.0/math.min.js`
- **Version:** 13.2.0
- **Project:** https://mathjs.org/
- **Source repository:** https://github.com/josdejong/mathjs
- **License:** Apache License 2.0 for math.js; the project distribution also includes third-party components with their own notices. Consult the package's license and notices for the exact distribution being used.
- **License text:** https://www.apache.org/licenses/LICENSE-2.0

## Runtime and network notes

- The page uses plain HTML, CSS, and JavaScript; no framework or build tool is required.
- A network connection is needed to retrieve MathJax and math.js from their CDNs.
- If you later vendor or redistribute copies of these libraries, retain the license and copyright notices required by their licenses and check the notices included with the exact versions you distribute.
- The dependency list is based on the script references in the current HTML file. If you add more external resources later, update this file.
