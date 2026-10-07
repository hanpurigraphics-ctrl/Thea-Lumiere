THEA LUMIERE — DRESS RENTAL LIBRARY
=====================================

Files:
- index.html
- style.css
- script.js
- assets/thea-lumiere-logo.png

HOW TO USE
----------
1. Keep the same folder structure.
2. Open index.html in a browser.
3. The website is responsive for desktop and mobile.
4. Click any dress card to open the photo/details modal.
5. Use the category buttons to filter the dress library.

ADDING YOUR REAL DRESSES
------------------------
Open script.js and edit the "dresses" array.

Each dress supports:
- name
- category
- style
- color
- sizes
- price
- tag
- description
- images: up to 3 photos

Example:
{
  id: 9,
  name: "Your Dress Name",
  category: "Gowns",
  style: "A-line gown",
  color: "Pink",
  sizes: "S · M · L",
  price: "₱1,800 / rental",
  tag: "New",
  description: "Your dress description.",
  images: [
    "assets/dresses/dress-09-1.jpg",
    "assets/dresses/dress-09-2.jpg",
    "assets/dresses/dress-09-3.jpg"
  ]
}

EMAIL
-----
The inquiry button currently uses:
hello@thealumiere.com

Change this in script.js to the actual email/social/contact method.

NOTES
-----
The sample dress images are remote image URLs. Replace them with the actual
Thea Lumiere dress photos when you have them. Local images are recommended
for the final deployed version.
