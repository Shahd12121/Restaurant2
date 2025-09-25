# Delicious Restaurant

Delicious Restaurant is a responsive, modern website for showcasing a restaurant's menu, services, and reservations. It is designed with a focus on clean design, user-friendly navigation, and responsiveness across devices.

## Table of Contents
- [Overview](#overview)
- [Features](#features)
- [Technologies Used](#technologies-used)
- [Installation](#installation)
- [Usage](#usage)
- [Project Structure](#project-structure)
- [Screenshots](#screenshots)
- [License](#license)

## Overview
This website provides visitors with a beautiful interface to explore the restaurant's offerings. Users can browse the menu, learn about the restaurant, view customer testimonials, and make table reservations online. The site is fully responsive and works well on mobile, tablet, and desktop devices.

## Features
- **Responsive Design:** Optimized for all screen sizes.
- **Hero Section:** Eye-catching introduction with a call-to-action button.
- **Menu Section:** Displays menu items with images, names, and prices.
- **About Section:** Highlights the restaurant's story and ambiance.
- **Testimonials Section:** Showcases customer feedback.
- **Reservation Form:** Users can book a table with name, email, phone, date, time, and special requests.
- **Sticky Navbar:** Smooth navigation across sections.
- **Footer with Social Links:** Links to Facebook, Instagram, and Twitter.

## Technologies Used
- HTML5
- CSS3 (Custom + Responsive)
- Bootstrap 5.3
- Font Awesome 6

## Installation
1. Clone the repository:  
   ```bash
   git clone https://github.com/yourusername/delicious-restaurant.git
2. Open the folder and locate the index.html file.
3. Open index.html in your preferred browser to view the website.

## Usage

1. Use the navigation bar to jump to different sections: Home, Menu, About, Reservation.

2. Click the Order Now button in the Hero section to scroll to the menu.

3. Fill in the Reservation Form to submit a table booking.

4. Testimonials show customer feedback in a card format.

5. Footer contains social media links for user engagement.

## Project Structure

delicious-restaurant/
│
├─ index.html          # Main HTML file
├─ style.css           # Custom CSS styles
├─ images/             # Folder containing all images used in the website
│   ├─ pizza.png
│   ├─ burger.png
│   ├─ pasta.png
│   ├─ salad.png
│   ├─ sushi.png
│   └─ cake.png
└─ README.md           # Project documentation

## How to Customize
1. Changing Text

- Open index.html.

- Locate the section you want to edit:

- Hero Section: Change the heading and paragraph inside <section class="hero">.

- Menu Section: Edit <h5> for item names and <p> for prices.

- About Section: Modify the <h2> and <p> tags.

- Testimonials: Change the <p> for feedback and <h6> for customer names.

2. Changing Images

- Replace images inside the images/ folder with your own images. Make sure the filenames match or update the src attribute in index.html.

- For Hero section background, update the background property in .hero class inside style.css:

.hero {
  background: url("images/your-new-hero.jpg") center/cover no-repeat;
}

3. Updating Menu Items

- Add or remove menu items by copying one of the <div class="col-6 col-md-4 col-lg-2"> blocks inside the Menu section.

- Change the image, item name, and price as needed.

4. Modifying Reservation Form

- The form is in index.html inside <section id="reservation">.

- You can add more fields or modify placeholders by editing <input> and <textarea> tags.

5. Changing Colors & Styles

- Open style.css.

- Update colors, fonts, button styles, or layout according to your preference.

