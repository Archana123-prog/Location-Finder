
# 📍 Location Finder (Pin Code Based)

A simple web application that finds the **location details of an Indian PIN code** and displays it on an interactive map.

## 🚀 Features

* 🔢 Enter a **6-digit PIN code**
* 📍 Fetches **location details (address)**
* 🗺️ Displays location on **interactive map (Leaflet)**
* ⚡ Real-time input detection (event listener)
* ❌ Error handling for invalid or not found PIN codes

## 🛠️ Tech Stack

* HTML
* CSS
* JavaScript
* Leaflet.js (for maps)
* OpenStreetMap (Nominatim API)

## ⚙️ How It Works

1. User enters a PIN code
2. Input event listener checks:

   * Must be 6 digits
   * Must be numeric
3. If valid → API request is sent
4. Location data (lat, lon, address) is fetched
5. Map + marker is displayed

## 📂 Project Structure

```
📁 location-finder
 ├── index.html
 ├── style.css
 ├── script.js
```

## ▶️ Run Locally

1. Download or clone the repo
2. Open `index.html` in your browser

## 🌐 API Used

* OpenStreetMap Nominatim API
* No API key required ✅

## 📌 Example

Input:
```
203207
```
<img width="1919" height="919" alt="Screenshot 2026-04-09 230853" src="https://github.com/user-attachments/assets/e6d9c0e5-d35d-4d72-b264-517ba65981d9" />

Output:

* Dadri, Gautam Buddha Nagar, Uttar Pradesh, India
* Map with marker 📍

<img width="1915" height="924" alt="Screenshot 2026-04-09 231149" src="https://github.com/user-attachments/assets/fdd712d7-75d9-4ae4-b396-d36252c3e351" />

## Zoom 🔍in & 🌍out

<img width="809" height="675" alt="Screenshot 2026-04-09 231330" src="https://github.com/user-attachments/assets/ed839071-1584-461e-b102-5dc683662f07" />

## 🚧 Future Improvements

* 🌍 Support for global PIN codes
* 📱 Mobile UI optimization
* 🔍 Search history
* 📌 Multiple results support

## 👩‍💻 Author

**Archana Kumari**
