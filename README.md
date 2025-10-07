# url_shortener# 🔗 URL Shortener

A simple **URL Shortener** built using **Node.js**, **HTML**, and **CSS**.  
This project allows users to shorten long URLs into easy-to-share short codes and stores them locally in a `links.json` file.

---

## 🚀 Features

- Shorten any valid URL with a custom or random short code  
- Persistent storage using JSON file (`data/links.json`)  
- Automatically creates data directory and JSON file if missing  
- Simple front-end form to submit and display shortened URLs  
- Redirects to the original URL when visiting the short link  

---

## 🧠 Tech Stack

- **Node.js** (HTTP server, File System)
- **HTML / CSS / JavaScript** (Frontend UI)
- **fs/promises** for async file handling
- **crypto** for generating random short codes

---

## 📁 Project Structure

URL-Shortener/
│
├── app.js # Main Node.js server file
├── data/
│ └── links.json # Stores shortCode → URL mappings
├── public/
│ ├── index.html # Frontend HTML
│ └── style.css # Frontend styles
└── README.md