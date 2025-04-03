## CyberSecurity Awareness Quiz
Project Screenshot <!-- Add a screenshot if available -->

A web-based quiz application designed to test and improve cybersecurity awareness. This interactive quiz features user authentication, a question bank, progress tracking, and leaderboard functionality.

## Features
## User Authentication:

Secure registration with unique username, email, and mobile number requirements

Login with either username or email

Password reset with two-factor verification (email + mobile)

Quiz Functionality:

20 cybersecurity questions with detailed explanations

Random selection of 15 questions per quiz

Progress tracking during the quiz

Immediate feedback on answers

## Dashboard:

Personal statistics (quiz attempts, high score, average score)

Quiz history with detailed review

Leaderboard showing top performers

Security Features:

Password complexity requirements

Prevention of password reuse

Client-side data persistence (localStorage)

QR code sharing capability

Technologies Used
HTML5, CSS3, JavaScript

Font Awesome for icons

QRCode.js for QR code generation

localStorage for client-side data persistence

Installation
No installation required - this is a client-side web application. Simply open index.html in any modern web browser.

For development:

Clone the repository

Open index.html in your browser

Start quizzing!

Usage
Register a new account with your details

Login with your credentials

Take the quiz and test your cybersecurity knowledge

Review your results and see where you can improve

Check the leaderboard to see how you compare to others

## File Structure
Copy
cybersecurity-quiz/
├── index.html          # Main application file
├── README.md           # This documentation file
└── screenshot.png      # Optional screenshot of the application
Customization
To modify the quiz questions, edit the questionBank array in the JavaScript section of index.html. Each question should follow this format:

javascript
Copy
{
    question: "Question text?",
    options: ["Option 1", "Option 2", "Option 3"],
    answer: 0, // Index of correct answer
    explanation: "Detailed explanation of the correct answer"
}
## Limitations
This is a client-side only application - no server-side persistence

Data is stored in browser localStorage (cleared if cache is cleared)

Designed as an educational demo rather than production system

## Future Enhancements
Add more cybersecurity questions

Implement server-side persistence

Add user profiles and achievements

Include timed quizzes and different difficulty levels
