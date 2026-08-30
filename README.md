# Gustavo Gasperin — Portfolio

Personal engineering portfolio. Education, work experience, and project work in IT systems, networking, and embedded development.

**Live:** https://gustavo-gasperin.github.io

## Stack

Vanilla HTML, CSS, and JavaScript in a single file. No framework, no build step.

- [GSAP](https://gsap.com) + ScrollTrigger — scroll animation
- [Lenis](https://lenis.darkroom.engineering) — smooth scrolling
- [Web3Forms](https://web3forms.com) — contact form delivery
- Google Fonts — Fraunces, Instrument Sans, IBM Plex Mono

## Structure

```
index.html     entire site — markup, styles, scripts, translations
images/        photos, diplomas, project documentation
DEPLOY.md      deployment and configuration notes
```

## Features

- Full English / Portuguese translation, switched at runtime
- Interactive SVG network topology, traced from a Cisco Packet Tracer build
- Body Control Module schematic with an Arduino emulator running in the browser
- Contact form with client-side validation, honeypot, time trap, and rate limiting

## Running locally

Serve the directory over HTTP — opening `index.html` from the file system will
trip the Content Security Policy.

```bash
python3 -m http.server 8000
```

Then open http://localhost:8000

## License

Code is free to reference. Content, images, and documents are not licensed for reuse.
