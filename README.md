## How to run
### Installation:
1. Clone the repository
2. In your terminal, write: ```npm install```
2. In the project directory, create .env file and add your API key as: ```API_KEY="Paste API Key here"``` (navigate to https://aistudio.google.com to generate API key)
**Note**: I have used Gemini 1.5 pro model. Check [main.js](https://github.com/Aaryan015/Gemini-Chatbot/blob/main/main.js) for model parameters.
3. Write ```node main.js``` on your IDE's terminal to run the server and navigate to localhost:3000 (double-check port number)
-----
P.S. - If you get 'undefined' as response while using the chatbot, it may be due to too many requests at the server end. To solve this, try to send each query with a brief pause.
