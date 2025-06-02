
# 📈 Stoxy

**Stoxy** is a sleek and responsive full-stack web application that provides real-time stock market insights, analytics, and visualizations. Built with a focus on performance and clean UI, Stoxy is perfect for tracking stock trends, comparing assets, and monitoring your favorites.

---

## 🚀 Features

- 🔍 **Search & View**: Instantly search for stocks and view real-time data.
- 📊 **Charts & Visualization**: Interactive candlestick charts and line graphs using financial APIs.
- 🧠 **AI Trend Analysis** *(optional)*: Get intelligent insights on trends (coming soon).
- 📁 **Watchlist Management**: Add stocks to your personal watchlist.
- 🌙 **Dark Mode**: Toggle-friendly light/dark UI for comfortable viewing.
- 📱 **Responsive Design**: Works smoothly on all devices.

---

## 🛠️ Tech Stack

**Frontend:**
- NEXT.js (with Tailwind CSS)
- Charting Library (e.g., Recharts / Chart.js / ApexCharts)
- app router

**Backend:**
- Node.js
- NEXT js
-API routes integration (NEXT js)
- MongoDB (Mongoose) for watchlist/user data

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

- add object detection based data entry
- order tracking for user
- More advanced AI-based predictive insights
- Mobile app (React Native or Kivy-based)

---

## 🙌 Contributing

Pull requests are welcome. For major changes, please open an issue first to discuss what you would like to change.

---
