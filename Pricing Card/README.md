# Pricing Cards

A clean, responsive pricing cards UI built with HTML and CSS.

## Preview

Three pricing tiers displayed as cards:

| Plan | Price | Highlighted Features |
|------|-------|----------------------|
| Free | $0/mo | 1 project, 5 GB storage |
| Pro | $12/mo | 10 projects, 50 GB storage, Priority support |
| Team | $39/mo | Unlimited projects, 500 GB storage, 24/7 support |

The **Pro** card is featured with a dark background and a "Most popular" badge.

## Files

- `index.html` — page structure and styles

## How to Use

1. Clone or download the project
2. Open `index.html` in your browser

## Customization

To edit a pricing tier, find its `.card` block in `index.html`:

- Change the `<p class="plan">` text for the plan name
- Update the `<div class="price">` value for the price
- Add or remove `<li>` items inside `<ul>` for features
- Add `class="included"` to a `<li>` to highlight it
- Add `class="featured"` to a `.card` to make it the dark highlighted card

## Technologies

- HTML5
- CSS3
- Google Fonts (Syne)
