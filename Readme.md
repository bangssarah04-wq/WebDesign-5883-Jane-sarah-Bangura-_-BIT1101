# LŎR Restaurant Website

**Restaurant Website Design: A Modern Digital Dining Experience**


| **Name** | Jane Sarah Bangura |
| **Student ID** | 905005883 |
| **Project** | Web design assignment: restaurant website concept, Figma prototype and HTML/CSS/JavaScript build |
| **Case study** | LŎR Restaurant, Freetown, Sierra Leone |

---

## Introduction

A restaurant website should do more than show attractive images. It should help visitors find information quickly and complete common tasks such as viewing the menu, contacting the restaurant, placing an order and making a reservation.

This project uses LŎR Restaurant in Freetown, Sierra Leone, as a real-world case and design reference. It is **not** an official redesign of LŎR's online presence. It is an independent website concept with its own information architecture, navigation structure, interface layout and user experience.

The project covers the early stages of the web design process: understanding users and their needs, organizing content, planning navigation and a sitemap, creating wireframes, and presenting the interface as a Figma interactive prototype. This folder contains the website built from that design in HTML, CSS and JavaScript.

---



## About this project

This website is based on a real restaurant in my country, LŎR Restaurant in Freetown, Sierra Leone. I used their name and logo style as my starting point, but this is **not** their official website. It is my own idea of what a modern restaurant website could look like.

I did visit the real LŎR website first. It was good, but I felt it had a lot of writing and not enough pictures. A restaurant website should make people hungry, so the images should pop out more than the words. It may be because they have a lot of items on their menu, so I kept mine short and simple: four menu groups with just a few dishes each.

To find a design I liked, I looked at about 10 to 15 different restaurant websites and took ideas from them. The biggest one is on the menu page: the **big circle** that shows which section you are in, with a signature dish inside it. I didn't copy anybody's design. I put the ideas together in my own style, which is **elegant, simple and refined**.

When I finished the first version, the site looked a bit plain to me. So I added the **golden leaves**: the leaves in the corners of the header and footer, and the leaves that float down the page on the menu. That made it feel more alive. The gold and black also match the restaurant's feel, which is elegant, refined and a little luxurious.

---

## The proposal

The aim is a modern restaurant website that shows information clearly and gives people an easy way to look around the restaurant, see the menu and prices, contact the restaurant, order and book a table.

Customers want to know a few things before they visit: what food is there, how much it costs, where the restaurant is, what services it has, what other people think, and if they can reserve a table. A good website puts all of that in one place. I started from what users need to do on the site, and then built the pages around that.

## The solution

The website has eight pages, and the menu bar at the top is the same on every page so nobody gets lost:

- **Home:** the first page, with the logo, a main picture, a short welcome, the restaurant's values and buttons like About Us and Reserve Now.
- **Menu:** four groups (Drinks, Appetizers, Entrées and Desserts). Each dish has a picture, a short description and a price.
- **About Us:** the story of the restaurant and the master chefs.
- **Services:** what the restaurant offers, like private dining, events, wine and group bookings.
- **Reviews:** what guests say about the restaurant.
- **Contact:** a contact form, plus the address, phone number and opening hours.
- **Order (cart):** the page for the items you picked, with quantities, prices and a summary.
- **Reservation:** a form to book a table.

## Who it is for

- **People thinking of visiting:** they want the menu, prices, reviews and location.
- **Regular customers:** they want to come back quickly to order, book again or check the contact details.
- **Busy people:** they want the important things easy to find with no searching.
- **Couples, families and groups:** they plan ahead and use the reservation page.
- **New visitors:** they don't know the restaurant yet, so they need a bit more background.

---

## How it is built

The site is made with **HTML and CSS**, which is what the assignment asked for.

### Files

```
LOR/
├── index.html          Home
├── menu.html           Menu
├── about.html          About Us
├── services.html       Services
├── reviews.html        Reviews
├── contact.html        Contact
├── order.html          Order (cart)
├── reservation.html    Reservation
├── styles.css          All the styling
└── images/             Photos and the About video
```

You can open `index.html` in a browser, or right-click it in VS Code and choose **Open with Live Server**. If you change something and don't see it, refresh with Ctrl + F5.

### HTML and CSS

- Most of the styling is in the one **external CSS file**, `styles.css`. I used a few small inline styles in the HTML here and there.
- I used **classes** a lot. I give an element a class name in the HTML, like `card` or `btn`, and then style that name once in the CSS. That way the same look is used everywhere without repeating code.
- The colours (gold, black and the card colour) are saved at the very top of the CSS, so changing the colours of the whole site only takes a few lines.
- Rows and columns are used to line up the cards, pictures and text. On tablets and phones the columns stack on top of each other so everything still fits.
- The ring with the small dot on the page you are on in the menu bar, and the lines on both sides of the word RESTAURANT in the logo, are done with just CSS. There are no extra images for them.
- The leaves in the header and footer corners are one gold SVG drawing, flipped around with CSS. The floating leaves use the same kind of SVG leaf, and CSS makes them fall.
- The fonts come from Google Fonts.

