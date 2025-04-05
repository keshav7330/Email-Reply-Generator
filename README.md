"# Email-Reply-Generator" 
An AI-powered email reply assistant built with **Spring Boot** and **React**, designed to generate professional responses to incoming emails. 
Initially built as a standalone web app, the project is also being developed into a Chrome Extension for seamless integration with Gmail.


## 🚀 Features

- ✉️ Generate contextual replies for incoming emails
- ⚙️ React frontend with dynamic UI
- ☕ Spring Boot backend handling AI logic and routing
- 🔗 Chrome Extension version for native Gmail experience *(in progress)*

---

## 🛠️ Tech Stack

- **Frontend**: React
- **Backend**: Spring Boot
- **Extension**: Chrome Extension (locally loadable)
- **IDE**: IntelliJ IDEA for Spring Boot
  
## 📦 Folder Structure

  email-reply-generator/
├── backend/              # Spring Boot backend (Java)
├── frontend/             # React frontend (JS/TS)
└── chrome-extension/     # Chrome extension files

How to Run the Project

🔹 Backend (Spring Boot)
You can run the Spring Boot application directly in IntelliJ IDEA:

Open the backend folder in IntelliJ.

Run the main application file (with @SpringBootApplication).

Server starts at: http://localhost:8080 (default)



🔹 Frontend (React)
Open a terminal in the frontend folder:

cd frontend
npm install       # Install dependencies
npm run dev       # Start the development server



🔹 Chrome Extension (Manual Load)
To test the Gmail integration via Chrome Extension:

Go to chrome://extensions/

Enable Developer Mode

Click Load unpacked

Select the chrome-extension/ folder of this project

Extension will be added to Chrome locally

📝 Refer to official Chrome Extension Docs for more details on local setup.

