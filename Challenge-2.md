# Challenge-2

## Problem
Create a Python script that generates random quizzes from a pool of questions stored in a file.

## Key Features
- Randomize questions and options.
- Track the user's score.

## Detailed Requirements for the Quiz Generator

### Objective
Develop a Python script that generates random quizzes from a pool of questions stored in a file. The app will randomize the order of questions and their options, take user responses, and track the score.

### Input File Format
- **File Type**: JSON (preferred for structured data).
- **Structure**:
  - Each question should include:
    - The question text.
    - A list of possible options.
    - The correct answer(s).
    - An optional category for filtering (e.g., Math, Science, etc.).

#### Example JSON Structure
```json
[
  {
    "question": "What is the capital of France?",
    "options": ["Berlin", "Madrid", "Paris", "Rome"],
    "answer": "Paris",
    "category": "Geography"
  },
  {
    "question": "Which planet is known as the Red Planet?",
    "options": ["Earth", "Mars", "Venus", "Jupiter"],
    "answer": "Mars",
    "category": "Science"
  }
]