### A note about JavaScript

The assignment only needs HTML and CSS, so **I did not add an external JavaScript file**. You will see a comment on the home page saying there is no JavaScript file.

The only JavaScript is a **few lines inside `menu.html`**. I added it because I wanted the menu to feel interactive and easy to use. It does these things:

- switches between Drinks, Appetizers, Entrées and Desserts and changes the big circle picture
- lets you pick how many of a dish you want and press **Add**
- shows the bar at the bottom with how many items you have and the subtotal
- makes the leaves float down the page

The other pages don't use JavaScript. That is why the **Order page shows the layout but stays empty**: filling it with the items you chose would need more JavaScript than the assignment asked for. The same goes for the contact and reservation forms: they are designed and ready, but they don't send anything yet.

### The footer

The Facebook, Instagram and TikTok icons in the footer go to the **real LŎR pages**. The details on the right (contact info) are only placeholders for the assignment, and the email is my own, **bangssarah04@gmail.com**, because I didn't have the restaurant's real email.

### What I would improve

- Add the JavaScript for the Order page so it lists what you picked.
- Make the contact and reservation forms really send.
- On phones, the four small cards on the reservation page are still squeezed into one row. I would stack them.

---

## What is not included

This project is about the design and the look of the website. It does not have a real database, online payment or a live booking system. The order and reservation parts show how it would work for the user, and they are not connected to anything real. They could be added later to turn this into a fully working website.

## Project Proposal

**Title:** Restaurant Website Design: A Modern Digital Dining Experience

The aim is to design a modern restaurant website that presents information clearly and gives users a simple digital experience for exploring the restaurant, viewing the menu, contacting the restaurant, placing an order and making a reservation.

### Background

- Customers need more than good food. Before visiting, they want to know what food is available, how much it costs, where the restaurant is, what services it offers, what other customers think, and whether they can reserve a table.
- A well-structured website brings all of this together in one place, so users don't have to search through different sources.
- LŎR was chosen because publicly available information shows a broad range of food and drink categories (breakfast, Japanese, Indian, Lebanese, Italian, international, dessert, Asian Thai and non-alcoholic drinks). This gave a good basis for a menu structure that is easy to browse without overwhelming users.
- The design follows a **user-centered approach**: it starts from what users need to do on the website, not from visual decoration alone. These needs guide the information architecture, navigation, wireframes and prototype.

---

## Proposed Solution

An independent, modern restaurant website concept based on the LŎR context, using a clear information architecture, consistent navigation, structured content and an interactive prototype.

### Pages

| Page | Purpose and content |
|---|---|
| **Home** | Starting point of the site: restaurant branding, a main visual area, a short introduction, key restaurant values, and calls to action such as View Menu and Reserve Now. |
| **Menu** | Food and drinks split into four categories: **Drinks, Appetizers, Entrées, Desserts**. Users pick a category and see item cards with the item name and price. |
| **About Us** | Restaurant background, supporting visuals, the restaurant experience and a section representing the chefs. Shows the identity of the restaurant, not only the menu. |
| **Services** | The dining experiences and services available, in clear sections with visuals and calls to action. |
| **Reviews** | A dedicated area for customer feedback and ratings, to help users decide. |
| **Contact Us** | A contact form (first name, last name, email, subject, comments or questions) plus contact details, location, phone and opening hours. |
| **Cart / Order** | Selected items, quantities, prices, an order summary and a checkout pathway. |
| **Reservation** | A structured reservation form. Flow: **Reservation → Enter Details → Review Information → Submit Reservation**. One of the main features of the site. |

### Consistent navigation

The main navigation is the same on every page:

**Home | Menu | About Us | Services | Reviews | Contact | Cart/Order | Reservation**

Important actions (View Menu, Reserve Now, Order, Submit Reservation, Contact Us) are shown as clear calls to action. A consistent header and footer help users understand the structure and move between sections.

---

## Target Users

The primary users are **potential and existing restaurant customers** who use computers, tablets or smartphones to find restaurant information and use restaurant services. Users visit for different reasons, so the site doesn't assume everyone has the same goal.

| User group | What they need |
|---|---|
| **Potential diners** | Learn about the restaurant, view the menu, check prices, explore services, read reviews, find the location, contact the restaurant and make a reservation. |
| **Existing customers** | Fast access to the menu again, prices, placing an order, making another reservation, contact details and opening information. |
| **Professionals and busy customers** | Clear navigation and direct paths to the menu, reservation, contact details and ordering, with little time spent searching. |
| **Couples, families and groups** | Explore the menu and restaurant information before deciding, and plan ahead with the reservation feature. |
| **Visitors and people unfamiliar with the restaurant** | Background information, location, menu, services, reviews, contact details and reservation options, with a clear structure because they don't know where things are. |

### Main user needs and how the website meets them

