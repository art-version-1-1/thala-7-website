# thala-7-website

A modern demo shoe shopping website built with HTML and CSS featuring a professional e-commerce layout inspired by the brand "THALA 7". This project showcases a clean, responsive navigation system and interactive UI elements.

## Overview

**THALA 7** is a fictional shoe brand website demonstrating best practices in front-end web design. The site features an engaging landing page with hero content, product imagery, and a full-featured navigation bar with dropdown menus.

## Features

### Navigation & Layout
- **Branded Header** with THALA 7 logo (dual-color styling)
- **Dynamic Navigation Bar** with:
  - Navigation links: Home, About, Contact
  - **Dropdown menus** for Brands (Nike, Adidas, Puma, Reebok)
  - **Dropdown menus** for More (New Arrivals, Sale, Best Sellers, FAQs)
  - Custom-styled search box with rounded corners and focus state effects
  - Shopping cart icon area
  - Login button with hover effects

### User Interface
- **Hero Section** with large tagline "7!! Thala For A Reason!" and descriptive content
- **Prominent Call-to-Action** (`Shop Now` button) styled as a clickable link with hover animations
- **Product Image Display** featuring shoe product imagery
- **Color Theme** using CSS variables (Primary: #ff5c0b, Secondary: #0d05b3ca)
- **Smooth Transitions** on interactive elements (nav links, buttons, dropdown menus)
- **Professional Footer** with consistent branding

### Interactive Elements
- Navigation link hover effects with color change and scale animation
- Search input focus states with border color transitions
- Dropdown menu visibility on hover with smooth appearance
- Button hover effects with secondary color background
- Shopping cart and login interactive areas

### Product Pages
- **Product Detail Page** (`shoe-page.html`) with:
  - Auto-sliding image carousel (5 product images)
  - Product description and pricing
  - Quantity selector dropdown
  - Add to Cart button
  - Breadcrumb navigation

### Shopping Cart
- **Cart Page** (`cart.html`) with:
  - Item table with product details, price, quantity controls
  - Bill summary with subtotal, shipping, total
  - Coupon code input and apply button
  - Checkout button

### Checkout Process
- **Checkout Page** (`checkout.html`) with:
  - Contact information form (name, email)
  - Payment details form (card number, expiry, CVV)
  - Order summary with bill breakdown
  - Proceed to checkout button

### Mobile Responsiveness
- **Responsive Design** optimized for all screen sizes
- **Mobile Navigation** with simplified navbar
- **Flexible Layouts** that stack on smaller screens
- **Touch-Friendly** buttons and inputs

## Technology Stack

- **HTML5** — semantic markup and structure
- **CSS3** — styling, flexbox layout, transitions, animations, media queries
- **Responsive Design** — mobile-first approach with breakpoints

## Project Structure

```
thala-7-website/
├── index.html           # Main landing page
├── shoe-page.html       # Product detail page with slider
├── cart.html            # Shopping cart page
├── checkout.html        # Checkout form page
├── style.css            # Global styles and responsive layout
├── images/              # Image assets
│   ├── 7.jpg           # Brand logo
│   ├── shoe-main.jpg   # Main product image
│   ├── s2.jpg          # Product side view
│   ├── s3.jpg          # Product back view
│   ├── s4.jpg          # Product details
│   ├── s5.jpg          # Additional product view
│   └── 10252891.png    # Cart icon
├── README.md           # Project documentation
└── LICENSE             # Project license
```

## Getting Started

1. Clone or download the project folder.
2. Open `index.html` in your web browser.
3. Navigate through the site using the navbar links and dropdown menus.
4. Click "Shop Now" to view the product page.
5. Add items to cart and proceed to checkout.

## Customization

### Colors
All colors are defined as CSS variables in the `:root` selector. Update them to match your brand:
```css
--primary-color: #ff5c0b;      /* Orange accent */
--secondary-color: #0d05b3ca;  /* Blue accent */
--background-color: #f4f4f4;   /* Light gray */
--text-color: #333;            /* Dark text */
```

### Dropdown Items
Edit the dropdown menu items in the HTML files under the `.dropdown` list items to customize Brands and More sections.

### Images
Replace images in the `images/` folder with your own product photos or branding assets.

### Content
Update product descriptions, prices, and text content in the HTML files to match your products.

## Files Overview

- **index.html** — Main landing page with navbar, hero section, and product showcase
- **shoe-page.html** — Product detail page with image slider, description, and add to cart
- **cart.html** — Shopping cart with item list and bill summary
- **checkout.html** — Checkout form with contact and payment details
- **style.css** — Complete styling including navbar, dropdowns, forms, cart, checkout, and responsive design
- **images/** — Directory for brand logos and product images
- **README.md** — Project documentation (this file)

## Key CSS Classes

- `.navbar` — Main navigation container
- `.nav-links` — Navigation menu links
- `.dropdown` — Dropdown menu wrapper
- `.dropdown-menu` — Hidden menu revealed on hover
- `.search-box` — Styled search input container
- `.shoe-order` — Call-to-action button
- `.home-left` — Hero content section
- `.home-right` — Product image section
- `.slider-track` — Image carousel container
- `.cart-main` — Cart page container
- `.sc-item` — Cart items table
- `.sc-bill` — Bill summary card
- `.checkout-main` — Checkout page layout
- `.left-checkout` — Checkout form section
- `.right-checkout` — Checkout summary section

## Browser Compatibility

Works on all modern browsers supporting CSS3 flexbox and transitions (Chrome, Firefox, Safari, Edge).

## Responsive Breakpoints

- **Desktop**: > 900px (full layout)
- **Tablet**: 600px - 900px (stacked sections)
- **Mobile**: < 600px (simplified navbar, centered content)

## Notes

- The site uses a desktop-first design approach with mobile optimizations
- The `Shop Now` button is implemented as an anchor link for semantic HTML
- Dropdown menus appear on hover and are hidden by default
- Image slider uses CSS animations for smooth transitions
- All transitions use 0.3s ease timing for smooth animations
- Cart and checkout pages include form validation-ready inputs
- Future expansion could include JavaScript for enhanced interactivity, cart functionality, and payment processing

