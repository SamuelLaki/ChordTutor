# ChordTutor

ChordTutor is a Guitar Chord Learning web application designed to help users learn and practice guitar chords through interactive lessons and quizzes.

**Made with Tesfalem Eshetu and Sarah Nasser**

## Features

- 🎸 Interactive chord learning interface
- 🖼️ Chord visualization with images
- 🔊 Audio playback for each chord
- 🎯 Drag and Drop quiz mode to test your knowledge
- 📊 Progress tracking

## Screenshots

### Homepage
![Homepage Screenshot](https://github.com/user-attachments/assets/9e347c02-b24e-49ad-b86e-c4ada838b1bc)

### Learn Section
![Learn Section Screenshot](https://github.com/user-attachments/assets/d3686b99-9146-43d6-9bfa-c054f17a735e)

### Quiz Mode
![Quiz Mode Screenshot](https://github.com/user-attachments/assets/fb036d6b-fc99-464e-a62a-2253eaf5e227)

### Chord Details
![Chord Details Screenshot](https://github.com/user-attachments/assets/68d41a2f-d5c6-4fff-840b-fa748344ddca)

## Requirements

- Python 3.6 or higher
- Flask

## Installation

1. **Clone the repository:**
```bash
   git clone https://github.com/SamuelLaki/ChordTutor.git
   cd ChordTutor
```

2. **Create a virtual environment (recommended):**
   ```bash
   # On macOS/Linux
   python3 -m venv venv
   source venv/bin/activate

   # On Windows
   python -m venv venv
   venv\Scripts\activate
   ```

3. **Install dependencies:**
```bash
pip install flask
```

## Running the Application Locally

1. **Start the Flask development server:**
```bash
python server.py
```

2. **Open your web browser and navigate to:**
```
http://127.0.0.1:5000/
```

## Project Structure

```
ChordTutor/
├── server.py              # Main Flask application file
├── templates/             # HTML templates
│   ├── homepage.html
│   ├── learn.html
│   ├── quiz.html
│   └── ...
├── static/               # Static files
│   ├── main.css         # CSS styles
│   ├── images/          # Chord images and assets
│   ├── chord_audios/    # Audio files for chords
│   └── ...
└── README.md
```

## How to Use

1. **Visit the homepage** to get started
2. **Navigate to the "Learn" section** to explore different chords
3. **Use the Quiz feature** to test your knowledge with drag-and-drop functionality
4. **Track your progress** as you learn

## Features in Detail

- **Interactive Learning**: Click on chords to hear their audio and see detailed fingerings
- **Visual Learning**: High-quality chord diagrams for easy understanding
- **Audio Support**: Listen to how each chord should sound
- **Quiz Mode**: Test your knowledge with an interactive drag-and-drop quiz
- **Responsive Design**: Works on desktop and mobile devices

## Contributing

Feel free to contribute to this project by submitting issues or pull requests.

## License

This project is open source and available under the [MIT License](LICENSE).
