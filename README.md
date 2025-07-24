Advanced Flashcard Quizzer

Overview

Flashcard Quizzer is an interactive command-line quiz application that loads flashcards from a JSON file, allows users to select categories, answer timed questions, and tracks their score and success rate. It supports exiting the quiz anytime by typing “exit”.

⸻

Features
	•	Load flashcards from a JSON file 
 
	•	Display available categories and let users select one
 
	•	Present questions one by one with answer input
 
	•	Case-insensitive answer checking
 
	•	Track score and total questions answered
 
	•	Show time taken per question
 
	•	Allow exiting quiz anytime by typing “exit”
 
	•	Show final results with score and percentage success rate

⸻

Requirements
	•	Python 3.x
	•	A JSON file containing flashcards structured by categories


 Flashcards JSON Format

The JSON file should be structured as an object with categories as keys and lists of flashcards as values. Each flashcard is an object with "question" and "answer" keys.

Example:

{
  "Science": [
    {"question": "What planet is known as the Red Planet?", "answer": "Mars"},
    {"question": "What is the chemical symbol for water?", "answer": "H2O"}
  ],
  "History": [
    {"question": "Who was the first president of the United States?", "answer": "George Washington"}
  ]
}

How to Use

	1.	Prepare your flashcards JSON file (e.g., flashcards.json) according to the format above.
  2.	Run the quiz script:
