# 🌍 GeoHunt – A Modern Geocaching Platform

**GeoHunt** is a geocaching web application built with **Flask** and **MongoDB Atlas**. It enables users to discover, create, and log geocache locations using an interactive map. Whether you're hunting for hidden treasures or placing your own, GeoHunt brings the adventure online.

🔗 **Live App**: [https://geocaching-three.vercel.app/](https://geocaching-three.vercel.app/)

---

## 🚀 Features

- 🗺️ **Map-Based Interface**: View and explore caches using an interactive map.
- 📍 **Create & Log Geocaches**: Add new caches with descriptions, hints, and coordinates.
- 🔐 **OAuth Authentication**: Secure login and signup via third-party providers.
- 👤 **User Dashboard**: Track your hidden and found caches.
- ☁️ **Cloud Database**: All data is stored securely in **MongoDB Atlas**.
- ⚡ **Lightweight & Fast**: Built with Flask for simplicity and performance.

---

## 🛠️ Tech Stack

- **Backend**: Flask (Python)  
- **Database**: MongoDB Atlas  
- **Frontend**: HTML/CSS + JavaScript (map integration)  
- **Authentication**: OAuth (via Flask libraries)  
- **Deployment**: Vercel (frontend)

---

## 💻 Setup Instructions (Windows)

```bash
# Create virtual environment
py -m venv env

# Activate virtual environment
.\env\Scripts\activate

# Install dependencies
py -m pip install -r requirements.txt

# Run the app
flask run
