# Speak to Code - Real-Time Voice to Code Generation

**Speak to Code** is an innovative project that converts real-time voice input into programming code in various languages. Leveraging **Whisper AI** for speech-to-text transcription and the **Gemini API** for code generation, this project enables users to dictate code in natural language and instantly receive code in languages like Python, JavaScript, C++, and more.

## Features
- **Voice Input**: Convert real-time spoken language into code.
- **Whisper AI**: Accurate speech-to-text transcription, supporting various languages and accents.
- **Gemini API**: Converts transcribed text into executable code in multiple programming languages.
- **Real-Time Processing**: Immediate conversion of speech into code, ready for execution or testing.
- **Multi-Language Support**: Generate code in Python, JavaScript, C++, and more.

## Technologies Used
- **Whisper AI**: Speech-to-text model for transcribing real-time voice input.
- **Gemini API**: AI-powered code generation based on natural language descriptions.
- **Python**: Used for handling backend processes and integration.
- **Flask/Django**: For creating a simple web interface (optional, based on your implementation).
- **WebSockets**: For real-time communication between voice input and code output.

## Getting Started
To get started with **Speak to Code**, clone the repository and follow the instructions below:

### Prerequisites
- [Python 3.8+](https://www.python.org/)
- [Whisper AI](https://github.com/openai/whisper)
- [Gemini API](https://www.gemini.com/)
- [Flask](https://flask.palletsprojects.com/) (optional for web interface)

### Installation
1. Clone the repository:
    ```bash
    git clone https://github.com/sufyanbinimran/speak-to-code.git
    ```

2. Navigate to the project folder:
    ```bash
    cd speak-to-code
    ```

3. Install dependencies:
    ```bash
    pip install -r requirements.txt
    ```

4. Run the application:
    ```bash
    python app.py
    ```

5. Use the web interface or command-line tool to start speaking commands and see them converted into code.

## Live Demo & Blog
- 🎤 **Try the App**: [Streamlit Demo](https://sufyan-gen-ai-speak-code.streamlit.app/)
- 📝 **Read the Blog**: [Revolutionizing Coding with Your Voice](https://medium.com/@sufyanbinimran/revolutionizing-coding-with-your-voice-️-99d578851341)

## Contributing
We welcome contributions to enhance this project! Fork the repository, submit issues, or create pull requests to help improve **Speak to Code**.

## License
This project is licensed under the MIT License - see the [LICENSE](LICENSE) file for details.

## Acknowledgements
- Special thanks to the creators of Whisper AI and the Gemini API for their contributions to AI-powered speech-to-text and code generation.

---

For more details or support, visit the [GitHub Repository](https://github.com/sufyanbinimran/speak-to-code).
