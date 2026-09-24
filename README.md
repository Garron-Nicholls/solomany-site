# solomany.com

The website for **Solomany Fitness**, a product of Solomany Limited — a
personal training application for iPhone and Apple Watch.

A single static page. No build step, no dependencies. Open `index.html` and
that is the site.

## Deploying

GitHub Pages, from the default branch, root directory. `CNAME` carries the
custom domain and Pages reads it automatically — do not delete it.

DNS is managed at Cloudflare.

## Design

The page uses the application's own design language rather than an
approximation of it: the palette's hex values verbatim, and the two typefaces
the app uses — a serif for anything the coach says, reached through `ui-serif`
so it resolves to New York on Apple devices, and a condensed grotesque,
uppercase and tracked, for anything the app says about itself. Newsreader and
Archivo Narrow are the fallbacks elsewhere.

No cards anywhere. The rule is the grouping device, which is the language's own
premise: a hairline does what a box used to.

## Before launch

- [ ] Registered office in the footer — see the comment above `<footer>` in
      `index.html`. A UK company must publish this, so the site is not
      compliant until it is there.
- [ ] A real privacy notice. The page currently promises one rather than
      pretending to be one.
