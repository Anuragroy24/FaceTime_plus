#  FaceTime+
Project Link:- https://facetime247.vercel.app/create
## 🚀 Project Overview
The **FaceTime+** is a high-performance and scalable solution built using the **MERN stack**. It allows users to schedule and host high-quality group video calls, share their screens, and chat in real-time. With a focus on performance optimization and scalability, this app is designed to handle large-scale video conferencing.

### 🔥 Key Features:
- 🎥 **High-Quality Video Calls**: Supports multiple participants with group video call functionality.
- 🗓️ **Meeting Scheduling**: Create, schedule, and join meetings seamlessly.
- 🖥️ **Screen Sharing**: Share your screen with participants during the call.
- 💬 **Real-Time Chat**: Integrated chat for messaging during the conference.
- 🛠️ **Admin Dashboard**: Manage meetings, users, and other administrative tasks.
- ⚡ **Scalability**: Optimized to handle large groups of users.

## 🛠 Tech Stack

| Technology  | Description                               |
|-------------|-------------------------------------------|
| MERN        | MongoDB, Express, React, Node             |
| WebRTC      | Real-time video and audio                 |
| Socket.IO   | Real-time, bidirectional communication    |
| JWT         | JSON Web Tokens for authentication        |

## 📷 Preview
_A sneak peek of the app's interface._

## 🚩 Project Structure
The project is divided into two main folders:

- **Frontend (React.js)**  
  Responsible for the UI/UX of the video conferencing interface. 
  Connects to WebRTC for video streaming and Socket.IO for real-time communication.
  
- **Backend (Node.js with Express)**  
  Handles API requests, authentication, meeting scheduling, and admin tasks. 
  Uses MongoDB for data storage and JWT for secure user authentication.

```bash
/FaceTime+
├── client                    # React frontend
│   ├── public
│   └── src
│       ├── components
│       └── utils
├── server                    # Node backend
│   ├── controllers
│   ├── models
│   └── routes
└── README.md
```

 🚀 Getting Started

1. Clone the Repository
```bash
git clone https://github.com/Anuragroy24/FaceTime_plus.git
cd FaceTime_plus
```

2. Install Dependencies
Backend:
```bash
cd server
npm install
```
Frontend:
```bash
cd client
npm install
```

3. Set Up Environment Variables

 Create a .env file in the server directory with the following values:
 ```bash
MONGO_URI=your_mongodb_connection_string
JWT_SECRET=your_jwt_secret
PORT=5000
```
4. Run the App
Backend:
```bash
npm run dev
```
Frontend:
```bash
npm start
```
5. Open the Application
Visit: http://localhost:3000 to start using the FaceTime_plus.

🎯 Features In Detail

🎥 Group Video Calls
Connect multiple users in high-quality video calls.
Powered by WebRTC for real-time media sharing.

🖥️ Screen Sharing
Share your screen with all participants, making it ideal for presentations, demos, and more.

💬 Real-Time Chat
Integrated chat feature with Socket.IO to exchange messages without interrupting the meeting.

🗓️ Meeting Scheduling
Create and schedule meetings with unique meeting IDs for seamless joining.

🛠️ Admin Dashboard
A comprehensive dashboard to manage users, meetings, and configurations.

## 📈 App Statistics

| Stats             | Description                                       |
|-------------------|---------------------------------------------------|
| High Scalability  | Handles hundreds of simultaneous connections       |
| Uptime            | 99.9% uptime with performance optimization         |
| Response Time     | Real-time messaging and near-instant video        |

## Project Structure




Here are some pictures of the web App:

First Image:

Second Image:

Third Image:

