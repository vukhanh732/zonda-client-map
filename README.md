# 🗺️ Client Sales Map App

An interactive mapping tool for visualizing client locations, healthcare sectors, and nearby services using the Google Maps JavaScript and Places APIs.

## 🚀 Features

- 🔍 **Location-Based Search** – Users can input a location to center the map and search within a radius.
- 📍 **Dynamic Markers** – Automatically detects and displays hospitals, doctors, and aged care centers using Google Places API.
- 🧭 **Client Data Integration** – Loads custom client data from a JSON file and plots them on the map.
- 🎯 **Sector Filtering** – Toggle visibility for sectors like hospitals, doctors, aged care, or client locations.
- 📏 **Distance-Based Filtering** – Uses the Haversine formula to filter client markers within a 5km radius of the searched point.
- 🛣️ **Directions & Details** – Click on a marker to view detailed info and get a direct link for Google Maps navigation.
- 🌐 **External Search Shortcut** – One-click button to search for nearby health services on Google.

## 🧰 Technologies Used

- **Google Maps JavaScript API**
- **Google Places API**
- **JavaScript (Vanilla)**
- **HTML/CSS**
- **Custom JSON data integration**

## 📦 How It Works

1. User searches for a location using the search bar.
2. A circular region is drawn on the map, and nearby health-related services are fetched using Google Places API.
3. Client data from a local `company_data.json` file is loaded and filtered by proximity.
4. Users can filter markers by category, and click on any marker to get business details and navigation directions.


