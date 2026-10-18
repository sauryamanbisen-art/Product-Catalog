# 🛍️ LeapCart — Premium E-Commerce Catalog & Checkout Platform

<div align="center">

![HTML5](https://img.shields.io/badge/HTML5-E34F26?style=for-the-badge&logo=html5&logoColor=white)
![CSS3](https://img.shields.io/badge/CSS3-1572B6?style=for-the-badge&logo=css3&logoColor=white)
![JavaScript ES6+](https://img.shields.io/badge/JavaScript_ES6+-F7DF1E?style=for-the-badge&logo=javascript&logoColor=black)
![Tailwind CSS](https://img.shields.io/badge/Tailwind_CSS-38B2AC?style=for-the-badge&logo=tailwind-css&logoColor=white)
![SPA Routing](https://img.shields.io/badge/SPA-History_API-6366F1?style=for-the-badge)
![Zero Dependencies](https://img.shields.io/badge/Dependencies-Zero_Build_Step-00B8A9?style=for-the-badge)
![Status](https://img.shields.io/badge/Status-Production_Ready-success?style=for-the-badge)

<p align="center">
  <b>A state-of-the-art, responsive e-commerce web application featuring real-time faceted search, native HTML5 drag-and-drop cart addition, multi-step validated checkout, coupon engine, and live order tracking.</b>
</p>

[✨ Live Features](#-key-features) •
[📐 Architecture](#-system-architecture) •
[🧭 User Flow](#-application-workflow) •
[📂 Project Structure](#-directory-structure) •
[🚀 Quick Start](#-getting-started) •
[🎟️ Promo Codes](#-promotional-coupons)

</div>

---

## 🌟 Executive Summary

**LeapCart** is a modern frontend e-commerce platform built without heavy frameworks to prove the power of modern vanilla web standards. Powered by clean HTML5, custom CSS design tokens, Tailwind CSS utility classes, and modular ES6+ JavaScript, LeapCart delivers a native app-like experience with zero compilation overhead.

### ⚡ Key Metrics
* **270+ Curated Products** with high-resolution imagery, detailed descriptions, ratings, and stock status.
* **6 Major Categories & 20+ Subcategories** across Electronics, Apparel, Accessories, Fitness, Home Decor, and Kitchen.
* **8 Dynamic SPA Views** coordinated seamlessly via the browser History API without page reloads.
* **Dual-Input Range Slider** synchronizing dual thumbs and numerical inputs for price filtering up to ₹70,000.
* **Native Drag-and-Drop Shopping** allowing items to be dragged directly into a responsive floating drop zone.
* **3-Step Checkout Flow** with Luhn-algorithm card validation, phone/pincode format checks, and instant review.

---


#  Features

##  Product Catalog

* Responsive product grid layout
* Product cards displaying:

  * Image
  * Title
  * Category
  * Price
  * Rating
* Optional product detail modal/page

---

##  Search Functionality

* Real-time product search
* Keyword-based filtering
* Instant UI updates while typing

---

##  Filtering System

Users can filter products by:

* Category
* Price Range
* Ratings

Supports:

* Multiple filters together
* Dynamic filtered results

---

##  Shopping Cart

* Add products to cart
* Remove products from cart
* Increase/decrease quantity
* Auto-update total price
* Display cart item count
* Empty cart handling

---

##  Drag and Drop

* Drag product cards into cart
* Visual feedback during drag
* Instant cart updates after drop

---

##  Checkout System

Validated checkout form including:

* Full Name
* Email Address
* Phone Number
* Shipping Address
* City
* Pincode
* Payment Method

Validation includes:

* Required fields
* Email format checking
* Numeric validation
* Inline error messages
* Prevent invalid submission

---

#  Responsive Design

Application is optimized for:

* Desktop
* Tablet
* Mobile Devices

Responsive features include:

* Adaptive grid layouts
* Mobile-friendly cart
* Flexible filter section

---

#  Frontend Concepts Practiced

* State Management
* Array Filtering
* Controlled Components
* Form Validation
* Drag and Drop API
* Conditional Rendering
* Local Storage
* Responsive UI Design
* Component Communication

---

#  Recommended Tech Stack

## Core

* HTML
* CSS
* JavaScript

## Optional Modern Stack

* React
* Tailwind CSS
* Context API / Redux

---

#  Suggested Project Structure

```bash
src/
│
├── components/
│   ├── Header
│   ├── SearchBar
│   ├── Filters
│   ├── ProductList
│   ├── ProductCard
│   ├── Cart
│   ├── CartItem
│   └── CheckoutForm
│
├── data/
│   └── products.js
│
├── styles/
│   └── global.css
│
├── App.js
└── main.js
```

---

#  Sample Product Data

```js
{
  id: 1,
  title: "Wireless Headphones",
  category: "Electronics",
  price: 2999,
  rating: 4.5,
  image: "image-url"
}
```

---

#  Functional Requirements

| ID    | Requirement                | Priority     |
| ----- | -------------------------- | ------------ |
| FR-1  | Product catalog rendering  | MUST HAVE    |
| FR-2  | Product search             | MUST HAVE    |
| FR-3  | Category filter            | MUST HAVE    |
| FR-4  | Price range filter         | MUST HAVE    |
| FR-5  | Rating filter              | MUST HAVE    |
| FR-6  | Multiple filters together  | MUST HAVE    |
| FR-7  | Add to cart button         | MUST HAVE    |
| FR-8  | Drag-and-drop cart         | MUST HAVE    |
| FR-9  | Cart totals                | MUST HAVE    |
| FR-10 | Quantity controls          | MUST HAVE    |
| FR-11 | Checkout form validation   | MUST HAVE    |
| FR-12 | Validation error handling  | MUST HAVE    |
| FR-13 | Responsive design          | MUST HAVE    |
| FR-14 | Local Storage persistence  | GOOD TO HAVE |
| FR-15 | Animations and transitions | GOOD TO HAVE |

---

#  Error Handling

| Scenario                  | Expected Behaviour        |
| ------------------------- | ------------------------- |
| Empty search results      | Show “No products found”  |
| Empty cart                | Show empty cart message   |
| Invalid form input        | Inline validation message |
| Checkout without products | Prevent submission        |

---

#  Future Improvements

Future features that can be added later:

* Wishlist
* Product details page
* Authentication
* Payment gateway integration
* Coupons and discounts
* Backend API
* Order history
* Product sorting

---


#  Expected UI Sections

* Header/Navbar
* Search Bar
* Filter Sidebar
* Product Grid
* Shopping Cart
* Checkout Form
* Success/Error Messages

---





