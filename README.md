# J-arvis - Phone Assistant

A web-based phone assistant with voice recognition, API integrations, and task automation features.

## Features
- ✅ Voice command recognition (Web Speech API)
- ✅ Text-based chat interface
- ✅ Weather API integration
- ✅ News API integration
- ✅ Task and reminder management
- ✅ Python Flask backend
- ✅ HTML/JavaScript frontend
- ✅ Natural language processing

## Project Structure
```
J-arvis-/
├── backend/
│   ├── app.py
│   ├── requirements.txt
│   ├── config.py
│   └── utils.py
├── frontend/
│   ├── index.html
│   ├── css/
│   │   └── style.css
│   └── js/
│       └── main.js
├── README.md
└── .gitignore
```

## Technologies Used
- **Backend:** Python (Flask)
- **Frontend:** HTML5, CSS3, JavaScript
- **APIs:** Web Speech API, Weather API, News API
- **Version Control:** Git & GitHub

## Getting Started

### Prerequisites
- Python 3.8+
- Node.js (optional for frontend tools)
- API Keys: OpenWeatherMap, NewsAPI

### Installation

1. **Clone the repository:**
```bash
git clone https://github.com/emmanuelchrisnchang-tech/J-arvis-.git
cd J-arvis-
```

2. **Install backend dependencies:**
```bash
pip install -r backend/requirements.txt
```

3. **Set up environment variables:**
Create a `.env` file in the backend folder:
```
WEATHER_API_KEY=your_openweathermap_key
NEWS_API_KEY=your_newsapi_key
FLASK_ENV=development
```

4. **Run the Flask app:**
```bash
python backend/app.py
```

5. **Open the frontend:**
Open `frontend/index.html` in your web browser.

## Features Explained

### Voice Recognition
Uses the Web Speech API to recognize voice commands and convert them to text.

### Chat Interface
Text-based interaction where users can type commands or questions.

### Weather Integration
Fetches current weather data and forecasts using OpenWeatherMap API.

### News Integration
Retrieves latest news headlines using NewsAPI.

### Task Management
Create, update, and manage reminders and tasks locally.

## Usage

1. Open the assistant in your browser
2. Click the microphone icon to start voice recognition
3. Speak your command (e.g., "What's the weather?", "Show me news")
4. The assistant will process and respond

## Contributing
Feel free to fork this repository and submit pull requests for improvements!

## License
This project is open source and available under the MIT License.

## Author
Created by emmanuelchrisnchang-tech

## Support
For issues, questions, or suggestions, please open an issue on GitHub.