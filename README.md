# ConnectIO 🎥💬  
A Real-Time Video Conferencing Web Application

ConnectIO is a full-stack video conferencing web application built using Node.js and WebRTC technologies. It enables users to securely create or join virtual meeting rooms with real-time video calls, chat, screen sharing, and collaboration features.

---

## 🚀 Features

- 🔐 **Google OAuth Authentication**
  - Secure login using Google accounts via Passport.js

- 🎥 **Real-Time Video Calling**
  - Peer-to-peer video communication using WebRTC (PeerJS)

- 💬 **Live Chat**
  - Real-time messaging powered by Socket.io

- 🖥️ **Screen Sharing**
  - Share your screen during meetings for better collaboration

- 🧑‍🤝‍🧑 **Participant Management**
  - View participants list in a dedicated modal

- 🎨 **Collaborative Whiteboard**
  - Draw and collaborate in real time with color options

- 🔊 **Meeting Controls**
  - Mute/unmute audio
  - Turn video on/off

- 🔗 **Room Management**
  - Unique Room ID generation
  - Copy & share meeting links

- 📧 **Email Invitations**
  - Send meeting invites via Nodemailer

---

## 🛠️ Tech Stack

### Backend
- **Node.js**
- **Express.js**
- **Socket.io**
- **PeerJS (WebRTC)**
- **Passport.js (Google OAuth)**
- **Nodemailer**

### Frontend
- **EJS Templating**
- **Bootstrap 4**
- **Font Awesome**
- **HTML, CSS, JavaScript**

---

## 🧠 Architecture Overview

- Uses **MVC architecture**
- WebRTC handles peer-to-peer video streams
- Socket.io manages real-time events (chat, join/leave, whiteboard sync)
- Google OAuth ensures secure authentication
- Express.js manages routing and server logic

---

## ⚙️ Installation & Setup

### Prerequisites
- Node.js (v16+ recommended)
- Google OAuth credentials
- SMTP credentials for email

### Steps

```bash
# Clone the repository
git clone https://github.com/your-username/connectio.git

# Navigate to project directory
cd connectio

# Install dependencies
npm install

# Start the server
npm start
