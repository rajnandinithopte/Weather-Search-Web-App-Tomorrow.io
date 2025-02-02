# Weather-Search-Web-App-Tomorrow.io

## Created a responsive **web application** for retrieving and displaying weather details using the **Tomorrow.io API**.

---

## 🔹Tech Stack

**Frontend:** Angular, TypeScript, HTML, CSS, Bootstrap  
**Backend:** Node.js, Express, MongoDB (Atlas), Google Cloud Platform (GCP) 

**Libraries & Frameworks:**
- **Angular Material** - UI components
- **Bootstrap 5.3** - Responsive web design
- **HighCharts** - Charting library
- **MongoDB Atlas** - Cloud database integration

---

## 🔹 APIs Used

1. **Tomorrow.io API** - Fetches real-time and forecast weather data.
2. **Google Places Autocomplete API** - Provides search suggestions for cities.
3. **Google Geocoding API** - Converts location names into latitude/longitude.
4. **IPinfo API** - Retrieves user location based on IP.
5. **MongoDB Atlas** - Stores user-favorited locations in a cloud database.
6. **Twitter (X) Share API** - Allows users to share weather updates on X (Twitter).

---

## 🔹Features

### 1. **User Location-Based Weather Search**
   - Automatically fetches weather data based on the **user’s current location**.
   - Uses **IPinfo API** to determine location.

### 2. **Search for Weather Details by City**
   - Implements a **search bar with autocomplete** powered by the Google Places API.
   - Fetches weather data via Tomorrow.io API **through a Node.js backend proxy**.
   - Displays search results dynamically **below the search form**.

### 3. **Weather Details View**
   - **Day View Tab:** Displays daily weather conditions including:
     - Temperature, humidity, wind speed, visibility, pressure.
   - **Daily Temp. Chart Tab:** Graphs the **temperature trends** for the next 15 days.
   - **Meteogram Tab:** Displays **hourly temperature changes** over 5 days using HighCharts.

### 4. **Favorites List (MongoDB Integration)**
   - Allows users to **save cities to a favorites list**.
   - Implements **persistent storage using MongoDB Atlas (cloud database)**.
   - Supports **removing cities from favorites and syncing data with the backend**.

### 5. **Social Media Sharing**
   - Integrates **Twitter (X) sharing**.
   - Generates a **pre-filled tweet** containing weather details.

### 6. **Interactive UI & Responsive Design**
   - Uses **Bootstrap 5.3** for **responsive web design** across devices.
   - Incorporates **Angular Material** for a smooth user experience.
   - Displays **loading spinners** while fetching API data.

### 7. **Backend & Cloud Deployment**
   - Uses a **Node.js backend** deployed on **Google Cloud Platform (GCP)**.
   - Stores user-favorite locations in **MongoDB Atlas** for cross-device sync.
   - Communicates with the backend via **asynchronous HTTP requests**.

## 🔹Live Demo

**Try it here:** https://hw3-rajnandini-thopte-csci571.wl.r.appspot.com/

Click the link above to explore the app in real time. 

### 🔹How to Search for Weather Details (USA Only)
Users can search for weather information within the **United States** using two methods:

1.  **Search by City & State:**  
   - Enter a **Street Address (optional)**, **City**, and **State (USA only)** in the form.  
   - The **City field** includes **autocomplete suggestions** powered by the Google Places API.  
   - Select a city from the dropdown or manually type it in.  
   - Click **Search**, and the app will retrieve weather details for the selected location.

2. **Use Current Location:**  
   - Enable the **"Use My Current Location"** checkbox.  
   - The app will automatically detect your **latitude and longitude** using the **IPinfo API** (limited to USA).  
   - Click **Search**, and the weather information for your **current location** in the **USA** will be displayed.

---
