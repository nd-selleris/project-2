# Sort Company — product page

School project: a clothing store page built with **HTML and CSS only**, based on the
"Classic Burger" design (desktop 1440 px, mobile 390 px). Only the fonts were changed.
Products come from [Sort Company](https://sortcompany.shop/collections/all-products/).

## File structure

```
index.html
css/
  reset.css        – removes browser defaults (loaded after normalize.css)
  variables.css    – colors, fonts, sizes, radius, spacing
  base.css         – body typography, icons
  layout.css       – page frame: sidebar, header, main
  components.css   – buttons, nav, chips, badge, quantity, cards
  responsive.css   – media queries (Mobile Friendly: from 1440 px down to 390 px)
```

Order of styles: normalize.css → reset → variables → base → layout → components → responsive.

- Fonts: Space Grotesk (headings) and DM Sans (text) from Google Fonts
- Icons: Google Material Symbols
- Product photos: loaded from the Sort Company store
