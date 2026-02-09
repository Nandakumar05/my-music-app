# 🎵 CloudTunes – Full Stack Music Streaming App

CloudTunes is a **Spotify-like music streaming web application** built using **React.js** and **Spring Boot**.  
Users can upload songs, browse music, and stream audio seamlessly from the cloud across devices.

---

## 🚀 Features

- 🎧 Upload and stream music online
- ☁️ Cloud-based audio storage (Cloudinary)
- 📂 Song management with MySQL database
- 🔍 Browse and play songs instantly
- 📱 Works on desktop & mobile browsers
- 🎨 Spotify-inspired UI design

---

## 🛠️ Tech Stack

### Frontend
- React.js
- Axios
- HTML5, CSS3
- Audio Player API

### Backend
- Java
- Spring Boot
- Spring Data JPA
- REST APIs

### Database
- MySQL

### Cloud Services
- Cloudinary (for audio file storage)

---

## 📁 Project Structure

### Backend (Spring Boot)
Music_App/
├── controller/
│ └── SongController.java
├── model/
│ └── Song.java
├── repository/
│ └── SongRepository.java
├── config/
│ └── SecurityConfig.java
└── MusicAppApplication.java


### Frontend (React)
music-player-ui/
├── src/
│ ├── components/
│ │ ├── Sidebar.js
│ │ ├── Header.js
│ │ ├── SongGrid.js
│ │ └── PlayerBar.js
│ ├── styles/
│ │ └── spotify.css
│ ├── App.js
│ └── index.js


---

## 🔗 API Endpoints

| Method | Endpoint | Description |
|------|---------|------------|
| POST | `/api/songs/upload` | Upload song |
| GET | `/api/songs` | Fetch all songs |
| GET | `/api/songs/play/{id}` | Play song |

---

## ▶️ How to Run Locally

### Backend
1. Open project in **Spring Tool Suite / IntelliJ**
2. Configure MySQL database
3. Add Cloudinary credentials
4. Run:
```bash
mvn spring-boot:run

backend rub at
http://localhost:9090
