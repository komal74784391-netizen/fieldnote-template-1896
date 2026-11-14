# Fieldnote - research profile template

A small static-site template for personal research profiles: a Markdown front
page, a publications page, shared layouts and one stylesheet.

## Using it

1. Copy this repository into a new repository of your own.
2. Edit `_config.yml` - set the site title and replace every value in the
   `author` block.
3. Rewrite the placeholder content in `index.md` (and `publications.md` if you
   keep that page).
4. Add a root-level `manifest.json` so the site can be indexed by the site
   gallery.

The gallery crawler is strict: it accepts only the manifest format used by the
entries already registered in `fieldnote-gallery-1896`. Anything else is
rejected and the site is left out of the gallery listing.

The template is maintained by the Fieldnote working group. All placeholder
values are intentionally obvious.
