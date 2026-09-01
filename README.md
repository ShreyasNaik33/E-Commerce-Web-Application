# NEXUS // E-Commerce Web Application

A single static file e-commerce web application with product catalog management, shopping cart, express checkout, order tracking, admin portal, and Indian Rupee (₹ INR) currency pricing. Built for direct deployment to Vercel.

![Nexus E-Commerce Platform](https://images.unsplash.com/photo-1550745165-9bc0b252726f?auto=format&fit=crop&w=1200&q=80)

## Features

- 🛍️ **Interactive Product Catalog**: 12 high-tech products across 6 hardware categories (Audio, Wearables, Peripherals, Displays, Gaming, Smart Home).
- 🔍 **Search & Category Filters**: Real-time keyword search, category pills, and sorting by Price (Low to High / High to Low), Top Rated, and Featured.
- 🖼️ **Product Spec Detail Modal**: Click on any product card to view detailed specifications, stock availability, ratings, and warranty info.
- 🛡️ **Image Fallback Protection**: Automatic error handlers to ensure high-res fallback images render seamlessly without broken links.
- 🛒 **Slide-Over Shopping Cart**: Live quantity adjustment, subtotal calculation in INR (`₹`), and express checkout trigger.
- 💳 **Interactive Payment Gateways**: Simulated checkout options for UPI/GPay/PhonePe, Credit/Debit Card, NetBanking, and Crypto with live authorization state & transaction reference IDs.
- 📦 **Order Logistics & Tracking Registry**: Real-time 4-step animated timeline (`Placed` → `Processing` → `Dispatched` → `Delivered`) plus an **All Orders Tracking Registry**.
- 🔐 **Admin Portal & Inventory Management**: Role switcher (Demo Customer / Demo Admin), revenue KPI stats, product add/edit/delete CRUD, and customer order status updates.
- 🚀 **Zero-Config Vercel Deployment**: Everything (HTML, CSS, JS, database engine) is packed into `index.html` for single-click Vercel static deployment.

## Quick Start

1. Clone or download this repository.
2. Open `index.html` in any web browser.
3. Or deploy to Vercel:
   ```bash
   npx vercel
   ```

## Technologies Used

- **HTML5 & Semantic Structure**
- **Vanilla CSS3** (Dark glassmorphic aesthetic, custom CSS variables, CSS grid/flexbox, keyframe animations)
- **Vanilla JavaScript ES6+** (Virtual database engine with LocalStorage state persistence)

## License

MIT License
