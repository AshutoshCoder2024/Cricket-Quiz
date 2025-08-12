## Overview

Cricket Master is a mobile-friendly, interactive cricket quiz app built with HTML, CSS, and JavaScript. It features a vast question bank, timed quizzes, instant scoring, and detailed feedback to test and improve your cricket knowledge.

---

## Features

🎯 10 random questions selected from 100+ cricket trivia
⏱️ 60-second timer with automatic submission
📊 Instant scoring showing correct and incorrect answers
🔄 Retry button to get a fresh set of questions
🏏 Questions cover history, players, World Cup, stats, and IPL
📱 Fully responsive design for all screen sizes
🎨 Clean and intuitive user interface
📝 Detailed explanations for answers

---

## Live Demo

*Add your live demo URL here (if available)*

---

## Screenshots

<img width="800" height="1000" alt="Screenshot 2025-08-13 014050" src="https://github.com/user-attachments/assets/1200141f-c183-4ae8-a9a1-ac508a74b181" />
<img width="800" height="1034" alt="Screenshot 2025-08-13 014113" src="https://github.com/user-attachments/assets/ac893f8b-0c38-4f43-9bc2-dd8d713a1daa" />
<img width="1478" height="192" alt="Screenshot 2025-08-13 014849" src="https://github.com/user-attachments/assets/fb128a68-ef9f-4577-b167-13fdca5233fc" />

---

## Tech Stack

* **HTML5:** Semantic markup for structure
* **CSS3:** Responsive styling and layout
* **JavaScript (ES6):** Quiz logic, timer, and UI interactivity
* **No external libraries:** Runs entirely in the browser

---

## Getting Started

### Prerequisites

* Modern web browser (Chrome, Firefox, Safari, Edge)
* No installation required

### Installation

1. Clone the repository:

   git clone https://github.com/AshutoshCoder2024/Cricket-Quiz

2. Navigate into the project folder:


   cd cricket-Quiz
   
4. Open `index.html` in your browser to start the quiz

### How to Use

* Read each question and select your answer
* Submit manually or let the timer auto-submit after 60 seconds
* Review your score and feedback on incorrect answers
* Click **Retry** to play again with a new set of questions

---

## Project Structure

```
cricket-Quiz/
├── index.html        # Main HTML file
├── style.css         # Styling and responsive design
├── script.js         # JavaScript quiz logic
└── README.md         # This documentation file
```

---

## Code Snippet

Random unique question selection function:

```javascript
function RandomQuestion() {
  const arr = [];
  let length = Question_Bank.length;

  for (let i = 0; i < 10; i++) {
    let index = Math.floor(Math.random() * length);
    arr.push(Question_Bank[index]);
    [Question_Bank[index], Question_Bank[length - 1]] =
      [Question_Bank[length - 1], Question_Bank[index]];
    length--;
  }
  return arr;
}
```

---

## Future Enhancements

* Difficulty levels (Beginner/Expert)
* Category-based quizzes (Batting, Bowling, History)
* High score tracking and leaderboards
* Multiplayer mode
* Enhanced UI animations

---

## Contributing

Contributions are welcome! To contribute:

1. Fork the repo
2. Create a feature branch (`git checkout -b feature-name`)
3. Commit your changes (`git commit -m 'Add feature'`)
4. Push to your branch (`git push origin feature-name`)
5. Open a Pull Request

---

