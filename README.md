# 🎬 Movie Review  

**Movie Review** is a **Full Stack Movie Discovery & Review Platform** built using **React**, **Spring Boot**, and **MongoDB**.  
It allows users to explore movies, watch trailers, post reviews, and maintain personal watchlists — all with a sleek and responsive interface powered by **Tailwind CSS**.

--

## 🚀 Features

- 🎞️ **Watch Trailers** — Stream movie trailers with smooth playback  
- 🗒️ **User Reviews** — Read, write, and manage reviews easily  
- 📋 **Watchlist** — Save your favorite movies for later  
- 📱 **Fully Responsive** — Works beautifully on mobile, tablet, and desktop  
- 🎨 **Tailwind CSS Styling** — Clean UI with custom animations  
- ⚡ **Fast & Seamless Experience** — Optimized loading and state handling  

---

## 🧠 Tech Stack

| Layer | Technologies |
|:------|:--------------|
| **Frontend** | React, React Router DOM, Tailwind CSS, MUI, Bootstrap |
| **Backend** | Spring Boot (Java) |
| **Database** | MongoDB (MongoDB Atlas) |
| **Icons** | FontAwesome, MUI Icons |
| **HTTP Client** | Axios |

---

## 📁 Folder Structure

```
/frontend/src
|-- components
|   |-- Hero
|   |-- Trailer
|   |-- Reviews
|   |-- ReviewForm
|   |-- NotFound
|   |-- Header
|-- App.js
|-- index.js
|-- index.css
|-- tailwind.config.js
|-- postcss.config.js
|-- api
|   |-- axios.js
/backend
|-- src/main/java/com/moviereview/api
|   |-- controllers
|   |-- services
|   |-- models
|   |-- repositories
|-- src/main/resources/application.properties
|-- pom.xml
|-- sample-data
```

---

## ⚙️ Setup & Installation

### 🖥️ Frontend Setup

1. **Clone this repository**
   ```bash
   git clone https://github.com/<your-username>/movie-review.git
   cd movie-review/frontend
   ```

2. **Install dependencies**
   ```bash
   npm install
   ```

3. **Start the app**
   ```bash
   npm start
   ```

---

### ⚙️ Backend Setup

1. Move to backend folder:
   ```bash
   cd ../backend
   ```

2. Start the Spring Boot server:
   ```bash
   ./mvnw spring-boot:run
   ```



