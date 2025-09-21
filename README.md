# Text to Speech Web Application

A simple and responsive web application that converts text to speech using the browser's built-in speech synthesis API.

## Features

- **Text-to-Speech Conversion**: Enter any text and have it read aloud
- **Responsive Design**: Works on desktop, tablet, and mobile devices
- **Clean UI**: Minimalist and user-friendly interface
- **No External Dependencies**: Uses only native browser APIs

## How to Use

1. Open the `index.html` file in a modern web browser
2. Type or paste your text into the text area
3. Click the "Speak" button to hear the text read aloud

## Browser Compatibility

This application uses the [Web Speech API](https://developer.mozilla.org/en-US/docs/Web/API/Web_Speech_API), which is supported in:
- Chrome (version 33+)
- Edge (version 14+)
- Firefox (version 49+)
- Safari (version 7+)
  
## Technical Details

The application uses the `SpeechSynthesisUtterance` interface of the Web Speech API to convert text to speech. The speech parameters are set as follows:
- Rate: 1 (normal speed)
- Volume: 5 (maximum)
- Pitch: 1 (normal pitch)

## Customization

You can modify the speech parameters in the JavaScript code:
```javascript
speech.rate = 1;    // Speech rate (0.1 to 10)
speech.volume = 5;  // Volume (0 to 1)
speech.pitch = 1;   // Pitch (0 to 2)

## File Structure
text-to-speech/
├── index.html # Main application file
├── mic.png # Microphone icon
└── README.md # This file
