# 🗺️ Mapbox Location Explorer

An interactive location search application built with **Next.js, React, TypeScript, and Mapbox**.

Search for places, addresses, landmarks, and points of interest, then explore the selected location directly on an interactive map.

## ✨ Features

- 🔎 Search places, addresses, and landmarks
- 📍 Interactive Mapbox map
- 📌 Automatically place a marker on the selected location
- 🧭 Automatically move the map to the selected location
- 🌎 Display the complete selected address
- 📐 Display latitude and longitude
- ⚡ Fast client-side location search
- 📱 Responsive UI
- 🔐 Environment-based Mapbox access token
- ⌨️ Keyboard-friendly search experience

## 🖥️ Preview

![Mapbox Location Explorer](./public/preview.png)

## 🚀 Tech Stack

- Next.js
- React
- TypeScript
- Mapbox Search JS
- Mapbox GL JS
- Tailwind CSS

## 🧩 How It Works

```text
User enters a location
        ↓
Mapbox Search JS
        ↓
Location suggestions
        ↓
User selects a place
        ↓
Selected address + coordinates
        ↓
Mapbox GL JS
        ↓
Map moves to location
        ↓
Marker is displayed
