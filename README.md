# Mettalica-streaming
The platform will allow users to stream music, create personalized playlists, and follow their favorite artists. Administrators will oversee user accounts, music content, and system settings.

🎵 Metallica Music Streaming Platform

A simple Music Streaming Management System built using:

Java (Console Backend)

HTML/CSS/JavaScript (UI/UX Frontend)

The system supports Admin, Artist, and Listener functionalities — including music uploads, playlist creation, and viewing playlist songs.

🚀 Project Features
🔐 User Roles

Admin

Manage Users (Create / Update / Delete)

Approve Uploaded Music

Artist

Upload Music

Interact with Fans

Track Music Performance

Listener

Stream Music

Create Playlist

Add Songs to Playlist

Show Playlist (NEW)

Follow Artists

📁 Project Structure
📦 Metallica-Music-Streaming
 ┣ 📜 MusicPlatform.java        # Fully functional Java backend
 ┣ 📜 index.html                # UI/UX frontend
 ┗ 📜 README.md                 # Project documentation
💻 Backend Overview (Java)

The backend includes:

Music → Stores song info

Playlist → Stores songs added by user

MusicPlatform → Main interactive system

| Option | Feature                 |
| ------ | ----------------------- |
| 5      | Upload Music            |
| 9      | Create Playlist         |
| 10     | Add Music to Playlist   |
| 12     | **Show Playlist (NEW)** |
| 0      | Exit                    |


🖥️ Frontend Overview (HTML/CSS/JS)

The UI includes:

Dropdown menu to choose options

Cards for each operation

Inputs and buttons for user actions

Highlighted sections that match options

Clean Metallica-styled theme

The UI simulates backend navigation and can be extended to real API integration.

🔗 Connecting Backend & Frontend

Currently the backend runs via Java console
and frontend runs in a browser as a visual representation of the same features.

You can later extend this to:
✔ Java Servlets
✔ Spring Boot APIs
✔ Full-stack integration

▶️ How to Run
1. Run Backend (Java)
2. javac MusicPlatform.java
java MusicPlatform


🛠️ Technologies Used
| Area       | Tools                        |
| ---------- | ---------------------------- |
| Backend    | Java, OOP, Console I/O       |
| Frontend   | HTML, CSS, JavaScript        |
| UI Styling | Custom CSS (Metallica Theme) |

📌 Future Improvements

Connect UI with backend using REST API

Add login system

Add music player functionality

Add database support (MySQL / MongoDB)

Add artist dashboards
