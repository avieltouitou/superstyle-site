# SuperStyle Site

This repository contains several zip archives with the static files for the **SuperStyle** website. Each archive includes HTML pages, CSS and assets required to browse the site offline.

## Getting started

1. Choose one of the site archives, for example `SuperStyle_Art_Site_With_Login.zip`, `SuperStyle_Complete_Site.zip` or `SuperStyle_Full_Site.zip`.
2. Unzip the archive:

   ```bash
   unzip SuperStyle_Art_Site_With_Login.zip
   ```

3. Open `index.html` directly in your browser or serve the folder with a simple HTTP server:

   ```bash
   python3 -m http.server
   ```

   Then browse to [http://localhost:8000/index.html](http://localhost:8000/index.html).

The pages use local storage to keep product and order information, so everything works without a backend.

## Page overview

- **index.html** – main catalog page that lets you add products and search existing ones.
- **orders.html** – customer order form that collects shipping information and displays selected items.
- **admin-orders.html** – admin view listing submitted orders with a button to mark them as completed.

Enjoy exploring SuperStyle!
