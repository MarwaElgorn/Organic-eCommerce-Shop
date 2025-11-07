
# 🛍️ Shopery

**Shopery** is a modern e-commerce web application built with **React (Vite)** for the frontend and **JSON Server** as a mock REST API to simulate backend operations.  
It delivers a smooth, responsive, and engaging shopping experience with dynamic product management and a clean UI.

---

## 🚀 Features
- 🛒 Browse and filter products  
- ➕ Add and remove items from the shopping cart  
- 📱 Responsive and mobile-friendly design  
- ✅ Form validation using **Formik** and **Yup**  
- 🔄 API communication via **Axios**  
- 💾 Local **JSON Server** for backend simulation  

---

## 🧠 Tech Stack
**Frontend:** React, Vite, React Router DOM, Axios, Bootstrap, React Icons  
**Backend:** JSON Server (Fake REST API)  
**Styling:** Bootstrap 5 + Custom CSS  
**Validation:** Formik & Yup  

---

## ⚙️ Installation & Setup

### 1️⃣ Clone the repository
```bash
git clone https://github.com/MarwaElgorn/shopery.git
cd shopery
````

### 2️⃣ Install dependencies

```bash
npm install
```

### 3️⃣ Run the backend (JSON Server)

```bash
npm run server
```

> The server will start on **[http://localhost:5000](http://localhost:5000)**

### 4️⃣ Run the frontend (React + Vite)

```bash
npm run dev
```

> Open the app on **[http://localhost:5173](http://localhost:5173)**

---

## 🌐 Deployment Guide

### 🔹 Backend (JSON Server)

To host your mock API:

1. Go to [Render](https://render.com)
2. Create a **New Web Service**
3. Connect your GitHub repository
4. Set:

   * **Build Command:** `npm install`
   * **Start Command:** `npm run server`
5. Deploy — Render will give you a live API endpoint like:

   ```
   https://shopery-api.onrender.com/products
   ```

---

### 🔹 Frontend (React + Vite)

To host your React app:

1. In your frontend code, replace all local API URLs (`http://localhost:5000`) with the Render API link.
2. Build the app:

   ```bash
   npm run build
   ```
3. Deploy the `dist` folder using one of the following:

   * [Netlify](https://www.netlify.com)
   * [Vercel](https://vercel.com)

---

## 📁 Project Structure

```
shopery/
│
├── src/
│   ├── components/
│   ├── pages/
│   ├── context/
│   ├── assets/
│   └── App.jsx
│
├── server/
│   └── db.json
│
├── package.json
└── vite.config.js
```

---

## 📸 Preview

Here’s a quick look at **Shopery** 👇

![Shopery Screenshot](./src/assets/01_Homepage.png)

---

## 🧑‍💻 Author

**Marwa Elgorn**
Front-End Developer passionate about creating dynamic, user-friendly, and responsive web applications.

📫 **Connect with me:**

* [GitHub](https://github.com/MarwaElgorn)
* [LinkedIn](https://www.linkedin.com/in/marwa-elgorn/)

---

## 🪄 License

This project is open-source and available under the [MIT License](LICENSE).

```

---

