# Gustavo Gasperin — Engineering Portfolio

Personal portfolio presenting Gustavo Gasperin's education, professional experience, and applied work in IT infrastructure, networking, embedded systems, industrial automation, computer-aided manufacturing, and business analytics.

**Live portfolio:** [gustavo-gasperin.github.io](https://gustavo-gasperin.github.io)

**Reuse of original code, images, and project materials requires Gustavo Gasperin's prior, express written authorization, subject to the exceptions in [Ownership and permissions](#ownership-and-permissions).**

## Project areas

The portfolio presents nine projects across five sections:

| Area | Projects |
| --- | --- |
| Networking and Embedded Systems | Enterprise Network Build; Smart Toolbox; Body Control Module |
| Intel Semiconductor Experience | Cleanroom semiconductor production and wafer patterning |
| PLC Projects | Drag Race Controller; Bag Sealing Station Control; Rail Welding Station Control |
| Computer Aided Manufacturing | CNC – Cutter Compensation, simulated in CNC Simulator Pro |
| Business Analytics | Employee Analytics: salary estimation and performance classification |

## Features

- English, Brazilian Portuguese, and Italian translations, switched at runtime.
- Responsive layouts, light and dark themes, keyboard navigation, reduced-motion support, and print styles.
- Interactive network topology and device-configuration viewer based on a Cisco Packet Tracer project.
- Body Control Module schematic with an Arduino emulator running in the browser.
- Illustrative drag-race playback, embedded PLC source, and zoomable ladder-logic diagrams.
- CNC assignment geometry, simulation images, speed/feed calculations, and syntax-highlighted G-code.
- Selected results and original plots from the Employee Analytics project.
- Contact form with client-side validation, a honeypot, minimum submission time, and per-visit submission limits.

## Technology and dependencies

The site uses vanilla HTML, CSS, and JavaScript in a single `index.html`. It has no application framework or build step and is published through [GitHub Pages](https://docs.github.com/en/pages).

| Component | Purpose and implementation |
| --- | --- |
| [GSAP](https://gsap.com/) and [ScrollTrigger](https://gsap.com/docs/v3/Plugins/ScrollTrigger/) | Scroll animation; version 3.12.5 is loaded from cdnjs. |
| [Lenis](https://github.com/darkroomengineering/lenis/tree/v1.1.13) | Smooth scrolling; version 1.1.13 and its MIT license notice are embedded in the HTML. |
| [Web3Forms](https://web3forms.com/) | Contact-form delivery. |
| Google Fonts: [Montserrat](https://fonts.google.com/specimen/Montserrat), [Inter](https://fonts.google.com/specimen/Inter), and [IBM Plex Mono](https://fonts.google.com/specimen/IBM+Plex+Mono) | Display, body, and monospace typography. |
| [hCaptcha](https://www.hcaptcha.com/) | Optional contact-form integration; currently inactive. |

Third-party components retain their own licenses and terms. See the [GSAP license](https://gsap.com/standard-license/) and the [Lenis 1.1.13 MIT license](https://github.com/darkroomengineering/lenis/blob/v1.1.13/LICENSE). Font licenses are available through their respective Google Fonts pages. This repository's permissions notice does not replace those licenses.

## Repository structure

```text
index.html                       Site markup, styles, scripts, and translations
images/                          Photographs, certificates, drawings, and project images
assets/vendor/                   Archived third-party distribution and license notices
README.md                        Portfolio overview, references, and permissions
LICENSE                          Rights and permissions notice for original materials
PORTFOLIO_SITE_DOCUMENTATION.md  Detailed maintenance reference
```

The displayed ladder diagrams, PLC source listings, and CNC program are embedded in `index.html`. Separate ladder `.svg` files are not required for the live page. The `source/`, `tmp/`, and `output/` directories contain reference archives or verification artifacts and are not required for the live website. The Resume button expects `resume.pdf` at the repository root.

## Acknowledgments and references

- **Website development:** Gustavo Gasperin, with assistance from Claude AI and ChatGPT.
- **PLC reference illustrations:** Erickson, Kelvin T. (2023). *Allen-Bradley PLCs: An Emphasis on Design and Application* (2nd ed.). Dogwood Valley Press LLC. ISBN 978-0-9766259-5-7. The portfolio identifies this source with the bag-sealing and rail-welding illustrations.
- **CNC assignment drawing:** Kent State University; drawing credited to Darwin L. Boyd, 2014.
- **Employee Analytics:** jointly developed by Gustavo Gasperin and Kyle Bartlett.
- **Semiconductor project:** completed with Angelina Urbina and Kaydence Porter through Kent State University's course offered in partnership with Intel.

Project-specific credits and context also appear on the website. References to institutions, products, and trademarks identify the work and tools involved and do not imply endorsement.

## Ownership and permissions

**Copyright © 2026 Gustavo Gasperin. All rights reserved in original materials owned by Gustavo Gasperin.**

The original website source code, embedded project programs, text, photographs, artwork, diagrams, screenshots, reports, and project documentation owned by Gustavo Gasperin are not offered under an open-source or general reuse license.

**Without Gustavo Gasperin's prior, express written authorization, no permission is granted to copy, modify, adapt, redistribute, republish, incorporate, or otherwise reuse those materials, in whole or in part.** This includes reuse in other websites, repositories, academic submissions, portfolios, presentations, products, and commercial or noncommercial projects. Attribution alone does not grant permission. Public availability does not constitute a general reuse license.

These restrictions apply only to rights held by Gustavo Gasperin. Third-party software, fonts, academic reference materials, trademarks, and collaborative contributions remain subject to their respective owners' rights and applicable licenses. Nothing in this notice overrides applicable law, valid prior permissions or licenses, or rights granted under [GitHub's Terms of Service](https://docs.github.com/en/site-policy/github-terms/github-terms-of-service#d-user-generated-content), including its provisions for public repositories.

The complete rights and permissions notice is in [LICENSE](LICENSE).

### Permission requests

Contact [contact.gasperin@gmail.com](mailto:contact.gasperin@gmail.com) before reusing original material. Identify the material requested, the intended use, where it will appear, and whether it will be modified. Any authorization must be explicit and in writing; permission is limited to the uses stated in that authorization. A request, acknowledgment, or absence of a response does not constitute permission.
