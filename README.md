# Healthcare Chatbot

This is a simple healthcare chatbot built using Node.js for the backend and HTML/CSS/JavaScript for the frontend.

## Features

✔ Provides replies based on common diseases, symptoms, and queries  
✔ Modern UI with interactive chat  
✔ Uses OpenAI API for intelligent replies  
✔ Easily extensible by adding more data in `diseases.json`

## Project Structure

Healthcare-Chatbot/
├── backend/ # Server logic and API configuration
├── frontend/ # Chat interface for users
├── .gitignore # Files to exclude from GitHub
├── README.md # This file


## Setup Instructions

### 1. Clone the repository

### 2. Install dependencies
npm install
### 3. Create `.env` file in `backend/` folder
Add the following content:
OPENAI_API_KEY=your_openai_api_key

Replace `your_openai_api_key` with your actual OpenAI API key.

### 4. Run the backend
node index.js

You should see:
Backend running on http://localhost:5000


### 5. Open the frontend
Open `frontend/index.html` in your browser and start chatting!

---

## ⚙ Notes

- The `.env` file is ignored and **will not be uploaded** to GitHub.
- You can add more diseases in `backend/data/diseases.json`.
- This project is for learning purposes.

---

Happy coding! 🚀
