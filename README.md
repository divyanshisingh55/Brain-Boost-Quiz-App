Brain Boost Quiz App
Overview
Brain Boost is an interactive quiz application built with React that challenges users with questions across multiple knowledge domains. The app features a clean, modern UI with engaging animations and a timed quiz experience.
Features

Multiple Knowledge Domains: Test your knowledge in General Knowledge, Science, Technology, Entertainment, and Trivia
Timed Questions: Each question has a 45-second timer to add challenge
Interactive UI: Engaging animations and visual feedback make learning fun
Progress Tracking: See your score and detailed results at the end of each quiz
Responsive Design: Works on desktop and mobile devices

Technology Stack

React (Hooks-based)
Tailwind CSS for styling
Custom animations

Installation and Setup

Clone the repository:
git clone https://github.com/yourusername/brain-boost-quiz.git

Navigate to the project directory:
cd brain-boost-quiz

Install dependencies:
npm install

Start the development server:
npm start

Open your browser and navigate to http://localhost:3000

Usage

Enter your name on the welcome screen
Select a knowledge domain
Answer each question within the time limit
View your results at the end of the quiz
Choose to try a different domain or restart the quiz

Customization
You can easily add more questions or domains by modifying the quizByDomain object in the code. Each question requires:

A unique ID
The question text
An array of options
The correct answer (which must match one of the options exactly)

Future Enhancements

User accounts and persistent scores
Difficulty levels
More extensive question database
Multiplayer mode
Achievements and badges
