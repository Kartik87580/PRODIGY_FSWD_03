# PRODIGY_FSWD_03 

# 🛍️ Local Store E-commerce Platform (MERN Stack)

A fully functional e-commerce web application developed using the MERN stack. This project allows customers to browse, add to cart, and purchase products from a local store online. Built as part of my Full Stack Developer internship at **Prodigy Infotech**.

---

## 🚀 Features

- 🖼️ Product listing with image, price, and description
- 🛒 Add to Cart & Remove from Cart
- 👤 User Signup/Login with JWT Auth
- 📦 Order placement
- 📱 Fully responsive UI with TailwindCSS + DaisyUI

> ✨ *Optional Features Coming Soon:*  
> Order tracking, reviews, customer support, filters & sorting

---

## 🧱 Tech Stack

**Frontend:** React.js, Axios, React Router DOM, TailwindCSS, DaisyUI  
**Backend:** Node.js, Express.js, MongoDB (via Mongoose)  
**Authentication:** JWT, bcryptjs  
**File Upload (optional):** Multer, Cloudinary  
**State Management:** Context API / Zustand (optional)

---

## 📦 Installation

### 1. Clone the Repository

```bash
git clone https://github.com/Kartik87580/ PRODIGY_FSWD_03.git
cd  PRODIGY_FSWD_03 
````

---

### 2. Backend Setup

```bash
cd backend
npm install
```

Create a `.env` file in the `backend/` folder:

```env
PORT=5000
MONGO_URI=your_mongo_uri
JWT_SECRET=your_secret_key
```

Start the server:

```bash
npm run dev
```

---

### 3. Frontend Setup

```bash
cd ../client
npm install
npm start
```

---

## 🗂️ Folder Structure

```
.
├── backend
│   ├── controllers
│   ├── models
│   ├── routes
│   └── index.js
├── client
│   ├── src
│   │   ├── components
│   │   ├── pages
│   │   └── App.js
```

---



## 👨‍💻 Author

**Kartik Jambucha**
Full Stack Developer Intern @ Prodigy Infotech


---

## 🪪 License

This project is licensed under the **MIT License**.




