<img width="1920" height="1022" alt="a1" src="https://github.com/user-attachments/assets/76428fb7-0692-45e6-9c0e-3403208c3bc8" />REAL-TIME-CODE-COLLABORATION-TOOL

COMPANY: CODTECH IT SOLUTIONS
NAME: Sumit Kasbe
INTERN ID: [Your Intern ID]
DOMAIN: MERN Stack Web Development
DURATION: 4 Weeks
MENTOR: Neela Santosh

📌 Project Description

This project is a Real-Time Code Collaboration Tool built using the MERN stack (MongoDB, Express.js, React.js, Node.js) along with Socket.IO for real-time communication.

The main purpose of this project is to allow multiple users to collaborate on code simultaneously in a virtual room. Each change made by one user is reflected instantly on all connected clients, providing a smooth and interactive collaborative coding experience.

In today’s world, platforms like Google Docs, Replit Multiplayer, and VS Code Live Share have made real-time collaboration an essential part of learning, teaching, and professional teamwork. This project is an attempt to build a simplified yet effective real-time collaborative coding platform.

🔹 Key Features Implemented
Room Management

Users can create a new collaboration room or join an existing one using a Room ID.

Each room is uniquely identified using the uuid library.

User Identification

Users can set their username to be recognized in the room.

Real-Time Collaboration

Implemented using Socket.IO for bidirectional communication.

Code changes made by one user are instantly synced across all connected users in the room.

Code Editor Integration

Integrated with CodeMirror for a rich coding experience.

Features include syntax highlighting and editor customization options.

Database & Server Integration

Backend built using Express.js and Node.js.

MongoDB manages room and user session details.

Responsive Design

Built with React.js for a modern, clean, and responsive interface.

Ensures usability across desktops, tablets, and mobile devices.

Deployment

Backend deployed on Render.

Frontend hosted with Netlify/Vercel (optional).

Accessible via live demo link.

🛠️ Working of the Application

When a user opens the app, they can create or join a room using a Room ID.

The user sets a username to identify themselves.

Once inside the room, Socket.IO establishes a persistent connection between the server and all clients in the room.

As soon as one user edits the code, the changes are emitted through the socket to the server.

The server then broadcasts updates to all other connected clients in the same room.

All users see the updated code instantly without any page refresh.

This architecture ensures smooth collaboration, enabling multiple users to code together in real time.

📸 Screenshots

🚀 Live Demo

👉 Click here to try CodeCast
https://codecast-324z.onrender.com/

📌 Conclusion

Through this project, I gained hands-on experience in building real-time collaborative applications using MERN + Socket.IO.

I learned how to:

Establish real-time bidirectional communication using WebSockets.

Implement state synchronization across multiple clients.

Integrate a code editor (CodeMirror) into a React app.

Deploy a full-stack MERN application to cloud platforms.

This project significantly improved my skills in full-stack development, real-time systems, and team collaboration tools, preparing me for building more advanced web applications in the future.
