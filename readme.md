# 👟 Thala7 - Sneaker Store

**Thala7-Sneaker Store** is a modern and responsive frontend website for an online shoe and sneaker store. The project provides a clean shopping experience with product details, shopping cart, checkout/payment UI, contact section, and responsive layouts for mobile and tablet devices.

> **Note:** This is a frontend/static project. No JavaScript, backend, database, or real payment gateway has been implemented.

## 🌟 Features

* 🏠 Home page with hero section
* 👟 Product details page
* 🛒 Shopping cart interface
* 💳 Checkout/payment interface
* 🔎 Search box UI
* 🏷️ Brand and category selection
* 📦 Product quantity selection
* 🎟️ Coupon code UI
* 💰 Price summary with subtotal, tax, discount, and total
* 💳 Multiple payment method UI:

  * Card
  * Crypto
  * Bank
  * More options
* 📱 Responsive design for mobile and tablet screens
* 📞 Contact section with contact information
* 📝 Contact form
* ⭐ Store achievements/statistics section
* 🎨 Font Awesome icons
* 🖼️ Product and payment-related images

## 🛠️ Technologies Used

| Technology        | Purpose                       |
| ----------------- | ----------------------------- |
| HTML5             | Website structure and content |
| CSS3              | Styling and layout            |
| CSS Media Queries | Responsive design             |
| Font Awesome      | Icons                         |
| PNG Images        | Product and UI graphics       |

## 📂 Project Structure

```text
Thala7-Sneaker-Store/
│
├── index.html
├── product.html
├── cart.html
├── payment.html
│
├── style.css
├── mediaquery.css
│
├── images/
│   ├── hero-img.png
│   ├── shoes_for_men-1.png
│   ├── shoes_for_men-2.png
│   ├── shoes_for_men-3.png
│   ├── shoes_for_men-4.png
│   ├── shoes_for_men-5.png
│   ├── cross sign.png
│   ├── secure-payment1.png
│   ├── secure-payment2.png
│   └── rozar-pay.png
│
└── README.md
```

## 📄 Pages

### 🏠 Home Page — `index.html`

The home page contains:

* Fixed navigation bar
* Thala7 logo
* Navigation links
* Brand and category dropdowns
* Search box
* Shopping cart icon
* Profile icon
* Hero section
* About section
* Contact section
* Store achievements

The hero section includes a **Shop Now** button that takes the user to the product page.

### 👟 Product Page — `product.html`

The product page displays:

* Product image
* Product name
* Product description
* Product price
* Discount information
* Quantity selector
* Add to Cart UI
* Additional product images
* About section
* Contact section

### 🛒 Shopping Cart — `cart.html`

The cart page contains:

* Product list
* Quantity controls
* Product prices
* Remove buttons
* Coupon code section
* Subtotal
* Taxes
* Discount
* Total amount
* Pay Now button
* Secure payment graphics
* Continue Shopping option

### 💳 Payment Page — `payment.html`

The payment page provides a checkout UI containing:

* Contact details
* Email input
* Card payment option
* Crypto payment option
* Bank payment option
* Card number field
* Expiry date
* CVC
* Country selection
* ZIP code
* Coupon code
* Order summary
* Payment/security graphics

## 🎨 Design

The website uses a simple modern color scheme based on:

* Orange
* Blue
* White
* Black

CSS custom variables are used for the main colors and UI elements.

The project also uses:

* Flexbox
* CSS Grid
* Fixed positioning
* CSS variables
* Custom buttons
* Form styling
* Horizontal product image scrolling

## 📱 Responsive Design

The project includes a separate `mediaquery.css` file for responsive layouts.

### Mobile

Responsive styling is provided for:

```text
320px - 430px
```

The mobile layout changes the structure of the hero section, product section, cart, payment section, contact section, and footer to fit smaller screens.

### Tablet

Responsive styling is provided for:

```text
768px - 1024px
```

Tablet-specific adjustments are applied to the navigation, hero section, product page, cart, payment page, and contact section.

## 🔗 Navigation Flow

```text
Home
 │
 ├── Shop Now
 │      ↓
 │   Product Page
 │      ↓
 │   Shopping Cart
 │      ↓
 │   Payment Page
 │
 ├── About
 │
 └── Contact
```

## 🚀 How to Run

No installation or build process is required.

### 1. Download or clone the project

```bash
git clone <your-repository-url>
```

### 2. Open the project folder

```text
cd Thala7-Sneaker-Store
```

### 3. Run the website

Open:

```text
index.html
```

in any modern web browser.

You can also use **VS Code + Live Server** for easier development.

## 📦 External Dependency

The project uses **Font Awesome** through its CDN for icons.

Examples include:

* Shopping cart
* User profile
* Search
* Heart
* Users
* Medal
* Star
* Credit card
* Bitcoin
* Bank

## ⚠️ Current Limitations

This project is currently a **static frontend website**.

The following functionality is UI-only:

* Search functionality
* Add to Cart functionality
* Quantity updates
* Remove from Cart
* Coupon validation
* Payment processing
* User profile
* Contact form submission
* Product/category filtering

There is currently:

* ❌ No JavaScript
* ❌ No backend
* ❌ No database
* ❌ No authentication system
* ❌ No real payment gateway
* ❌ No server-side form processing

## 🔮 Future Improvements

The project can be extended by adding:

* JavaScript-based cart functionality
* Dynamic product filtering
* Search functionality
* Product data management
* Local Storage
* User authentication
* Backend API
* Database integration
* Real payment gateway
* Order management
* Admin dashboard
* Contact form backend
* Product reviews and ratings

## 👨‍💻 Author

**Subhendu Tewary**

### Project

**Thala7 - Sneaker Store**

A frontend web development project built using HTML5 and CSS3.

## 📜 License

This project is created for educational and portfolio purposes.
