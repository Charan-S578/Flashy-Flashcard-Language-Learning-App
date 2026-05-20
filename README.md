# Flashy – Flashcard Language Learning App

This Python project is a Flashcard-based language learning app built using Tkinter and Pandas. It helps users learn French words by showing flashcards that flip between French and English meanings. Users can mark known words, and the app randomly cycles through remaining words for effective memorization.

---

## 📌 Features

- Flashcard-based learning system
- Random French word selection
- Automatic card flip after 3 seconds
- Mark words as known or unknown
- Dynamic word list updates
- Simple and interactive GUI

---

## 🛠 Technologies Used

- Python 3
- Tkinter GUI Library
- Pandas
- Random module

---

## 📂 Project Structure

```text
Project/
│
├── main.py
├── data/
│   └── french_words.csv
├── images/
│   ├── card_front.png
│   ├── card_back.png
│   ├── right.png
│   └── wrong.png
└── README.md


▶️ How It Works
App loads French words from CSV.
A random French word is displayed.
After 3 seconds, it flips to show English meaning.
User clicks ✔ if known or ✖ if unknown.
Known words are removed from learning list.


🚀 How to Run
python main.py
