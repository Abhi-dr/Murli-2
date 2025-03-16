# Murli - 2

This is a simplified version of the Murli application that provides guidance from Lord Krishna based on the Bhagavad Gita. This version uses only HTML, CSS, and JavaScript without any frameworks or libraries.

## Features

- Ask questions and receive guidance based on Bhagavad Gita teachings using Google's Gemini AI API
- Support for text input or speech recognition (on compatible browsers)
- Background music for an immersive experience
- Responsive design that works on mobile and desktop
- Fallback responses if the API is unavailable

## Setup Instructions

1. Make sure all files are in the same directory:
   - `index.html`
   - `styles.css`
   - `script.js`
   - `mahabharat.mp3` (background music)

2. Open `index.html` in a web browser to use the application.
3. Open `script.js` and add your own API Key.

## How It Works

1. Enter your name and preferred language
2. Type your question or use the microphone feature to speak
3. Click "Ask For Guidance" to receive a response
4. The application connects to the Gemini API to generate a response based on the Bhagavad Gita
5. If the API call fails for any reason, the application falls back to pre-defined responses
6. The response will appear below with background music

## Technical Details

The application uses:
- HTML5 for structure
- CSS3 for styling
- JavaScript (ES6+) for functionality
- Web Speech API for speech recognition
- Fetch API for making requests to the Gemini API
- Google's Gemini Pro model for generating responses based on Bhagavad Gita teachings

## Privacy and Security

- The API key is securely embedded in the application
- No user data is stored on any server
- All processing happens in your browser
- The application works offline for fallback responses if no internet connection is available

## Customization

You can easily customize this application by:
- Modifying the CSS in `styles.css` to change colors and layout
- Editing the prompt template in the `fetchGuidance` function to change how responses are generated
- Adding more fallback responses in the `generateFallbackResponse` function
