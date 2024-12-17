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
```


## Functional Requirements

1. **Load Questions**:
   - The script should load questions from the JSON file at the start.

2. **Randomize Questions**:
   - Shuffle the order of the questions every time the quiz runs.

3. **Randomize Options**:
   - Shuffle the options for each question.

4. **Display Questions**:
   - Present one question at a time with options numbered (e.g., 1, 2, 3, 4).

5. **Take User Input**:
   - Accept input corresponding to the option number (e.g., 1, 2, etc.).
   - Validate the input to ensure it matches available options.

6. **Track Score**:
   - Keep a tally of correct answers.
   - Show the score after all questions are answered.

7. **Optional Features**:
   - Allow users to select a category (e.g., Math, Science) to filter questions.
   - Implement a time limit for each question.
   - Add a "skip" option that moves the question to the end of the quiz.
