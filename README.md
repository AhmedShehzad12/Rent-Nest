<div align="center">

# 🏡 RentNest — Hotel Booking Platform

### A modern full-stack platform to discover, book, and manage hotel & rental properties online.

[![Live Demo](https://img.shields.io/badge/🌐_Live_Demo-Visit_Now-success?style=for-the-badge)](https://rent-nest-7eri.vercel.app/listings)
[![GitHub](https://img.shields.io/badge/GitHub-RentNest-181717?style=for-the-badge&logo=github)](https://github.com/AhmedShehzad12/Rent-Nest)
[![License](https://img.shields.io/badge/License-Educational-blue?style=for-the-badge)](#-license)
[![PRs Welcome](https://img.shields.io/badge/PRs-Welcome-brightgreen?style=for-the-badge)](#-contributing)

</div>

---

## 📖 **About the Project**

**RentNest** is a full-stack web application that allows users to **discover, view, and book hotels** or rental properties online. It provides a clean, user-friendly interface for browsing properties, managing bookings, and listing new properties.

Built using **Node.js + Express + MongoDB** with a **server-side rendered (EJS)** frontend, RentNest offers a seamless experience for both property owners and travelers.

---

## 🚀 **Live Demo**

| Service | URL |
|---------|-----|
| 🌐 **Live Application** | [rent-nest-7eri.vercel.app](https://rent-nest-7eri.vercel.app/listings) |
| 📦 **Source Code** | [github.com/Mahfooj12/RentNest](https://github.com/Mahfooj12/RentNest) |

> 💡 **Note:** The app is hosted on Vercel. The first request may take a few seconds if the server is cold-starting.

---

## ✨ **Features**

<table>
  <tr>
    <td width="50%">

### 👤 User Features
- 🔐 Register & login securely
- 🏨 Browse available properties
- 🔎 Search & filter listings
- 📄 View detailed property info
- 📅 Book properties instantly
- 🏠 Add & manage your own listings

    </td>
    <td width="50%">

### ⚙️ Technical Features
- 🔒 Session-based authentication
- 🗄️ MongoDB database integration
- 📱 Fully responsive design
- ⚡ Fast server-side rendering (EJS)
- 🎨 Bootstrap-powered clean UI
- 🛡️ Input validation & error handling

    </td>
  </tr>
</table>

---

## 🛠️ **Tech Stack**

<table>
  <tr>
    <th>Category</th>
    <th>Technology</th>
  </tr>
  <tr>
    <td>🎨 <b>Frontend</b></td>
    <td>
      <img src="https://img.shields.io/badge/EJS-B4CA65?logo=ejs&logoColor=white" />
      <img src="https://img.shields.io/badge/Bootstrap-7952B3?logo=bootstrap&logoColor=white" />
      <img src="https://img.shields.io/badge/HTML5-E34F26?logo=html5&logoColor=white" />
      <img src="https://img.shields.io/badge/CSS3-1572B6?logo=css3&logoColor=white" />
      <img src="https://img.shields.io/badge/JavaScript-F7DF1E?logo=javascript&logoColor=black" />
    </td>
  </tr>
  <tr>
    <td>🔙 <b>Backend</b></td>
    <td>
      <img src="https://img.shields.io/badge/Node.js-339933?logo=node.js&logoColor=white" />
      <img src="https://img.shields.io/badge/Express.js-000000?logo=express&logoColor=white" />
    </td>
  </tr>
  <tr>
    <td>🗄️ <b>Database</b></td>
    <td>
      <img src="https://img.shields.io/badge/MongoDB-47A248?logo=mongodb&logoColor=white" />
      <img src="https://img.shields.io/badge/Mongoose-880000?logo=mongoose&logoColor=white" />
    </td>
  </tr>
  <tr>
    <td>🧰 <b>Tools</b></td>
    <td>
      <img src="https://img.shields.io/badge/Git-F05032?logo=git&logoColor=white" />
      <img src="https://img.shields.io/badge/GitHub-181717?logo=github&logoColor=white" />
      <img src="https://img.shields.io/badge/npm-CB3837?logo=npm&logoColor=white" />
      <img src="https://img.shields.io/badge/Nodemon-76D04B?logo=nodemon&logoColor=white" />
    </td>
  </tr>
  <tr>
    <td>☁️ <b>Deployment</b></td>
    <td>
      <img src="https://img.shields.io/badge/Vercel-000000?logo=vercel&logoColor=white" />
      <img src="https://img.shields.io/badge/MongoDB_Atlas-47A248?logo=mongodb&logoColor=white" />
    </td>
  </tr>
</table>

---

## 📂 **Project Structure**

```text
RentNest/
│
├── public/                    # Static assets
│   ├── css/                   # Stylesheets
│   ├── js/                    # Client-side scripts
│   └── images/                # Image assets
│
├── views/                     # EJS templates
│   ├── layouts/               # Boilerplate layouts
│   ├── listings/              # Property listing pages
│   ├── users/                 # Auth pages
│   └── partials/              # Reusable components (navbar, footer)
│
├── models/                    # Mongoose schemas
│   ├── user.js                # User model
│   ├── listing.js             # Property/listing model
│   └── ...
│
├── routes/                    # Express routes
│   ├── listings.js            # Listing routes
│   ├── users.js               # Auth routes
│   └── ...
│
├── controllers/               # Business logic
│   └── ...
│
├── utils/                     # Utility functions
│   └── ...
│
├── app.js                     # Main Express app
├── package.json
├── package-lock.json
├── .env                       # Environment variables (not committed)
├── .gitignore
└── README.md
```

---

## ⚙️ **Getting Started**

### **Prerequisites**

Make sure you have the following installed:

- ![Node.js](https://img.shields.io/badge/Node.js-v18+-339933?logo=node.js&logoColor=white)
- ![npm](https://img.shields.io/badge/npm-latest-CB3837?logo=npm&logoColor=white)
- ![MongoDB](https://img.shields.io/badge/MongoDB-Atlas_Account-47A248?logo=mongodb&logoColor=white)
- ![Git](https://img.shields.io/badge/Git-latest-F05032?logo=git&logoColor=white)

### **1️⃣ Clone the Repository**

```bash
git clone https://github.com/Mahfooj12/RentNest.git
cd RentNest
```

### **2️⃣ Install Dependencies**

```bash
npm install
```

### **3️⃣ Configure Environment Variables**

Create a `.env` file in the root directory:

```env
MONGO_URL=your_mongodb_connection_string
SESSION_SECRET=your_session_secret
PORT=3000
```

> ⚠️ **Important:** Never commit the `.env` file to GitHub. Make sure it's listed in `.gitignore`.

### **4️⃣ Run the Application**

**Development mode (with Nodemon):**

```bash
npx nodemon app.js
```

**Or production mode:**

```bash
npm start
```

The app will be running at:

```
http://localhost:3000
```

---

## 🔐 **Environment Variables**

Your `.env` file should contain:

| Variable | Description |
|----------|-------------|
| `MONGO_URL` | MongoDB connection string (local or Atlas) |
| `SESSION_SECRET` | Secret key for session management |
| `PORT` | Server port (default: 3000) |

**Your `.gitignore` must include:**

```text
node_modules/
.env
```

---

## 📸 **Screenshots**

<div align="center">

### 🏠 Home Page
<img src="./screenshots/home.png" alt="Home Page" width="800"/>

### 🏨 Property Detail Page
<img src="./screenshots/property.png" alt="Property Page" width="800"/>

### 🔐 Login Page
<img src="./screenshots/login.png" alt="Login Page" width="800"/>

</div>

> 💡 **Tip:** Add your screenshots in a `screenshots/` folder at the root of the project.

---

## 🌟 **Future Improvements**

- 💳 **Online Payment Integration** — Stripe/Razorpay for booking payments
- ⭐ **Ratings & Reviews** — Let users rate properties and leave reviews
- 🔔 **Booking Notifications** — Email/SMS alerts for confirmed bookings
- 🗺️ **Map Integration** — Show property locations on interactive maps
- ❤️ **Wishlist** — Save favorite properties for later
- 📊 **Admin Dashboard** — Analytics, booking management, user insights
- 📧 **Email Confirmation** — Automated booking confirmation emails
- 📱 **Mobile App** — Native iOS/Android version
- 🌐 **Multi-language Support** — i18n for global reach
- 🔍 **Advanced Filters** — Price range, amenities, ratings

---

## 🤝 **Contributing**

Contributions are welcome! Here's how you can help:

1. Fork the repository
2. Create a feature branch (`git checkout -b feature/AmazingFeature`)
3. Commit your changes (`git commit -m 'Add some AmazingFeature'`)
4. Push to the branch (`git push origin feature/AmazingFeature`)
5. Open a Pull Request

---

## 📄 **License**

This project is created for **educational and portfolio purposes**. Feel free to use it as a learning reference.

---

## 👨‍💻 **Author**

<div align="center">

**Ahmed Shehzad**

🎓 Computer Science & Engineering (Artificial Intelligence)

[![GitHub](https://img.shields.io/badge/GitHub-Mahfooj12-181717?style=for-the-badge&logo=github)](https://github.com/AhmedShehzad12)
[![LinkedIn](https://img.shields.io/badge/LinkedIn-Connect-0A66C2?style=for-the-badge&logo=linkedin)](https://www.linkedin.com/in/ahmed-shehzad-2a8b78219/)

</div>

---

<div align="center">

### ⭐ **If you like this project, please give it a star!** ⭐

Made with ❤️ using Node.js, Express & MongoDB

<img src="https://capsule-render.vercel.app/api?type=waving&color=0A66C2&height=100&section=footer" width="100%"/>

</div>