| User need | How the website addresses it |
|---|---|
| Find restaurant information | About Us page |
| Explore food and drinks | Categorized Menu page |
| Understand prices | Menu item cards with prices |
| Find restaurant services | Services page |
| See customer feedback | Reviews page |
| Contact the restaurant | Contact Us page and contact form |
| Find the location | Contact section |
| Make a reservation | Dedicated Reservation page |
| Place or review an order | Cart/Order page |
| Move around the website easily | Consistent navigation |
| Identify important actions | Clear buttons and calls to action |

**Design goal:** reduce unnecessary searching and give users clear paths to the information and actions they are most likely to need.

---

## Project Scope

**Included:** user research and design analysis, information architecture, navigation planning, sitemap, user journeys, wireframes, interface design and an interactive Figma prototype, plus this HTML/CSS/JavaScript build of the design.

**Not included:** a fully working restaurant system. There is no live database, payment gateway, real-time reservation system or production ordering system. The ordering, checkout and form features show the proposed user experience and are not connected to a real service. The concept is a foundation that could later be developed into a fully functional website.

---

# About the Code

A multi-page restaurant website built with plain HTML, CSS and JavaScript. No frameworks and nothing to install.

## Folder structure

Keep everything in one folder, like this:

```
LOR/
├── index.html          Home
├── menu.html           Menu (Drinks, Appetizers, Entrées, Desserts)
├── about.html          About Us
├── services.html       Services
├── reviews.html        Reviews
├── contact.html        Contact
├── order.html          Your Order (cart)
├── reservation.html    Make a reservation
├── styles.css          All the styling
├── script.js           Menu, cart, forms and floating leaves
└── images/             All photos and the About video
```

## How to run it

1. Open the `LOR` folder in VS Code.
2. Right-click `index.html` and choose **Open with Live Server**.
3. The site opens in your browser (usually `127.0.0.1:5500`).

You can also double-click `index.html` to open it directly. After changing any file, refresh with **Ctrl + F5** so the browser doesn't show an old copy.

## How it works

- **Navigation:** every page has the same header and footer. The page you are on gets a gold ring with a small dot on top.
- **Menu:** the dishes live in the `M` list at the top of `script.js` (name, description, price in le, image). The big circle picture for each category is in the `F` list just below it.
- **Cart:** items added on the menu page are saved in the browser, so the order stays when you move between pages. The cart count in the header and the order page both read from it.
- **Checkout:** not connected yet. The button shows a message asking guests to call to confirm.
- **Forms:** the contact and reservation forms show a confirmation message but do not send anything yet.

## Images needed

Put these in the `images` folder with exactly these names. A missing image is hidden and the gold placeholder shows instead.

- **Home and pages:** `signiture steak dish.jpg`, `dining.jpg`, `private room.jpg`, `sevices.jpg`, `tour.jpg`, `reviews (2).jpg`
- **About video:** `About.mp4` and its cover `about-video.jpg`
- **Chefs:** `jane sarah bangura.jpg`, `trevor samuels.jpg`, `gorden ramsy.jpg`, `bola ramsey.jpg`, `booby duflay.jpg`
- **Reviewers:** `katty.jpg`, `viv.jpg`, `mira.jpg`
- **Drinks:** `cocktail.jpg`, `martini.jpg`, `juice.jpg`, `water.jpg`, `alcohol.jpg`, `citrus.jpg`
- **Appetizers:** `eggs.jpg`, `beef.jpg`, `burrata.jpg`, `seared.jpg`
- **Entrées:** `rosemary.jpg`, `fish.jpg`, `chicken.jpg`, `risotto.jpg`
- **Desserts:** `chocolate.jpg`, `creme.jpg`, `tiramisu.jpg`, `ice cream.jpg`
- **Big menu circles:** `sig cocktail.jpg`, `cs.jpg`, `cd.jpg` (the entrée circle reuses `signiture steak dish.jpg`)

## Common edits

- **Change a price or dish:** edit the `M` list in `script.js`.
- **Change colours:** edit the values at the top of `styles.css` (`--gold`, `--bg`, `--panel` and so on).
- **Change address, phone or hours:** these appear in the footer and on the contact and reservation pages, so update each page.
- **Add a new page:** copy an existing page, change its content, then add a link to it in the header and footer of every page.

## Troubleshooting

- **Menu looks empty:** `script.js` is missing or not in the same folder as the pages.
- **Images missing:** check the file name and spelling in the `images` folder (names must match exactly).
- **Changes not showing:** refresh with Ctrl + F5.

---

## Conclusion

The project designs a modern restaurant website that gives users clear information and simple ways to interact with the restaurant. Using LŎR as a design reference, it turns the needs of potential and existing customers (menu and prices, restaurant details, reviews, contact information, ordering and reservations) into an information architecture, sitemap, navigation structure and user journeys. The wireframes and Figma prototype show how users would move through the Home, Menu, About Us, Services, Reviews, Contact Us, Cart/Order and Reservation pages, with consistent navigation and clearly identified actions.