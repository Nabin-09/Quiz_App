# Quiz App

A lightweight and interactive trivia application built with vanilla JavaScript, HTML, and CSS. Test your knowledge with randomly selected questions and track your score.

## 🔗 Live Demo

Check out the live version of the Quiz App here: [Quiz App Live Demo](https://nabin-09.github.io/Quiz_App/)

![Quiz App Screenshot](https://github.com/Nabin-09/Quiz_App/blob/main/Images/Sample.png)

## ✨ Features

- Random selection of questions from a larger question bank
- Multiple-choice questions with immediate feedback
- Score tracking system
- Responsive design for all device sizes
- Clean and intuitive user interface
- Visual feedback for correct and incorrect answers

## 🛠️ Technologies Used

- **HTML5** - Semantic markup for structure
- **CSS3** - Custom styling with animations and responsive design
- **JavaScript** - Vanilla JS for all functionality (no frameworks or libraries)

## 🧩 Technical Implementation

### JavaScript Architecture

The Quiz App employs a modular JavaScript approach with the following key components:

#### Key Functions

| Function | Description |
|----------|-------------|
| `StartQuiz()` | Initializes the quiz by resetting score, shuffling questions, and selecting 5 random questions from the pool |
| `showQuestion()` | Renders the current question and its answers to the DOM |
| `resetState()` | Clears previous question state and resets UI elements |
| `selectAnswer(e)` | Handles user answer selection, applies styling for correct/incorrect answers, and updates score |
| `showscore()` | Displays the final score when all questions are answered |
| `handleNextButton()` | Manages navigation to the next question or score display |

#### Program Flow

1. Quiz initialization with random question selection
2. Question rendering with multiple-choice options
3. User interaction and immediate feedback
4. Score tracking throughout the quiz session
5. Quiz completion with final score display
6. Option to restart the quiz

### File Structure

```
Quiz_App/
│
├── index.html         # Main HTML structure
├── style.css          # CSS styling and animations
├── script.js          # Quiz logic and functionality
```

## 📋 How to Use

1. Visit the [live demo](https://nabin-09.github.io/Quiz_App/) or clone the repository
2. Click on your answer choice for each question
3. See immediate feedback on your selection
4. Click "Next" to proceed to the next question
5. View your final score after completing all questions
6. Click "Play Again" to restart with a new set of random questions

## 🚀 Local Development

To run this project locally:

```bash
# Clone the repository
git clone https://github.com/Nabin-09/Quiz_App.git

# Navigate to the project directory
cd Quiz_App

# Open in your preferred browser
open index.html
```

No build tools or dependencies required!

## 🧠 Adding New Questions

To expand the question bank, edit the `questions.js` file and add new question objects following this format:

```javascript
{
    question: "Your question text here?",
    answers: [
        { text: "Option 1", correct: false },
        { text: "Option 2", correct: false },
        { text: "Correct Answer", correct: true },
        { text: "Option 4", correct: false },
    ]
}
```

## 🔧 Future Improvements

- Add difficulty levels
- Implement timer functionality
- Create category selection
- Add sound effects for correct/incorrect answers
- Implement persistent high scores using local storage

## 👨‍💻 About the Developer

This project was developed by [Nabin](https://github.com/Nabin-09). Check out more of my projects on my [GitHub profile](https://github.com/Nabin-09).

## 📝 License

MIT License

Copyright (c) 2025 Nabin

Permission is hereby granted, free of charge, to any person obtaining a copy
of this software and associated documentation files (the "Software"), to deal
in the Software without restriction, including without limitation the rights
to use, copy, modify, merge, publish, distribute, sublicense, and/or sell
copies of the Software, and to permit persons to whom the Software is
furnished to do so, subject to the following conditions:

The above copyright notice and this permission notice shall be included in all
copies or substantial portions of the Software.

THE SOFTWARE IS PROVIDED "AS IS", WITHOUT WARRANTY OF ANY KIND, EXPRESS OR
IMPLIED, INCLUDING BUT NOT LIMITED TO THE WARRANTIES OF MERCHANTABILITY,
FITNESS FOR A PARTICULAR PURPOSE AND NONINFRINGEMENT. IN NO EVENT SHALL THE
AUTHORS OR COPYRIGHT HOLDERS BE LIABLE FOR ANY CLAIM, DAMAGES OR OTHER
LIABILITY, WHETHER IN AN ACTION OF CONTRACT, TORT OR OTHERWISE, ARISING FROM,
OUT OF OR IN CONNECTION WITH THE SOFTWARE OR THE USE OR OTHER DEALINGS IN THE
SOFTWARE.
