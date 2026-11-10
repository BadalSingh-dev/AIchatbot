# AI Chatbot 🤖

A **Java-based AI Chatbot** designed for interactive communication using **Natural Language Processing (NLP) concepts** and **rule-based artificial intelligence**.

The chatbot analyzes user input, identifies the user's intent, and provides an appropriate response using a collection of trained FAQ and conversation patterns.

## ✨ Features

- 🤖 Interactive AI chatbot
- 🧠 NLP-style text processing
- 🔍 Intent recognition and classification
- 📚 Frequently Asked Questions (FAQ) responses
- 💬 Rule-based response generation
- 🔄 Fallback responses for unknown queries
- 🖥️ Java Swing GUI
- ⌨️ Console-based interaction
- ⏰ Date and time responses
- 🚪 Exit and help commands

## 🛠️ Technologies Used

- **Java**
- **Object-Oriented Programming (OOP)**
- **Natural Language Processing Concepts**
- **Rule-Based AI**
- **Java Swing**
- **String Processing**
- **Collections Framework**

## 🧠 How It Works

The chatbot follows a simple NLP and intent-matching pipeline:

```text
User Input
    ↓
Text Preprocessing
    ↓
Tokenization / Keyword Analysis
    ↓
Intent Detection
    ↓
Rule-Based Response Selection
    ↓
Chatbot Response
```

For example:

```text
User: Hello

Chatbot: Hello! How can I help you?
```

Another example:

```text
User: What can you do?

Chatbot: I can answer FAQs, respond to greetings,
and help you with basic conversations.
```

## 🚀 Getting Started

### Prerequisites

Install **Java JDK 8 or later**.

Check your Java installation:

```bash
java -version
```

Check the compiler:

```bash
javac -version
```

### Run the Project

Compile the source files:

```bash
javac src/*.java
```

Run the application:

```bash
java -cp src Main
```

### Windows

If the project includes `run.bat`, you can simply double-click it or run:

```bash
run.bat
```

## 💻 Interfaces

The project supports two ways of interacting with the chatbot:

### Console Interface

Run the application through the terminal and communicate with the chatbot using text input.

### GUI Interface

The Java Swing interface provides a simple chat window where users can enter messages and receive responses in real time.

## 📂 Project Structure

```text
AIChatbot/
├── src/
│   ├── Main.java
│   ├── Chatbot.java
│   ├── Intent.java
│   ├── NLPProcessor.java
│   └── ChatbotGUI.java
├── README.md
└── run.bat
```

## 🎯 Learning Objectives

This project was developed to gain practical experience with:

- Java application development
- Object-oriented programming
- NLP concepts
- Intent classification
- Rule-based AI systems
- GUI development using Java Swing
- Text processing and pattern matching
- Building interactive software

## 🔮 Future Improvements

- Integrate a real machine-learning NLP model
- Add a larger training dataset
- Implement sentiment analysis
- Add voice input and output
- Connect the chatbot to an external API
- Store conversation history
- Add database integration
- Improve intent classification using ML algorithms

## 👨‍💻 Author

**Badal Singh**

Built as a practical Java project to explore **Artificial Intelligence, NLP, and interactive application development**.
