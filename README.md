# Quiz App

This is a simple and interactive quiz application built with React. The app presents a set of multiple-choice questions to the user and allows them to select their answers. Upon submission, the app provides the user with their score.

## Features

- Multiple-choice questions with radio buttons for selecting answers.
- Option to select answers by clicking on the text of the options.
- Displays the score once the user completes all questions.
- Smooth UI with 3D effects and animations.

## Technologies Used

- **React**: Frontend library for building the user interface.
- **CSS**: Custom styles for the UI, including 3D effects and animations.
- **Bootstrap**: Used for basic layout and responsive design.

## Setup Instructions

### Prerequisites
Ensure you have the following installed on your system:
- **npm** (Node package manager)

### Installation

1. Clone the repository:
   ```bash
   git clone https://github.com/your-username/quiz-app.git
   cd quiz-app
   ```

2. Install dependencies:
   ```bash
   npm install
   ```

3. Start the development server:
   ```bash
   npm start
   ```

   This will run the app in development mode, and you can access it at `http://localhost:3000` in your browser.

### Running the App

Once the app is running, you can:
1. Answer the quiz questions.
2. Click on any option to select it.
3. Submit your answers to view your score.

## Project Structure

- **`App.js`**: Main component that holds the state of the app and handles logic for the quiz.
- **`Question.js`**: Displays the current question and the options for the user to choose from.
- **`Options.js`**: Contains the options (radio buttons) for each question.
- **`Score.js`**: Displays the score after all questions are answered.
- **`questionBank.js`**: Holds the question data used by the app.

## Styling

- The app uses custom CSS with 3D effects and animations to make the user interface more engaging.
- The background includes a 3D parallax effect for a dynamic look.
- The radio buttons and buttons have hover and active effects to make interactions visually appealing.

## Future Enhancements

- Add more questions and categories.
- Allow users to retake the quiz.
- Store the quiz results locally or in a backend database.
- Add a timer for each question.
