# Shopify Technical Assessment - Custom Sections

This repository contains custom Shopify theme sections developed for the Ecomexperts technical assessment. The focus was on high-performance Liquid templating, responsive CSS design, and complex conditional logic using Vanilla JavaScript.

## Implemented Features

### 1. Gift Guide Banner
A responsive hero banner featuring:
* **Glassmorphism Design:** Modern aesthetic using CSS blur and transparency.
* **Button Animations:** Hover effects including scaling and a glow pulse.
* **Customizer Support:** Fully editable text, images, and links.

### 2. Product Grid Popup & Bundle Logic
An advanced interactive section featuring:
* **Hotspots:** Pulsing "+" icons for user interaction.
* **AJAX Fetching:** Real-time product data retrieval without page refreshes.
* **"The Devil in the Details" Bundle:** * **Logic:** If 'Black' and 'Medium' are selected, the 'Soft Winter Jacket' is automatically added to the cart.
    * **Implementation:** Built using the Shopify AJAX API (`/cart/add.js`) and Vanilla JS.

## Architecture
* **Modular Styling:** CSS is moved to external asset files (`assets/`) for better caching.
* **No jQuery:** All scripts are written in pure ES6+ JavaScript.
* **Self-Contained Sections:** Sections are designed to be portable across different themes.

## Submission Details
* **GitHub Repository:** [Srikanth-Nadimpalli](https://github.com/srikanthraju0312/Srikanth-Nadimpalli)
* **Branching Strategy:** Work performed in `dev` branch with a formal Pull Request to `master`.
* **Testing:** Verified for mobile responsiveness and edge-case logic triggers.

---
*Developed by Srikanth Raju Nadimpalli*