# Book cover photos

Drop cover images for the Bookshelf page (`/blog/books/`) into this folder.

## How to add a cover

1. Save the image here, e.g. `img/books/intelligent-investor.jpg`
2. Open `_data/books.yml` and set the `image:` field for that book:

   ```yaml
   - title: The Intelligent Investor
     author: Benjamin Graham
     image: /img/books/intelligent-investor.jpg
   ```

Any book without an `image:` value automatically renders a designed cover card
instead, so the page never shows a broken image.

## Image guidance

- **Aspect ratio:** 2:3 portrait (e.g. 400x600px). Other ratios are cropped to fill.
- **Format:** JPG for photos, PNG if the cover has flat colour or text edges.
- **Size:** keep files under ~150KB so the page stays fast.

## A note on sourcing

If you photograph your own copies, the photos are yours to publish. If you use
publisher cover art, that artwork is copyrighted — reproducing it alongside genuine
commentary about the book is normal practice for book reviews, but the safest route
is your own photographs.
