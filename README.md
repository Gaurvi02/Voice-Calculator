
# Voice Calculator

## Introduction

Voice Calculator is an innovative Python-based application that combines speech recognition and text-to-speech technologies to perform calculations and provide spoken feedback. This project features a user-friendly graphical interface created with Tkinter and integrates the powerful Wolfram Alpha API for handling complex calculations.

## Features

- **Voice-Activated Calculations**: Perform mathematical operations using voice commands.
- **Time-Sensitive Greetings**: Receives personalized greetings based on the time of day.
- **Intuitive GUI**: Simple and clean interface for easy interaction.
- **Wolfram Alpha Integration**: Capability to solve advanced mathematical problems.
- **Multilingual Support**: Ability to understand and respond in multiple languages.

## Requirements

Before installation, ensure your system meets the following requirements:

- Python 3.x
- Active internet connection (for Wolfram Alpha API)
- Audio input device (microphone)

## Installation

Follow these steps to set up the Voice Calculator on your local machine:

1. **Clone the Repository**:
   ```bash
   git clone https://github.com/Gaurvi02/Voice-Calculator.git
   cd Voice-Calculator
   ```

2. **Install Required Libraries**:
   ```bash
   pip install pyttsx3 wolframalpha SpeechRecognition pyaudio
   ```

3. **Wolfram Alpha API Setup**:

   - Obtain an API key from Wolfram Alpha Developer Portal.
   - In the voice_calculator.py file, replace the placeholder in the WolfRamAlpha function with your API key:
     ```python
     app_id = "YOUR-API-KEY-HERE"
     ```

## Usage

To start using the Voice Calculator:

1. **Launch the Application**:
   ```bash
   python voice_calculator.py
   ```

2. **Interacting with the Calculator**:
   - The app will greet you based on the current time.
   - Say "wake up" to activate the calculator.
   - Use voice commands for calculations, e.g., "calculate 5 plus 3".
   - To exit, say "finally sleep".

## Code Structure

The main script `voice_calculator.py` contains several key functions:

- `greetMe()`: Provides time-based greetings.
- `speak(audio)`: Converts text to speech.
- `takeCommand()`: Captures and processes voice input.
- `WolfRamAlpha(query)`: Interfaces with Wolfram Alpha API.
- `Calc(query)`: Handles mathematical calculations.
- `project()`: Main function for voice command processing.
- `myclick()`: GUI update function.

## GUI Components

The application features a simple GUI created with Tkinter:

- A microphone button to activate voice input.
- Visual feedback for active listening state.

## Troubleshooting

If you encounter issues:

- Ensure your microphone is properly connected and configured.
- Check your internet connection for Wolfram Alpha queries.
- Verify that all required libraries are correctly installed.

## Contributing

Contributions to the Voice Calculator project are welcome! Please follow these steps:

1. Fork the repository.
2. Create a new branch for your feature.
3. Commit your changes.
4. Push to the branch.
5. Create a new Pull Request.

## License

This project is licensed under the MIT License. See the LICENSE file for details.

## Acknowledgments

- Thanks to the Wolfram Alpha team for their powerful API.
- Appreciation to the developers of the speech recognition and text-to-speech libraries used in this project.

## Contact

For questions or feedback, please contact Gaurvi Sood.

Enjoy calculating with your voice!
