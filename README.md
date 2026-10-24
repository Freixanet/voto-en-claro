# Voto en claro

An independent Spanish-language interface for comparing political proposals by topic. The reading experience brings each proposal, its source, its date and the questions it leaves open into the same view.

**[Explore the site](https://freixanet.github.io/voto-en-claro/)**

## Design and implementation

- Twelve topics with a consistent comparison structure.
- Progressive reading depth, a glossary and source links.
- URL and browser-history navigation between topics; reload preserves the reading position.
- Keyboard navigation, visible focus and reading preferences.
- One static `index.html`, with embedded styles and JavaScript. No build step or backend.

## Run locally

```sh
python3 -m http.server 8080
```

Open `http://localhost:8080`.

## Editorial method

The site distinguishes published rules, campaign announcements, historical programmes and general positions. These are different kinds of evidence, not interchangeable promises. Its methodology and correction route are available under “Sobre la web”. Content is maintained manually; a successful deployment does not verify a political claim or keep a source current.

Before updating a proposal, check the original source and date, revise the visible attribution, and exercise the affected topic in all reading modes.

Built by [Marcos Freixanet](https://github.com/Freixanet).
