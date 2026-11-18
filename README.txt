SHANTI GURU INDUSTRIES LIMITED - TEMPLATE 2 (light theme)

Open index.html in a browser. No CDN or internet is needed. The 3D hero is written in plain WebGL (no three.js); text uses system fonts (Georgia / system-ui) because the Google Fonts link was removed.

Files:
  index.html       page structure
  style.css        all styling (colours are CSS variables at the top)
  script.js        page content, scroll animations, hero dot-grid effect and the 3D hero (plain WebGL, no libraries)
  images-data.js   product images used as 3D textures
  images/          product photos and store.jpg (store interior photo)

Change colours: edit --sa (accent), --ch (secondary), --ink (background) at the top of style.css.
The top-bar button switches to a dark theme.

Update: the Committees block and the 'Changes in the Board and KMP' block were redesigned (card layout with committee tabs, and a dated register with Appointment / Resignation tags). Their styles are at the end of style.css; the data is in script.js (C = committees, TL = board changes).
Animations: the Board of Directors section has its own animation block at the end of style.css (marked 'Board of Directors section animations') and a small hover-tilt script in script.js. Delete that CSS block to remove them. They switch off automatically for visitors who use 'reduce motion'.
Investors Desk: redesigned as a hub - a scrip-code panel on the left and the six document links grouped on the right. Links and groups are in script.js (look for G=); styles are the 'Investors Desk' block at the end of style.css.
Products: each product is now its own card. As the visitor scrolls, the cards appear one after another and stack on top of each other (the previous card shrinks and dims as the next slides over it). Gap between products: margin-bottom on .pcd in the 'Products: stacked cards' block at the end of style.css.
Contact Us: redesigned as a split layout - a contact-details panel on the left (office, email, phone, investor contact) and the message form on the right with topic chips and floating labels. The form still opens the visitor's email app (mailto), as before. Markup is in index.html (#contact); styles are the 'Contact Us' block at the end of style.css.

Footer: a four-column footer (brand, Explore links, Investors, Contact) with a copyright bar and Back to top link sits after Contact Us. Markup is <footer class="ft"> at the end of index.html; styles are the .ft block in style.css (it keeps its dark-green look in both themes).
