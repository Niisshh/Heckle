# 🚀 Heckle — Real-Time Chat & Video Call App

Heckle is a **full-stack real-time chat application** built with **Angular 19**, **ASP.NET Core 9 Web API**, **SignalR**, and **WebRTC**.  
It supports **instant private messaging**, **user presence**, and **peer-to-peer HD video calling** — combining the power of modern web technologies to create a Slack-, Zoom-, or WhatsApp-like experience.

---

## 📚 Table of Contents
- [✨ Features](#-features)
- [🧠 Technologies Used](#-technologies-used)
- [🛠️ Installation](#️-installation)
- [⚙️ Project Setup](#️-project-setup)
  - [Backend (ASP.NET Core)](#backend-aspnet-core)
  - [Frontend (Angular)](#frontend-angular)
- [🔑 Authentication](#-authentication)
- [💬 Real-Time Features](#-real-time-features)
- [🎥 Video Calling (WebRTC)](#-video-calling-webrtc)
- [📦 Deployment](#-deployment)
- [🤝 Contributing](#-contributing)
- [📄 License](#-license)
- [💙 Credits](#-credits)

---

## ✨ Features

✅ **User Authentication (JWT)** — Secure login and registration using ASP.NET Identity  
✅ **Profile Picture Upload** — Upload and display avatars in chat  
✅ **Real-Time Messaging** — Instant message delivery using SignalR  
✅ **Online/Offline Presence** — See which users are active  
✅ **Typing Indicators & Notifications** — Real-time UX enhancements  
✅ **Private Chats** — One-on-one messaging with history  
✅ **Peer-to-Peer Video Calls** — WebRTC-based high-quality video communication  
✅ **Responsive UI** — Built with TailwindCSS and Angular Material  
✅ **PWA Support** — Installable progressive web app  
✅ **Azure Deployment (CI/CD)** — Ready for production hosting  

---

## 🧠 Technologies Used

### Frontend
- Angular 19  
- TailwindCSS  
- Angular Material  
- TypeScript  
- WebRTC  

### Backend
- ASP.NET Core 9 Web API  
- SignalR  
- Entity Framework Core + SQLite  
- ASP.NET Identity  
- JWT Authentication  

### Tools & Services
- Visual Studio Code  
- Postman / Thunder Client  
- Azure CI/CD for Deployment  

---

## 🛠️ Installation

### Prerequisites
Make sure you have the following installed:
- [.NET 9 SDK](https://dotnet.microsoft.com/)
- [Node.js (LTS)](https://nodejs.org/)
- [Angular CLI 19+](https://angular.io/cli)
- [Visual Studio Code](https://code.visualstudio.com/)
- [SQLite](https://www.sqlite.org/)
- [Postman or Thunder Client](https://www.postman.com/)

---

## ⚙️ Project Setup

### Backend (ASP.NET Core)

```bash
cd Heckle.API
dotnet restore
dotnet ef database update
dotnet run
