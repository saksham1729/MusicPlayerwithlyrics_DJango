# 🎵 Django Music Player with Lyrics

This is a **web-based music player** built using **Django**, which allows users to play songs, view song metadata, and synchronize lyrics with the audio. The project combines modern frontend design with Django’s powerful backend framework to deliver a clean and functional user experience.

---

## 🚀 Features

- 🎧 Play audio files directly from the browser
- 🖼️ Display song metadata: artist name, song title, album art
- 📃 Dynamic, time-synced lyrics display (if enabled)
- 🔄 Pagination-based song browsing (one song per page)
- 📂 Media files served from Django project (or remote URLs)
- 🎨 Clean and responsive user interface

---

## 🛠️ Tech Stack

- **Backend**: Django (Python)
- **Frontend**: HTML5, CSS3, JavaScript, Font Awesome
- **Media Player**: [MediaElement.js](https://www.mediaelementjs.com/)
- **Database**: SQLite (default Django DB)
- **Templates**: Django Template Language (DTL)

---

## 📁 Project Structure

musicplayer/
│
├── App/ # Django app for music handling
│ ├── models.py # Song model with fields for audio, title, artist, lyrics, etc.
│ ├── views.py # View logic for pagination and rendering
│ ├── templates/
│ │ ├── index.html # Main UI template
│ │ └── main.html # Song & lyrics layout
│ └── static/
│ ├── style.css # Custom player styling
│ └── script.js # Lyrics synchronization (optional)
│
├── media/ # Uploaded audio/image files
├── db.sqlite3 # SQLite database
├── manage.py
└── README.md
