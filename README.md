# Sort Company — product page

School project: a clothing store page built with **HTML and CSS only**, based on the
"Classic Burger" design (desktop 1440 px, mobile 390 px). Only the fonts were changed.
Products come from [Sort Company](https://sortcompany.shop/collections/all-products/).

## Pages

| File | Page |
|---|---|
| `home.html` | Home: new drop + new products |
| `index.html` | Products (the page from the design) |
| `lookbook.html` | Lookbook: photos of the new drop |
| `about.html` | About the brand and its drops |
| `login.html` / `signup.html` | Log in and Sign up forms |

## CSS-only features (no JavaScript)

- **Photo slider:** the dots are radio buttons; `:checked` + `:has()` shows the matching photo
- **Search and categories menus:** `<details>` / `<summary>` in the sidebar
- **Category links** jump to a product and highlight it with `:target`
- Hover and focus states on all buttons, links and cards
- The − / + quantity buttons are only visual (counting needs JavaScript)

## File structure

```
index.html, home.html, lookbook.html, about.html, login.html, signup.html
css/
  reset.css        – removes browser defaults (loaded after normalize.css)
  variables.css    – colors, fonts, sizes, radius, spacing
  base.css         – body typography, icons
  layout.css       – page frame: sidebar, header, main
  components.css   – buttons, nav, chips, badge, slider, quantity, cards, dropdowns
  pages.css        – lookbook gallery, log in / sign up forms
  responsive.css   – media queries (Mobile Friendly: from 1440 px down to 390 px)
```

Order of styles: normalize.css → reset → variables → base → layout → components → pages → responsive.

- Fonts: Space Grotesk (headings) and DM Sans (text) from Google Fonts
- Icons: Google Material Symbols
- Product photos: loaded from the Sort Company store
