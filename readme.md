# Thala 7.

A simple shoe e-commerce front-end built with **HTML and CSS only**. It recreates a four-page shopping flow for the "Thala 7." brand.

## Pages

| Page | File | Description |
|------|------|-------------|
| Home | [index.html](index.html) | Landing page with hero section and stats bar |
| Product | [product.html](product.html) | Product detail page (opens via **Shop Now**) |
| Cart | [cart.html](cart.html) | Shopping cart with order summary (opens via **Add to Cart**) |
| Checkout | [checkout.html](checkout.html) | Payment / checkout page (opens via **Pay Now**) |

## Flow

```
Home  →  Product  →  Cart  →  Checkout
      Shop Now   Add to Cart  Pay Now
```

## Project structure

```
.
├── index.html
├── product.html
├── cart.html
├── checkout.html
└── css/
    ├── style.css      # home page + shared navbar
    ├── product.css
    ├── cart.css
    └── checkout.css
```

## How to run

No build step or server needed. Just open `index.html` in a web browser.

## Notes

- Built with plain HTML and CSS (no JavaScript).
- Interactive elements (quantity steppers, coupon, payment) are styled but not functional — they would require JavaScript/a backend.
- Some images and brand logos use placeholder URLs and emoji as stand-ins.
