
# 📈 Stoxy

**Stoxy** is a sleek and responsive full-stack web application that includes an admin page ai based and a user page where user will be able to add to cart product and order it.

---

## 🚀 Features

- 🔍 **Search & View**: Instantly search for stocks and view real-time data.
- 📊 **Charts & Visualization**: Interactive candlestick charts and line graphs using financial APIs.
- 🧠 **AI based admin dashboard** : because of the computer based data entry there will be no manual data entry required at the stores 
- 📁 **Watchlist Management**: Add products to your personal watchlist.
- 📱 **Responsive Design**: Works smoothly on all devices.
- 📱 **admin panel**: monitors every user what are the items they have in cart ,order canceled notification ,dispatch button to make the user notify there order is dispatched 

---

## 🛠️ Tech Stack

**Frontend:**
- NEXT.js (with Tailwind CSS)
- Charting Library (e.g., Recharts / Chart.js / ApexCharts)
- app router
- media pipe for object detection

**Backend:**
- Node.js
- NEXT js
-API routes integration (NEXT js)
- MongoDB (Mongoose) for cloud data

**Auth:**
- JWT-based authentication (NEXT-auth/auth.js)
- Login/Register with secure password hashing

---

## ⚙️ Installation

1. **Clone the repository**
```bash
git clone https://github.com/yourusername/stoxy.git
cd stoxy
```

3. **Set up environment variables**

Create a `.env` file in the `/server` directory:
```env
MONGO_URI=your_mongodb_connection_string
JWT_SECRET=your_jwt_secret
```

4. **Run the app**
```bash
# In /server
npm run build

# In /client
npm run dev
```

The app will be running at `http://localhost:3000`.

---

## 📷 Screenshots

---

## 🧪 Future Improvements
- order tracking for user
- More advanced AI-based predictive insights
- Mobile app (React Native or Kivy-based)

---

## 🙌 Contributing

Pull requests are welcome. For major changes, please open an issue first to discuss what you would like to change.

---
