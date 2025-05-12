## 🗣️ Text to Speech Converter

A simple and elegant web application that converts written text into spoken audio using the **Web Speech API**. Built with **HTML**, **CSS**, and **JavaScript**, it allows users to select from a variety of available voices and listen to the entered text.

---

### 🚀 Features

- Convert typed text into speech instantly
- Choose from multiple voices (based on the system/browser)
- Clean and modern UI with gradient styling
- Fully responsive and user-friendly design
- No third-party libraries or dependencies

---

### 🛠️ Technologies Used

- **HTML** – for structuring the interface  
- **CSS** – for styling and animations  
- **JavaScript (Vanilla)** – to implement the speech synthesis logic  
- **Web Speech API** – to handle voice selection and text-to-speech conversion

---

### 🔍 How It Works

1. User types or pastes text into the input area.
2. The browser fetches the list of available voices using the `SpeechSynthesis.getVoices()` method.
3. User selects a voice from the dropdown list.
4. When the "Listen" button is clicked, the app uses the `SpeechSynthesisUtterance()` object to speak the entered text.

---


### 📦 Setup Instructions

1. Clone the repository:

git clone https://github.com/Uvajanani/Text-to-Speech-Converter.git

2. Navigate into the project directory:

cd text-to-speech-converter

3. Open `index.html` in your browser to use the app.

> 💡 No need for installation or dependencies — everything runs in the browser!

