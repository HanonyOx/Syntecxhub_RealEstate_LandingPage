# 🏡 HomeNest — Real Estate Landing Page

HomeNest is a modern, responsive real estate website designed to provide users with a clean and intuitive platform for discovering properties, exploring real estate services, reading property-related articles, and learning more about the brand.

The project focuses on creating a professional real estate experience using **HTML5 and CSS3**, with responsive layouts that adapt across desktop, tablet, and mobile screen sizes.

---

## 📌 Project Overview

HomeNest was created as a frontend development project to practice and demonstrate skills in:

* Semantic HTML
* Modern CSS layouts
* Responsive web design
* CSS Flexbox
* CSS Grid
* CSS variables
* Media queries
* Hover effects and transitions
* Font Awesome icons
* Google Fonts
* Image integration
* Navigation using anchor links
* Responsive footer design

The website is structured as a single-page real estate platform with multiple sections that users can navigate through from the navigation bar.

---

## ✨ Features

### 🧭 Responsive Navigation

The navigation bar provides quick access to the major sections of the website:

* Home
* Properties
* About Us
* Services
* Contact Us

The navigation automatically adapts to different screen sizes. On tablet and mobile devices, the desktop navigation is replaced with a hamburger menu icon.

---

### 🏠 Hero Section

The homepage features a large hero section with a real estate background image and a clear call-to-action.

It includes:

* HomeNest branding
* Navigation menu
* Main headline
* Supporting description
* Buy/Rent/Sell options
* Property search form

The hero section is designed to immediately communicate the purpose of the website and encourage users to search for properties.

---

### 🔎 Property Search Form

The search interface allows users to specify:

* Location
* Property type
* Price range

Users can also switch between:

* Buy
* Rent
* Sell

The form uses styled inputs, dropdown menus, icons, and responsive layouts to maintain usability across different devices.

---

### 🏘️ Featured Properties

The Featured Properties section displays a collection of property cards.

Each property card contains:

* Property image
* Property name
* Location
* Number of bedrooms
* Number of bathrooms
* Property size
* Price

The cards also include interactive hover effects. When the user hovers over a property card, the card moves upward and the property image zooms slightly.

---

### ⭐ Why Choose HomeNest

This section explains why users should choose HomeNest when searching for a property.

It contains four feature cards:

1. **Verified Properties**

   * Properties are presented as being verified for quality and authenticity.

2. **Best Price Guarantee**

   * Highlights competitive property pricing.

3. **Expert Support**

   * Communicates that users can receive assistance throughout the process.

4. **Easy Process**

   * Emphasizes a simple and transparent property-search experience.

---

### 📊 Company Statistics

The statistics section provides quick information about the fictional HomeNest brand.

Current statistics include:

* **10K+** Properties Listed
* **25K+** Happy Clients
* **15+** Years of Experience
* **50+** Expert Agents

These statistics are presented using cards with Font Awesome icons.

---

### 💬 Customer Testimonials

The testimonial section provides social proof through customer reviews.

Each testimonial includes:

* Customer profile image
* Customer name
* Customer role
* Review
* Quote icon

The testimonials are arranged using CSS Grid and automatically adjust based on the device's screen size.

---

### 📰 Latest News & Tips

The website also contains an articles section where users can discover real estate-related content.

Example articles include:

* 10 Tips for First-Time Home Buyers
* Best Neighborhoods to Invest In
* How to Increase Your Property Value
* Real Estate Market Trends

Each article contains an image, title, publication date, and a "more..." indicator.

---

### 📩 Newsletter

The footer contains a newsletter subscription area where visitors can enter their email address and subscribe to receive property updates and news.

The newsletter section is designed to become more compact on tablet and mobile devices.

---

### 🔗 Footer

The footer contains several navigation categories:

#### Quick Links

* Home
* Properties
* About Us
* Services
* Contact Us

#### Property Types

* Apartments
* Houses
* Villas
* Townhouses
* Luxury Properties

#### Support

* Help Center
* Terms of Services
* Privacy Policy
* FAQ

#### Social Media

The footer also includes icons for:

* Facebook
* X
* Instagram
* LinkedIn

---

## 📱 Responsive Design

HomeNest is designed to work across multiple screen sizes.

### 💻 Desktop

On larger screens:

* Four property cards are displayed per row.
* Four feature cards are displayed per row.
* Four testimonials are displayed per row.
* Four articles are displayed per row.
* The full navigation menu is visible.
* The footer displays its different columns horizontally.

### 📱 Tablet

On tablet-sized screens:

* Property cards change to two columns.
* Feature cards change to two columns.
* Testimonials change to two columns.
* Articles change to two columns.
* Desktop navigation is replaced with a hamburger menu.
* Footer sections stack vertically.
* Footer lists can be collapsed/expanded through the plus icon design.

### 📱 Mobile

On smaller screens:

* Content changes to a single-column layout.
* Property cards stack vertically.
* Testimonials stack vertically.
* Articles stack vertically.
* The navigation menu is replaced with a hamburger icon.
* Search form controls stack vertically.
* Footer content becomes vertically arranged.
* Hero typography is reduced to fit smaller screens.

---

## 🎨 Design System

The project uses CSS custom properties to maintain a consistent visual identity.

### Primary Colors

