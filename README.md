# Butterfly AI Chatbot

A versatile AI-powered chatbot built with Flask and OpenAI's API, offering multiple interaction modes for different purposes.

## Features

- **Multiple Modes**: 
  - Normal Mode: Friendly and intelligent conversations
  - Coding Mode: Senior Software Engineer assistance with production-ready code and DSA explanations
  - Study Mode: Expert teacher providing step-by-step explanations
  - Interview Mode: Technical interviewer for practice and feedback
  - Content Mode: Professional content writer for blogs and social media

- **Real-time Chat Interface**: Interactive web-based chat interface
- **OpenAI Integration**: Powered by OpenAI's API for intelligent responses

## Prerequisites

- Python 3.8+
- pip (Python package manager)
- OpenAI API key

## Installation

1. Clone the repository:
```bash
git clone https://github.com/deepikadeepu18122004-collab/BUTTERFLY-AI.git
cd BUTTERFLY-AI
```

2. Create a virtual environment:
```bash
python -m venv venv
source venv/Scripts/activate  # On Windows
# or
source venv/bin/activate  # On macOS/Linux
```

3. Install dependencies:
```bash
pip install -r requirements.txt
```

4. Create a `.env` file in the root directory and add your OpenAI API key:
```
OPENAI_API_KEY=your_api_key_here
```

## Usage

1. Start the Flask server:
```bash
python app.py
```

2. Open your browser and navigate to:
```
http://localhost:5000
```

3. Select a mode and start chatting!

## Project Structure

```
BUTTERFLY-AI/
├── app.py              # Main Flask application
├── templates/
│   └── index.html      # Chat interface HTML
├── static/
│   ├── script.js       # Frontend JavaScript
│   └── style.css       # Frontend CSS
├── requirements.txt    # Python dependencies
├── .env               # Environment variables (not tracked)
└── README.md          # This file
```

## Technologies Used

- **Backend**: Flask
- **AI API**: OpenAI
- **Frontend**: HTML, CSS, JavaScript
- **Environment**: Python dotenv for configuration

## License

This project is open source and available under the MIT License.

## Author

Created by deepikadeepu18122004-collab

## Support

For issues and questions, please open an issue on GitHub.
