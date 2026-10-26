# Tops American Grill, Bakery & Bar

Website for Tops, Rotterdam's hometown diner at the Five Corners (351 Duanesburg Rd, Schenectady, NY 12306) since 1953.

It's a single static page with no build step. Open `index.html` in a browser, or host the folder on any static host (GitHub Pages, Netlify, and so on).

## Files

- `index.html`: the whole site (styles and scripts inline)
- `menu.json`: the "Full menu & prices" list
- `images/`: logo, wordmark, building and food photos

## Updating the menu and prices

Edit `menu.json` (on GitHub: open the file, then click the pencil icon). Each item looks like this:

```json
{
  "updated": "2026-10-26",
  "items": [
    { "section": "breakfast", "name": "Eggs Benedict", "desc": "With home fries", "price": 0.00, "soldOut": false }
  ]
}
```

- `section` is one of `breakfast`, `lunch`, `dinner`, `bakery`, `sides`
- `price` is a number; leave it out to show "Ask your server"
- `soldOut: true` crosses the item out and adds a "Sold out today" tag
- Items show in the order they appear in the file
- `updated` is the date shown as "Prices updated …"

While `items` is empty, the menu section links to the printed PDF menu.

## Before launch

- Confirm hours, the Friday fish fry, and menu details with the restaurant.
- Photos come from the restaurant's own website and Instagram. Get the owner's OK to use them.
- The night building photo was widened on the left and enlarged. Tell the owner about this edit.
