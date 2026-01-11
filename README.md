# 🛒 React Shopping Cart — Custom Hook Implementation

This project is a **React Shopping Cart application** built to demonstrate how to manage shared business logic using a **Custom Hook (`useCart`)** instead of lifting state across many components.

It is designed as a **learning + portfolio project** showing clean structure, reusable logic, and real‑world features like persistence and tab sync.

---

## 🚀 Features

* Add products to cart
* Increase / decrease product quantity
* Remove items from cart
* Auto calculate total price
* Persist cart using LocalStorage
* Sync cart across multiple browser tabs
* Business logic separated using Custom Hook

---

## 🧠 What This Project Demonstrates

* Creating and using **Custom Hooks**
* State management with `useState`
* Side effects with `useEffect`
* Performance optimization using `useMemo`
* Functional state updates
* Separation of UI and logic (clean architecture)

---

## 📁 Project Structure

```
src/
 ┣ components/
 ┃ ┣ Card.jsx
 ┃ ┣ CartItem.jsx
 ┃ ┗ ProductCard.jsx
 ┣ hooks/
 ┃ ┗ useCart.js
 ┣ data/
 ┃ ┗ products.js
 ┣ App.jsx
 ┗ main.jsx
```

---

## 🪝 Custom Hook — useCart

The `useCart` hook is responsible for all cart behavior:

* Initialize cart from LocalStorage
* Save cart to LocalStorage on change
* Sync cart across browser tabs using `storage` event
* Add product to cart
* Remove product from cart
* Update quantity
* Calculate total using `useMemo`

This keeps components simple and focused only on rendering UI.

---

## ⚙️ Tech Stack

* React (Vite)
* JavaScript (ES6+)
* React Icons
* Browser LocalStorage API

---

## ▶️ How to Run Locally

```bash
# clone repo

git clone https://github.com/abhishek-kr01/react-shopping-cart-custom-hook.git
cd react-shopping-cart-custom-hook

# install dependencies
npm install

# start dev server
npm run dev
```

Then open in browser:

```
http://localhost:5173
```

---

## 📌 Possible Future Improvements

* Context API version of cart
* Redux Toolkit implementation
* Product images and UI enhancement
* Backend API integration
* TypeScript conversion
* Unit testing with Vitest / Jest

---

## 👨‍💻 Author

**Abhishek Kumar**

---

## ⭐ Support

If you find this useful:

* Star the repository
* Fork and experiment
* Try building your own version using Context or Redux
