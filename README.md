# CodeCrafter  
An **AI-powered tool** built with the **MERN stack** for **analyzing, reviewing, and generating** code to boost development efficiency.  

---

## Features  
- **AI Code Review**: Analyzes your code and suggests improvements.  
- **Code Generation**: Generates optimized code snippets for various programming languages.  
- **Google AI Integration**: Leverages Google’s Gemini AI to detect issues, improve, and generate code.  
- **Express.js Server**: Handles AI requests and user inputs efficiently.  
- **CORS Support**: Ensures smooth API communication.  
- **Syntax Highlighting**: Uses **Prism.js** for better readability.  
- **User-Friendly Interface**: Built with React and optimized for seamless experience.  
- **Multi-Language Support**: Supports Python, Java, C++, and more. 

---

## Installation & Setup  

### 1️. Clone the Repository  
```sh
git clone https://github.com/srijaniroy/CodeCrafter
cd CodeCrafter
```

### 2️. Install Dependencies  
```sh
# Backend
cd backend
npm install

# Frontend
cd ../frontend
npm install
```

### 3️. Set Up Environment Variables  

   Create a `.env` file in the backend folder and add Google Gemini API key.

   Example `.env`:

   ```
   GOOGLE_GEMINI_KEY=your-google-api-key
   ```
### 4️. Run the Project  
```sh
# Start backend
cd BackEnd
npx nodemon

# Start frontend
cd ../Frontend
npm run dev
```

---

## How It Works

1. **User Submits Code:** The user enters code in the provided editor.
2. **AI Reviews Code:** After the user clicks the "Generate or Review" button, the code is sent to the backend, which processes it using the AI model.
3. **AI Feedback:** The AI analyzes the code and generates feedback, which is then displayed in a formatted review on the frontend.
4. **Suggestions & Fixes:** The review includes suggestions for improving code quality, performance, error fixes, and security checks.

---

## Technologies Used

- **Frontend:** 
  - **React**: For building the UI.
  - **PrismJS**: For code syntax highlighting.
  - **Markdown**: For displaying AI-generated reviews.
  - **Axios**: For making API requests to the backend.

- **Backend:**
  - **Node.js & Express**: To create the backend server and handle API requests.
  - **AI Integration**: Using **Google Gemini API** (Model: Gemini 2.0 Flash) for code analysis and review.

---
 
## Future Enhancements  
- **User Authentication** (Sign-up, login, and user history).  
- **Real-Time Collaboration** (Live editing and reviews).  
- **Code Auto-Fixes** (Automatically apply AI-suggested corrections and optimizations to your code with a single click).  
