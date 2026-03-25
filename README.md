# Bottega Atelier Website

Bottega Atelier is a luxury fashion storefront website built as a responsive single-page shopping experience.

## What the Website Includes

- Premium product gallery with multiple product images
- Category filtering (`All Products`, `Clothing`, `Shoes`)
- Search and sorting (popular, newest, price asc/desc)
- Cart drawer with quantity controls and item removal
- Wishlist support with local persistence
- Product quick-view modal with fit/material/size guidance
- WhatsApp contact links (customer support and business actions)
- Quotation PDF generation at checkout (with invoice reference)
- Light and dark mode support
- Privacy Policy and Terms & Conditions pages

## Tech Stack

- `HTML5`
- `CSS3`
- `Vanilla JavaScript`
- `localStorage` for cart, wishlist, theme, and lightweight analytics
- `jsPDF` for quotation PDF generation

## Product Catalog (Current)

The storefront currently includes these products:

1. Fear Of God Grey Suede High Skate
2. P.H.S Long Leather Down Jacket Men 200g
3. Casablanca Monogram Knit Jumber Tee
4. Jil Sander T-Shirt
5. Faruk Balkanas: Hudson Model Hakoko Suut Deri Eva Taban
6. Moncler BLACK Down Jacket
7. Fear Of God: Essentials
8. Casablanca Monogram Knit Jumber
9. Moncler: Etiache Rain Jacket
10. Made Vintage Asymmetrical Denim Jacket Lapel 14oz
11. Amiri Varsity Tiger Denim Jeans

## Files

- `index.html` - Main storefront page (layout, styling, interactions)
- `products.json` - Product metadata and image mappings
- `privacy-policy.html` - Privacy policy page
- `terms-and-conditions.html` - Terms page
- `assets/` - Product images, branding assets, and media

## Checkout and Quotation Flow

When a customer proceeds to checkout:

1. Cart details are validated
2. Quotation PDF is generated and downloaded
3. A payment reference number is included (invoice/quotation number)
4. WhatsApp flow is triggered for order follow-up
