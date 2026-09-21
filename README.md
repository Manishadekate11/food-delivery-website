 # 🍔 Foodie Express — Food Delivery Website

A modern, responsive food delivery web application where users can browse dishes by category, search for their favorite food, add items to a live shopping cart, and place orders — all with smooth animations and real-time feedback.

Built as a hands-on project to learn React fundamentals, state management (Context API + Redux Toolkit), and modern UI development with Tailwind CSS.

![React](https://img.shields.io/badge/React-19-61DAFB?logo=react&logoColor=white)
![Vite](https://img.shields.io/badge/Vite-8-646CFF?logo=vite&logoColor=white)
![Redux](https://img.shields.io/badge/Redux%20Toolkit-764ABC?logo=redux&logoColor=white)
![Tailwind](https://img.shields.io/badge/TailwindCSS-4-38B2AC?logo=tailwind-css&logoColor=white)

---

## 🌐 Live Demo

🔗 [https://manisha-food-delivery-website.netlify.app/](#) <!-- Replace # with your deployed Vercel/Netlify link -->

---

## 📸 Screenshots

<!-- Add screenshots here once deployed, e.g. -->
<!-- ![Homepage](./screenshots/home.png) -->
<!-- ![Cart Drawer](./screenshots/cart.png) -->

---

## ✨ Features

### ✅ Currently Working
- 🔍 **Live Search** — instantly filter dishes as you type
- 🗂️ **Category Filters** — browse by All, Breakfast, Soups, Pasta, Main Course, Pizza, Burgers
- 🍽️ **Food Cards** — clean cards showing image, name, price, and veg/non-veg indicator
- 🛒 **Slide-in Cart Drawer** — add items and watch the cart panel slide in automatically
- ➕➖ **Quantity Controls** — increase or decrease item quantity directly in the cart
- 🗑️ **Remove Items** — delete unwanted items from the cart with one click
- 💰 **Live Order Summary** — auto-calculated Subtotal, Delivery Fee, Taxes, and Grand Total
- 🔔 **Toast Notifications** — instant feedback for add, remove, and order actions
- 📱 **Fully Responsive** — optimized for mobile, tablet, and desktop
- 🎨 **Smooth Hover Effects** — interactive card and button animations

### 🚧 In Progress / Planned
- 💳 **Payment Gateway Integration** (Razorpay) — checkout currently simulates order placement only
- 🔐 **User Authentication** — login/signup
- 📜 **Order History** — view past orders
- 🗄️ **Backend & Database** — persistent orders instead of local-only state
- 🛠️ **Admin Dashboard** — manage food items

---

## 🛠️ Tech Stack

| Category | Technology |
|---|---|
| Frontend Framework | React 19 |
| Build Tool | Vite |
| Styling | Tailwind CSS |
| Cart State Management | Redux Toolkit |
| Search/Filter State | Context API |
| Notifications | react-toastify |
| Icons | react-icons |

---

## 📦 Getting Started

### Prerequisites

Make sure you have **Node.js** (v18 or higher) installed on your machine.

### Installation & Setup

```bash
# 1. Clone the repository
git clone https://github.com/YOUR_USERNAME/food-delivery-website.git

# 2. Navigate into the project folder
cd food-delivery-website

# 3. Install dependencies
npm install

# 4. Start the development server
npm run dev
```

The app will be running locally at:

http://localhost:5173


### Build for Production

```bash
npm run build
```

---

## 📁 Project Structure

food-delivery-website/
├── public/
├── src/
│ ├── assets/ # Food images
│ ├── components/
│ │ ├── Nav.jsx # Header with search & cart icon
│ │ ├── Card.jsx # Individual food item card
│ │ └── OrderPanel.jsx # Slide-in cart drawer
│ ├── contacts/
│ │ └── UserContext.jsx # Search & category filter state
│ ├── pages/
│ │ └── Home.jsx # Main landing page
│ ├── redux/
│ │ ├── store.js # Redux store config
│ │ └── cartSlice.js # Cart actions & reducers
│ ├── Category.jsx # Category list & icons
│ ├── food.js # Food items data
│ ├── App.jsx
│ ├── main.jsx
│ └── index.css
├── package.json
└── README.md


---

## 🧠 How It Works

- **Category filtering & search** are managed globally using React's **Context API**, so any component can access and update the current filtered food list.
- **Cart functionality** (add, remove, update quantity, clear) is handled by **Redux Toolkit**, keeping cart state centralized and predictable.
- Clicking **"Add to Dish"** dispatches an action to Redux, shows a toast, and automatically opens the cart drawer.
- The **Order Summary** recalculates Subtotal, Delivery Fee, Taxes, and Total in real time based on cart contents.
- "Place Order" currently clears the cart and shows a success toast — real payment processing is not yet integrated.

---

## 🤝 Contributing

This is a personal learning project, but suggestions and feedback are always welcome! Feel free to open an issue or fork the repo.

---

## 📄 License

This project is open source and free to use for learning purposes.

---


## 👤 Author

**ACER** <!-- Manisha Dekate-->
- GitHub: [@Manishadekate11](https://github.com/Manishadekate11)

---

⭐ If you found this project helpful, consider giving it a star!
