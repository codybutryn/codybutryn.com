# codybutryn.com

The portfolio site of Cody Butryn — growth marketer, web designer, and founder,
Milwaukee, Wisconsin.

Three hand-coded static pages. No framework, no build step, no dependencies.
Open any `.html` file in a browser and it runs.

| File | What it is |
| --- | --- |
| `index.html` | The estimate — positioning, scope of work, five completed work orders, contact |
| `gallery.html` | The flat file — concepts, brand boards, ad creative, video |
| `resume.html` | The résumé — prints straight to PDF via the browser |

## The design

The site is built as a contractor's carbonless estimate form: printed carbon-blue
rules and caps labels, typed Courier fill-ins, one red stamp ink carrying every
state. Proof arrives as line items and stamped totals rather than as a case-study
scroll — the argument being that the audience already signs this piece of paper.

The full system — tokens, type ramp, elevation rules, component grammar — is
recorded in [DESIGN.md](DESIGN.md), derived from the shipped code rather than from
intentions. Product truth lives in [PRODUCT.md](PRODUCT.md).

Both were produced with [Impeccable](https://github.com/pbakaus/impeccable).

## Running it locally

No install needed — open `index.html` directly. To serve it over HTTP instead
(needed if you want to test the print path or check headers):

```bash
npx http-server -p 8317 -c-1
```

## Deployment

Deployed on Cloudflare Pages, built from this repository's default branch.
There is no build command and no output directory — Pages serves the repo root
as-is. `_headers` sets security headers and asset caching.

## Editing

Each page carries its own `<style>` block; there is no shared stylesheet, so a
token change must be applied to all three files in the same edit. `DESIGN.md`
documents this as a known maintenance constraint.

To add a piece to the gallery, copy a `.gcard` block in `gallery.html` and set its
image `src`, title, tag, and `data-cat` (`web` | `branding` | `ads` | `video`).

## License

Code is available for reference. Content, imagery, and the Cody Butryn identity
are not licensed for reuse.
