# Free landing page templates

Two free, single-file landing page templates. Every word is placeholder copy (Lorem Ipsum) — swap in your own.

Made by [Nishant Vyas](https://www.linkedin.com/in/nishantvyas/).

Live demos: [Night Shift](https://nishantvyas.github.io/free_templates/night-shift/) · [Signal](https://nishantvyas.github.io/free_templates/signal/)

| Template | What it is |
|---|---|
| [**Night Shift**](night-shift/) | A dark hero with a live "console" panel that plays a timed, step-by-step session (with a replay button) over an animated line field, then tabbed product previews, a comparison table, three pricing plans, a partner block and a quote section. |
| [**Signal**](signal/) | A scroll-driven page over a WebGL particle field that reshapes itself chapter by chapter, with pinned sections, a comparison table, pricing, a quote tunnel, and a close where the logo assembles from dots. |

## Use

Each template is one `index.html` with its CSS and JavaScript inline. Open it in a browser, or serve the folder:

```sh
npx serve .
```

No build step, no dependencies to install.

## Built with

- Type: [Archivo](https://fonts.google.com/specimen/Archivo), [Hanken Grotesk](https://fonts.google.com/specimen/Hanken+Grotesk) and [JetBrains Mono](https://fonts.google.com/specimen/JetBrains+Mono), from Google Fonts.
- Night Shift: plain JavaScript and canvas.
- Signal: [GSAP](https://gsap.com) 3.12 with ScrollTrigger, [Lenis](https://github.com/darkroomengineering/lenis) smooth scroll (both from public CDNs), and plain WebGL.
- Both respect `prefers-reduced-motion` and work on phones.

## License

MIT — see [LICENSE](LICENSE). The fonts and the libraries loaded from CDNs are under their own licenses.
