# 🛒 Simple E-Commerce Cart (Learning Project)

This is a small **JavaScript project** I built while learning **DOM manipulation** and **basic cart functionality**.  
It simulates an e-commerce shopping cart where users can add products, view items in the cart, see the total price, and checkout.

---

## 🚀 Features
- Displays a list of products with name & price
- Add products to the cart
- View cart items dynamically
- Shows total price of all items in the cart
- Empty cart message when no items are added
- Checkout button clears the cart with confirmation

---

## 🛠️ Technologies Used
- **HTML** → structure of the page  
- **CSS** → basic styling (with `hidden` class for toggling)  
- **JavaScript (ES6)** → handles DOM updates and cart logic  

---

## 📂 Project Structure
ecommerce-cart/
│-- index.html # Main HTML file
│-- style.css # Styling (optional)
│-- script.js # JavaScript logic



## 📖 How It Works
1. Products are defined in a JavaScript array with `id`, `name`, and `price`.  
2. Clicking **Add to Cart** adds the selected product into the cart.  
3. The cart dynamically displays items and updates the total price.  
4. If the cart is empty, an "Empty cart" message is shown.  
5. Clicking **Checkout** clears the cart and shows a success alert.  

---

## 🧑‍💻 What I Learned
- How to loop through arrays and dynamically render HTML elements.  
- How to use **event delegation** (click events on product list).  
- How to calculate totals and update the DOM in real time.  
- How to manage state (`cart` array) in a simple project.  

---

## 🔮 Future Improvements
- Add quantity update (increase/decrease items in cart)  
- Allow removing individual items from the cart  
- Persist cart data using **localStorage**  
- Improve design with better CSS or a framework like Tailwind  

---

✨ *This project is part of my JavaScript learning journey. It helped me understand how basic e-commercee carts work under the hood.*