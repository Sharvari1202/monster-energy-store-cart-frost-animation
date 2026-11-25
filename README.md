# ⚡ Monster Energy – Interactive 3D E-Commerce Store

An immersive, modern Monster Energy product showcase and e-commerce demo featuring 3D can animations, realistic frost effects, moving icy smoke, condensation droplets, interactive product selection, and a shopping cart with a Node.js and Express backend.

Explore different Monster Energy flavours through an engaging, scroll-based experience with dynamic backgrounds, animated product visuals, and an interactive shopping interface.

## 🚀 Features

### 🎨 3D Product Showcase
- Interactive Monster Energy can showcase.
- Animated 3D-style can rotation.
- Smooth scroll-based product movement.
- Mouse-responsive product animations.
- Dynamic background colour transitions.
- Multiple Monster Energy flavour selections.

### ❄️ Frost & Ice Animation Effects
- Animated icy smoke surrounding the can.
- Frost-inspired visual effects.
- Ice crystal sparkle animations.
- Realistic-looking water droplets and condensation.
- Smooth floating and rotating can animations.
- Dynamic cold-glow effects.
- Moving smoke and can animations while scrolling.

### ⚡ Multiple Monster Energy Flavours
- Monster Energy Original – Green theme.
- Monster Ultra Sunrise – Orange theme.
- Monster Ultra Blue Hawaiian – Blue theme.
- Monster Lewis Hamilton – Red theme.
- Monster Ultra White – Silver and white theme.

### 🛒 Shopping Cart System
- Browse Monster Energy products.
- Add products to the shopping cart.
- Increase or decrease product quantities.
- Remove products from the cart.
- Automatic cart quantity calculation.
- Dynamic total price calculation.
- Interactive cart drawer.
- Checkout form integration.

### 📦 Order Management
- Customer information form.
- Product and quantity selection.
- Delivery address collection.
- Backend order submission.
- Order validation.
- Automatic order ID generation.
- Save orders in a JSON file.

### 📱 Responsive Design
- Desktop, tablet, and mobile support.
- Responsive product layouts.
- Mobile-friendly shopping cart.
- Smooth navigation and scrolling.
- Modern UI with premium visual styling.

## 🛠️ Technologies Used

**Frontend**
- HTML5
- CSS3
- JavaScript
- CSS Animations
- Responsive Web Design

**Backend**
- Node.js
- Express.js
- REST API
- JSON File Storage

**Design & Animation**
- 3D-style CSS transforms
- Keyframe animations
- Gradient effects
- Glassmorphism-inspired UI
- Scroll-based animations

## 📂 Project Structure

```text
monster-energy-store-cart-frost-animation/
│
├── assets/
│   ├── monster-energy-logo.png
│   ├── original.png
│   ├── sunrise.png
│   ├── blue-hawaiian.png
│   ├── lewis-hamilton.png
│   └── ultra-white.png
│
├── backend/
│   └── server.js
│
├── data/
│   └── orders.json
│
├── index.html
├── package.json
└── README.md
```

## ⚙️ Installation & Setup

### 1. Clone the Repository

```bash
git clone https://github.com/YOUR-USERNAME/monster-energy-store-cart-frost-animation.git
```

### 2. Navigate to the Project

```bash
cd monster-energy-store-cart-frost-animation
```

### 3. Install Dependencies

```bash
npm install
```

### 4. Start the Backend Server

```bash
npm start
```

### 5. Open in Browser

```text
http://localhost:3000
```

## 🔗 REST API Endpoints

| Method | Endpoint | Description |
|---|---|---|
| GET | `/api/health` | Check backend status |
| GET | `/api/flavours` | Retrieve product details |
| POST | `/api/orders` | Submit a customer order |

### Sample Order Request

```json
{
  "customerName": "John",
  "email": "john@example.com",
  "phone": "9876543210",
  "flavourId": "original",
  "quantity": 2,
  "address": "Mumbai, Maharashtra"
}
```

## 💡 Project Highlights

- Combines creative UI/UX design with full-stack development.
- Interactive animations create an immersive product experience.
- Dynamic product selection with flavour-based themes.
- Shopping cart with real-time quantity and price updates.
- REST API integration using Node.js and Express.
- Backend order storage using JSON files.
- Responsive interface for different screen sizes.

## 🔮 Future Enhancements

- User authentication and registration.
- Database integration using MongoDB or MySQL.
- Payment gateway integration.
- Order history and tracking.
- Product search and filtering.
- Admin dashboard.
- Wishlist functionality.
- Deployment with a live demo URL.

## ⚠️ Important Note

This project is an educational full-stack e-commerce demonstration. Product prices are illustrative INR values. Checkout demonstrates order submission and JSON-based storage. No real payment gateway or delivery service is connected.

## 👩‍💻 Author

**Sharvari Jadhav**

GitHub: [https://github.com/Sharvari1202)

LinkedIn: [)

## ⭐ Support

If you like this project, consider giving it a ⭐ on GitHub!

**Unleash the Beast! ⚡**
