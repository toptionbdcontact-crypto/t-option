# t Option — GitHub Pages Website

## What this version does
- Works on GitHub Pages (no PHP/server/database required).
- Responsive on mobile and desktop.
- Products, prices, descriptions and product photos can be changed from `products.js`.
- Product photos go inside the `images` folder.

## How to add your own product
1. Put the photo inside `images/`, for example `images/black-tshirt.jpg`.
2. Open `products.js`.
3. Add a product object like:

{
  name: "Black Premium T-Shirt",
  category: "tshirt",
  price: "৳ 799",
  image: "images/black-tshirt.jpg",
  description: "Premium cotton T-Shirt."
},

4. Save and upload the changed files to GitHub.

## How to change WhatsApp number
Open `index.html` and find:
`<!-- Replace the # below with your WhatsApp link ... -->`

Replace the `href="#"` with:
`href="https://wa.me/8801XXXXXXXXX"`

Use your full number with country code and without `+`, spaces or dashes.

## GitHub Pages
Create a GitHub repository, upload all files/folders while keeping the same structure, then:
Settings → Pages → Deploy from a branch → main → /(root) → Save.

After deployment GitHub will show your free website address.
