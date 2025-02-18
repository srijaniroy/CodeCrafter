
# CodeCrafter  
An **AI-powered tool** built with the **MERN stack** for **analyzing, reviewing, and generating** code to boost development efficiency.  

## Features  
- **AI Code Review**: Analyzes your code and suggests improvements.  
- **Code Generation**: Generates optimized code snippets for various programming languages.  
- **Google AI Integration**: Leverages Google’s Gemini AI to detect issues, improve, and generate code.  
- **Express.js Server**: Handles AI requests and user inputs efficiently.  
- **CORS Support**: Ensures smooth API communication.  
- **Syntax Highlighting**: Uses **Prism.js** for better readability.  
- **User-Friendly Interface**: Built with React and optimized for seamless experience.  
- **Multi-Language Support**: Supports Python, Java, C++, and more.  

## Installation & Setup  

1. Clone the Repository  
   ```sh
   git clone https://github.com/srijaniroy/CodeCrafter
   cd CodeCrafter
   ```

2. Install Dependencies  
   ```sh
   # Backend
   cd BackEnd
   npm install

   # Frontend
   cd ../Frontend
   npm install
   ```

3. Set Up Environment Variables  

   Create a `.env` file in the backend folder and add the Google Gemini API key.  

   Example `.env` file:  
   ```
   GOOGLE_GEMINI_KEY=your-google-api-key
   ```

4. Run the Project  
   ```sh
   # Start backend
   cd BackEnd
   npx nodemon

   # Start frontend
   cd ../Frontend
   npm run dev
   ```
   The frontend will be available at `http://localhost:5173`, and the backend at `http://localhost:3000`.  

## How It Works  

1. **User Submits Code**: The user enters code in the provided editor.  
2. **AI Reviews Code**: After the user clicks the "Generate or Review" button, the code is sent to the backend, which processes it using the AI model.  
3. **AI Feedback**: The AI analyzes the code and generates feedback, which is then displayed in a formatted review on the frontend.  
4. **Suggestions & Fixes**: The review includes suggestions for improving code quality, performance, error fixes, and security checks.  

## Technologies Used  

### Frontend  
- **React.js** – For building the user interface  
- **Vite** – For fast development and optimized builds  
- **Prism.js** – For code syntax highlighting  
- **Markdown** – For displaying AI-generated reviews  
- **Axios** – For handling API requests  

### Backend  
- **Node.js** – JavaScript runtime for backend logic  
- **Express.js** – Lightweight server framework  
- **CORS** – For secure cross-origin requests  
- **Google Gemini AI** – AI model Gemini 2.0 Flash used for code analysis and generation  

## Future Enhancements  
- **User Authentication** – Sign-up, login, and user history  
- **Real-Time Collaboration** – Live editing and reviews  
- **Code Auto-Fixes** – Automatically apply AI-suggested corrections and optimizations to your code with a single click  
