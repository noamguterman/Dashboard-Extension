# 📊 Personal Dashboard – Chrome Extension  

A **Chrome Extension** that displays the **current time, weather, and Dogecoin performance**, using multiple APIs and **async JavaScript** for real-time updates.  

![Personal Dashboard](https://raw.githubusercontent.com/noamguterman/Dashboard-Extension/refs/heads/main/dashboard-preview.png)  

## 🚀 Live Demo  
🔗 [Try Personal Dashboard](https://noamguterman.github.io/Dashboard-Extension/)  

---

## 📝 Features  
✅ **Real-time time display** – Updates every second to show the current time.  
✅ **Dynamic background images** – Fetches a new nature-themed background from Unsplash.  
✅ **Live Dogecoin tracking** – Displays current price, daily high, and daily low from CoinGecko.  
✅ **Weather updates** – Uses OpenWeather API to fetch real-time weather based on the user's location.  
✅ **Chrome new tab override** – Replaces the default new tab page with the Personal Dashboard.  

---

## 🛠️ Tech Stack  
- **Frontend:** HTML, CSS, Vanilla JavaScript  
- **APIs:** Unsplash, CoinGecko, OpenWeather  
- **Chrome Extension:** Manifest v3  

---

## 🎯 How It Works  
1️⃣ The **current time** is displayed and updates every second.  
2️⃣ The **background image** updates dynamically using the Unsplash API.  
3️⃣ **Dogecoin performance** is fetched from CoinGecko and displayed in real time.  
4️⃣ The **weather forecast** is retrieved based on the user's geolocation.  
5️⃣ The extension **overrides the new tab page**, replacing it with this dashboard.  

---

## 🏠 Project Structure  
```
/
  ├── index.html            # Main extension page
  ├── index.css             # Styling for UI elements
  ├── index.js              # Main JavaScript logic
  ├── manifest.json         # Chrome Extension manifest file
  ├── images/               # Static assets like icons
```

---

## 🛠️ APIs & Data Sources  
- **Unsplash API** – Fetches random nature-themed images for the background.  
- **CoinGecko API** – Retrieves Dogecoin market data (current price, high/low).  
- **OpenWeather API** – Provides real-time weather updates based on location.  

---

## 🌟 Why This Project?  
This project showcases **Chrome Extension development** and **real-time API integration**. It demonstrates:  
✔️ **Asynchronous JavaScript** (fetching API data dynamically)  
✔️ **Real-time UI updates** (auto-refreshing time and data)  
✔️ **Geolocation API usage** (fetching user location for weather updates)  
✔️ **Manifest v3 for Chrome Extensions**  

---

## 🐝 License  
This project is for personal use and is not licensed for redistribution or modification.  

---
