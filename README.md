# 🛒 QuickCart – Modern E-commerce App

QuickCart is a full-stack e-commerce web application built with **Next.js**, **Clerk Authentication**, **MongoDB**, **Cloudinary**, and **Inngest** for event-driven architecture. This app allows users to browse products, manage carts, and place orders with real-time syncing and cloud uploads.


---

## 🚀 Live Demo

👉 [Live Site on Vercel](https://quick-cart-three-opal.vercel.app/)

👉 [GitHub Repository](https://github.com/Aswin432/QuickCart/tree/main)

---

## ⚙️ Tech Stack

- **Next.js 15**
- **React 19**
- **Tailwind CSS**
- **Clerk Auth (Next.js SDK)**
- **MongoDB & Mongoose**
- **Cloudinary (Image Uploads)**
- **Inngest (Event Handling)**
- **Axios, React Hot Toast**

---

## 🧠 Features

- 🔐 Seller and User Authentication via Clerk
- 📦 Add / Update / Delete products (Seller)
- 🛍️ Cart with quantity updates and total calculations
- ☁️ Upload product images to Cloudinary
- 📤 Order creation using Inngest event system
- 🧾 Save orders in MongoDB
- ✅ Protected routes with role-based access
- 💬 Toast notifications on all actions

---

## 📁 Folder Structure

├── app/ # Next.js routes │ ├── api/ # API routes (cart, product, order) │ └── components/ # Reusable UI components ├── config/ # DB connection and Inngest setup ├── lib/ # Auth utilities ├── models/ # Mongoose schemas ├── public/ # Static assets ├── styles/ # Global Tailwind styles ├── context/ # App-wide context provider └── .env.local # Environment variables


