# FoodTable — Website

Complete single-page website for **FoodTable (Roasted FoodTable)**, Chowk Azam.
Premium fast-food ordering design in the style of modern burger/pizza brand sites:
black header with a big centre logo, hero carousel, sticky category pills, search,
popular items, full menu with prices, cart drawer and WhatsApp ordering.

## Files
- `index.html` — the page
- `styles.css` — all styling
- `script.js` — menu data, cart, search, hero carousel and the Sajji animation
- `images/` — food photos used by the site (sajji, pizza, burger, shawarma)

## Run it
Open `index.html` in any browser, or upload all files (keeping the folder
structure) to any web host / Netlify / cPanel.

## Add your own Sajji video
The Sajji popup ("Watch It Build" button on the Sajji cards) plays a built-in
animation: plate -> chicken drops in -> masala rains -> rice rains -> steam.
To use your own video instead, save it as:

    images/sajji-video.mp4

The site detects the file automatically and plays the video in the popup.
Delete the file to go back to the animation.

## Orders
The cart saves in the visitor's browser. "Order on WhatsApp" sends the full
order to 0309-1555141 (wa.me/923091555141). To change the number, search
script.js for `923091555141`.

## Business details on the site
- Opposite Askari Bank, Layyah Road, Chowk Azam
- Phones: 0309-1555141, 0370-0580141
- Email: foodtable141@gmail.com
- Hours: 1:00 PM - 1:00 AM daily - Free Home Delivery
- Menu and prices are exactly as on the FoodTable flyers (Nov 2026).
