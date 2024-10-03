# Quiz App

A simple Quiz App built with vanilla JavaScript that dynamically fetches questions from a public API and presents them in a multiple-choice format. Users have 30 seconds to answer each question, and they can only select an answer after the first 10 seconds. At the end of the quiz, the results will be displayed in a table format showing the user's answers for each question.

## Features

- The quiz consists of 10 questions fetched from [JSONPlaceholder API](https://jsonplaceholder.typicode.com/posts).
- Each question has 4 answer options (A-B-C-D), dynamically generated from the question's content.
- Users cannot click on the answers during the first 10 seconds of each question.
- Each question is automatically moved to the next one after 30 seconds.
- Users cannot return to previous questions.
- A table of results is shown at the end of the quiz with each question and the user's selected answer.

## Installation

1. Clone this repository to your local machine.

```bash
git clone https://github.com/yourusername/quiz-app.git
```

2. Install the necessary dependencies:
   ```bash
   npm install
   ```

To run your project in development mode, use the following command:
   ```bash
   npm install
   ```

Open your browser and visit the following URL:
http://localhost:8080
