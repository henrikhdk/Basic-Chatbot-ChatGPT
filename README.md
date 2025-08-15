# Basic Chatbot with ChatGPT

## Overview
This project is a simple chatbot application that leverages OpenAI's ChatGPT API to provide conversational capabilities. The chatbot is built using Node.js and serves a web-based interface for users to interact with the bot.

## Features
- **Interactive Chat Interface**: A user-friendly web interface for chatting with the bot.
- **Powered by ChatGPT**: Utilizes OpenAI's ChatGPT API for generating responses.
- **Customizable**: Easily extendable to include additional features or integrate with other APIs.

## Project Structure
```
Basic-Chatbot-ChatGPT/
├── openai.js          # Handles interaction with OpenAI's API
├── package.json       # Project dependencies and scripts
├── server.js          # Node.js server setup
├── public/            # Static files served by the server
│   ├── index.html     # Main HTML file for the chatbot interface
│   ├── main.js        # Frontend JavaScript for handling user input and bot responses
│   └── style.css      # Styling for the chatbot interface
```

## Prerequisites
- Node.js (v14 or later)
- An OpenAI API key

## Installation
1. Clone the repository:
   ```bash
   git clone https://github.com/henrikhdk/Basic-Chatbot-ChatGPT.git
   ```
2. Navigate to the project directory:
   ```bash
   cd Basic-Chatbot-ChatGPT
   ```
3. Install dependencies:
   ```bash
   npm install
   ```

## Configuration
1. Create a `.env` file in the root directory.
2. Add your OpenAI API key to the `.env` file:
   ```env
   OPENAI_API_KEY=your_openai_api_key_here
   ```

## Usage
1. Start the server:
   ```bash
   node server.js
   ```
2. Open your browser and navigate to `http://localhost:3000`.
3. Start chatting with the bot!

## Contributing
Contributions are welcome! Feel free to open an issue or submit a pull request.

## License
This project is licensed under the MIT License. See the LICENSE file for details.

## Acknowledgments
- [OpenAI](https://openai.com) for providing the ChatGPT API.
- [Node.js](https://nodejs.org) for the server runtime.

---

Enjoy building and chatting with your bot!