| Variable              | Purpose                       |
| --------------------- | ----------------------------- |
| `--primary-navy`      | Main dark/navy color          |
| `--accent-gold`       | Primary brand accent          |
| `--accent-gold-hover` | Hover state for gold elements |
| `--accent-light-gold` | Light text/accent background  |
| `--text-heading`      | Main heading color            |
| `--text-body`         | Body text                     |
| `--text-muted`        | Muted text                    |
| `--text-light`        | Light/white text              |
| `--bg-main`           | Main page background          |
| `--bg-card`           | Card background               |
| `--bg-dark-footer`    | Footer background             |
| `--border-light`      | Light borders                 |

Using CSS variables makes it easier to update the overall theme without having to modify individual selectors throughout the stylesheet.

---

## 🔤 Typography

The project uses two Google Fonts:

* **Inter**
* **Plus Jakarta Sans**

The primary body font is:

```css
font-family: "Plus Jakarta Sans", sans-serif;
```

The typography was selected to give the website a modern, clean, and professional appearance.

---

## 🧩 Technologies Used

### HTML5

Used to create the structure and semantic content of the website.

Major HTML elements include:

* `<nav>`
* `<section>`
* `<div>`
* `<form>`
* `<input>`
* `<select>`
* `<button>`
* `<footer>`

---

### CSS3

CSS is responsible for the complete visual presentation of the project.

The project makes use of:

* CSS Variables
* Flexbox
* CSS Grid
* Media Queries
* Transitions
* Hover Effects
* Background Images
* Responsive Units
* Box Shadows
* Border Radius
* CSS positioning

---

### Font Awesome

Font Awesome is used for interface and social media icons.

Examples include:

* House icon
* Location icon
* Bed icon
* Bathroom icon
* Search-related icons
* Facebook
* X
* Instagram
* LinkedIn
* Plus icon
* Arrow icons

---

### Google Fonts

Google Fonts provides the typography used throughout the project.

---

### Unsplash

Property and testimonial images are sourced from Unsplash.

---

## 📂 Project Structure

A simple version of the project structure is:

```text
HomeNest/
│
├── Images/
│   └── house.jpg
│
├── index.html
├── style.css
└── README.md
```
---

## 🖥️ Browser Compatibility

The website is designed to work with modern browsers such as:

* Google Chrome
* Microsoft Edge
* Mozilla Firefox
* Safari

For the best experience, it is recommended to use an up-to-date browser.

---

## 🎯 Project Goals

The main goals of this project were to:

1. Build a professional real estate landing page.
2. Practice creating responsive layouts.
3. Improve understanding of CSS Grid and Flexbox.
4. Practice creating reusable visual components using HTML and CSS.
5. Implement responsive behavior using media queries.
6. Improve UI/UX design skills.
7. Practice using external fonts and icon libraries.
8. Create a project suitable for a frontend development portfolio.

---

## 🧠 What I Learned

Building HomeNest provided practical experience with several frontend concepts.

### Responsive Layouts

I learned how to change layouts depending on screen size using media queries.

For example, a four-column desktop grid can become a two-column tablet layout and eventually a single-column mobile layout.

### CSS Grid

CSS Grid was particularly useful for:

* Property cards
* Feature cards
* Statistics
* Testimonials
* Articles

### Flexbox

Flexbox was used extensively for:

* Navigation
* Forms
* Footer sections
* Card content
* Buttons
* Icon alignment

### CSS Variables

Using CSS variables helped maintain consistent colors throughout the application and made the design easier to maintain.

### UI Interactions

Transitions and hover effects were used to make the website feel more interactive.

Examples include:

* Property card movement
* Property image zoom
* Button hover effects
* Navigation underline animation
* Social media icon hover effects

---

## 🔮 Future Improvements

Although the current project is primarily a frontend UI project, several features could be added in the future.

### Functional Property Search

The search form could be connected to JavaScript or a backend API to allow users to actually filter properties based on:

* Location
* Property type
* Price
* Buy/Rent/Sell

### Property Details

Each property card could link to a dedicated property details page containing:

* More images
* Full property description
* Amenities
* Location
* Agent information
* Contact options

### Authentication

User authentication could be implemented so visitors can:

* Create accounts
* Log in
* Save properties
* Manage their profile

### Backend Integration

A backend could be added to manage:

* Properties
* Users
* Agents
* Testimonials
* Newsletter subscriptions
* Contact forms

### Database

A database such as MongoDB or PostgreSQL could be used to store property and user information.

### Mobile Navigation

The hamburger menu can be connected to JavaScript so users can open and close the mobile navigation menu.

### Newsletter Functionality

The newsletter form can be connected to a backend or email service to store subscriber information and send updates.

---

## ⚠️ Current Limitations

This version of HomeNest is primarily a **frontend UI project**.

Some features are currently visual rather than fully functional:

* Property search does not perform real filtering.
* Buy/Rent/Sell buttons are UI elements.
* Newsletter subscription does not currently submit data to a backend.
* Property cards do not contain dedicated property detail pages.
* The hamburger menu requires JavaScript functionality.
* Social media icons are currently presentation elements.
* Property information is static.

---


## 👨‍💻 Author

**Anthony Omeh**

Frontend Developer | Aspiring Software Developer

This project represents my continued journey in frontend development and my effort to build practical projects while improving my understanding of modern web development.

---

## ⭐ Support

If you found this project useful or interesting, consider giving the repository a ⭐ on GitHub.

Thank you for checking out **HomeNest**! 🏡
