# WorkFlux — 2D Work and Flux Integrals

WorkFlux is a standalone, interactive visualization for exploring a planar vector field along a parameterized curve. It is designed to make the geometry behind **work and flux line integrals** easier to investigate.

## Features

- Explore a parameterized curve and the vector field along it.
- Visualize the tangent vector **T**, normal vector **N**, and vector field **F** at the moving point.
- Animate the point along the curve and inspect its position and parameter.
- Show or hide visual elements such as the curve, tangent, normal, field vectors, grid, and animated flow.
- Adjust animation and flow controls.
- Explore synchronized work and flux graphs as functions of arc length.
- Use the responsive layout on desktop, tablet, and mobile screens.
- View mathematical expressions rendered with MathJax.

## Run it

This project is a self-contained HTML page; there is no build step or package installation required.

1. Download the main WorkFlux HTML file.
2. Open the file in a modern browser.
3. For full functionality, allow the page to load its third-party libraries from their CDNs. An internet connection is required for MathJax and math.js as currently configured.

You can also host the HTML file on a static site. If you rename it, keep the `.html` extension.

## Controls

The interface includes animation, reset and view-centering controls, curve and vector visibility toggles, adjustable flow settings, and an expanded view for the work and flux graphs. The arc-length slider can be used to inspect the moving point directly.

## Inspiration and acknowledgments

WorkFlux was inspired in part by **[FieldPlay](https://github.com/anvaka/fieldplay)**, a vector-field explorer created by **Andrei Kashcha ([@anvaka](https://github.com/anvaka))**.

FieldPlay helped inspire the idea of making vector fields something to explore dynamically and visually. WorkFlux takes that inspiration in its own direction, focusing on a parameterized curve and the geometric interpretation of work and flux line integrals.

WorkFlux is an independent project and is not affiliated with or endorsed by the FieldPlay project or its creator. This acknowledgment describes conceptual inspiration and does not imply that FieldPlay source code was incorporated into WorkFlux.

This project also relies on third-party libraries listed in [`THIRD_PARTY_DEPENDENCIES.md`](THIRD_PARTY_DEPENDENCIES.md). Please retain their notices and license information when redistributing those libraries or a bundle that includes them.

## Project status

WorkFlux is an interactive educational visualization. It is intended to support exploration and intuition, rather than replace formal definitions, proofs, or careful mathematical analysis.

## Copyright and permissions

Copyright © 2026 Edwin Garcia Cuevas. All rights reserved.

Except for third-party components and materials identified as belonging to others, the original WorkFlux source code, documentation, and original visual design are reserved to the copyright holder.

No license is granted to copy, modify, redistribute, sublicense, or incorporate original WorkFlux materials into another project without prior written permission from the copyright holder, except where a separate written agreement or applicable law permits otherwise.

Third-party libraries remain subject to their respective licenses. See [`THIRD_PARTY_DEPENDENCIES.md`](THIRD_PARTY_DEPENDENCIES.md) for details.

For permission requests, contact the copyright holder through the contact method listed in the project's official repository or website.

This notice describes the project's intended permissions and is not legal advice.
