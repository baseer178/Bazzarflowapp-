# BazaarFlow - Modern E-Commerce Store & Real-Time Seller Hub

A high-performance, mobile-first single and multi-vendor shop application built with **React 19**, **Vite**, and **Tailwind CSS**. Features a frictionless 30-second checkout flow for buyers and a real-time order dispatch & inventory control panel for sellers.

---

## 🌟 Key Features

### 🛒 Buyer Storefront
- **Instant Product Catalog:** Fast filtering across categories with live instant search.
- **30-Second Express Checkout:** Click "Order Now" to open a streamlined checkout modal without tedious account registration.
- **Nationwide Delivery Fields:** Name, phone/WhatsApp number, delivery city, and complete street address.
- **Payment Options:** Cash on Delivery (COD) and Online Bank Transfer.
- **Shopping Bag:** Slide-out drawer with quantity adjustments and multi-item checkout.

### 📦 Seller Command Hub
- **Live Incoming Orders Feed:** Real-time push alert toasts when new orders arrive.
- **Delivery Dispatch Manager:** 1-click **"Copy Dispatch Label"** for couriers (TCS, Leopards, Trax, DHL) and direct **WhatsApp chat links** with customers.
- **Status Pipeline:** Seamlessly update order lifecycle (`Pending` ➔ `Confirmed` ➔ `Shipped` ➔ `Delivered` ➔ `Cancelled`).
- **Product Inventory Management:** Add, edit, or delete products with price, stock count, and stock status indicators (`In Stock`, `Low Stock`, `Out of Stock`).
- **Analytics KPIs:** Gross revenue, pending shipments, delivered orders, and active catalog count.

---

## 🚀 Quick Start Guide

### 1. Clone the repository
```bash
git clone https://github.com/your-username/bazaarflow-shop.git
cd bazaarflow-shop
```

### 2. Install dependencies
```bash
npm install
```

### 3. Start development server
```bash
npm run dev
```
Open `http://localhost:3000` or `http://localhost:5173` in your browser.

### 4. Build for Production
```bash
npm run build
```
The production bundle will be generated in the `dist/` directory.

---

## 🌐 Deploy to Vercel or Netlify

### Deploy on Vercel
1. Push your code to GitHub:
   ```bash
   git init
   git add .
   git commit -m "Initial commit of BazaarFlow shop"
   git branch -M main
   git remote add origin https://github.com/<your-username>/bazaarflow-shop.git
   git push -u origin main
   ```
2. Go to [Vercel](https://vercel.com) and click **"Add New Project"**.
3. Import your GitHub repository.
4. Framework Preset will be automatically detected as **Vite**.
5. Click **"Deploy"**. Your shop will be live in ~45 seconds!

### Deploy on Netlify
1. Connect your repository on [Netlify](https://netlify.com).
2. Set Build command: `npm run build`
3. Set Publish directory: `dist`
4. Click **"Deploy Site"**.

---

## 📄 License
MIT License. Free to use and customize for personal or commercial projects.
