# CHAT-APPLICATION
 
COMPANY: CODTECH IT SOLUTIONS

NAME: MACHARLA ARAVIND

INTERN ID: CT06DF238

DOMAIN: FULL STACK WEB DEVELOPMENT

DURATION: 6 WEEKS

MENTOR: NEELA SANTOSH

## Project Title: Real-Time Chat Application Using Node.js and Socket.IO
📝 Project Description:
This project is a real-time chat application developed as part of Task 2 of the CodTech Full Stack Web Development Internship. The main objective of this task was to build a fully functional web-based chat app where users can send and receive messages live — without refreshing the page. It focuses on implementing two-way communication between the frontend and backend using Socket.IO, a JavaScript library that enables real-time, bidirectional, and event-based communication.As a beginner in web development, this task gave me a practical experience of working with real-time applications, understanding how WebSockets work behind the scenes, and integrating the frontend and backend smoothly using Node.js, Express, and vanilla JavaScript.The chat application consists of a clean and simple interface where users can type a message and click “Send.” Instantly, the message appears in the chat window, and if the same page is opened in another tab or browser, it gets updated there too — proving that the chat works live and in real-time. This is made possible by the Socket.IO library, which wraps around WebSockets and handles all the real-time message broadcasting and listening.On the frontend, I used basic HTML, CSS, and JavaScript to build the user interface. There’s a heading ("Live Chat"), a list to display messages, and an input box with a send button. The layout is responsive and works on both desktop and mobile devices. On the backend, I created a Node.js server using Express.js, and added Socket.IO to listen for chat events from users. When a message is received from one user, the server broadcasts it to all connected clients — including the original sender.One of the most important things I learned during this task was how to set up and manage file structures properly. All frontend files (index.html, style.css, and script.js) were placed inside a folder called public, and the server used express.static('public') to serve those files. I also learned how small errors like incorrect file extensions (like .rtf instead of .html) or putting files in the wrong folder can break the whole app. Fixing these issues manually helped me understand real-world debugging and file management.
The project was built entirely using TextEdit (in Plain Text mode) and Terminal on macOS, without any advanced IDE like VS Code. This helped me become comfortable working with the command line, using commands like cd, ls, npm init, and npm install to manage the project and install necessary dependencies. I also learned how to start and stop a Node.js server using node server.js, and how to check for errors like “Cannot GET /” and fix them.
Here’s what the folder structure looked like:
pgsql
Copy
Edit
chat-app/
├── server.js
├── package.json
└── public/
    ├── index.html
    ├── style.css
    └── script.js
    
In conclusion, Task 2 helped me understand the concept of real-time applications, socket communication, and backend event handling. It strengthened my knowledge of how client and server communicate, how to manage projects in a full stack setup, and gave me the confidence to build chat-based or multiplayer applications in the future. This was an excellent follow-up to Task 1, and a major step forward in my journey as a full stack web developer.

#OUTPUT
