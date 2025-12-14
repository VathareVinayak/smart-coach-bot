# Smart Sports Coach Chatbot 🤖🏏

A minimal Rasa-based conversational AI project inspired by AI-powered sports coaching platforms such as Sherlock SuperCoach.

## 🎯 Objective
To build a lightweight and clean chatbot that provides basic sports coaching guidance, focusing on fitness, match preparation, and motivation using intent-based conversation design.

## 🧠 Key Features
- Simple greeting and farewell interactions  
- Fitness-related coaching tips  
- Match preparation guidance  
- Motivation and mindset support  

## 🛠 Tech Stack
- Python  
- Rasa Open Source  
- YAML  

## 📁 Project Structure
- `data/nlu.yml` – Defines user intents and training examples  
- `data/stories.yml` – Handles conversation flows  
- `domain.yml` – Contains intents and bot responses  
- `config.yml` – Defines the NLU pipeline and dialogue policies  

## 🚀 How to Run
```bash
# Train the Rasa model
rasa train

# Talk to the chatbot in the terminal
rasa shell
````

## 📌 Scope & Design Choice

This project is intentionally kept small to demonstrate best practices in Rasa fundamentals without overengineering.
It is designed to be easily extendable with advanced AI models, user profiling, or external APIs in future iterations.

## 🔮 Future Enhancements

* Personalized coaching suggestions
* Mood-based responses
* Integration with sports analytics APIs

---
