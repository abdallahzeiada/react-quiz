# React Quiz App

A responsive React application that tests your knowledge of React concepts through an interactive quiz experience.

## 🚀 Features

- **15 React-focused Questions**: Test your knowledge of React fundamentals and advanced concepts
- **Timer**: 30 seconds per question to challenge your speed and knowledge
- **Progress Tracking**: Visual progress bar to track your journey through the quiz
- **Point System**: Different questions have different point values based on difficulty
- **Highscore Tracking**: Save and display your best performance
- **Fully Responsive**: Works perfectly on mobile, tablet and desktop devices
- **Modern UI**: Clean and engaging user interface with smooth animations

## 🛠️ Technologies

- React 19
- React Hooks (useState, useEffect, useReducer)
- CSS3 with custom properties
- JSON Server (for development)

## 📋 Prerequisites

- Node.js (v16.0 or higher recommended)
- npm or yarn

## ⚙️ Installation & Setup

1. Install dependencies:
```bash
npm install
# or
yarn install
```

2. Start the JSON server (for local development):
```bash
npm run server
# or
yarn server
```

3. In a separate terminal, start the React application:
```bash
npm start
# or
yarn start
```

4. Open your browser and visit:
```
http://localhost:3000
```

## 🎮 How to Play

1. Click "Let's Start" on the welcome screen
2. Read each question carefully and select the answer you believe is correct
3. The timer counts down from 30 seconds for each question
4. After selecting an answer, click "Next" to proceed to the next question
5. Your score will be calculated based on correct answers
6. After completing all questions, you'll see your final score and highscore

## 📱 Responsive Design

The quiz is fully responsive and works well on:
- Mobile phones (portrait and landscape)
- Tablets
- Desktop computers

## 🎨 Customization

### Colors

You can customize the color scheme by modifying the CSS variables in `src/index.css`:

```css
:root {
  --color-darkest: #123a40;
  --color-dark: #005057;
  --color-medium: gold;
  --color-light: #fff;
  --color-theme: seagreen;
  --color-accent: orangered;
}
```

### Questions

To modify or add questions, update the `data/questions.json` file. Each question follows this format:

```json
{
  "question": "Your question text here?",
  "options": ["Option 1", "Option 2", "Option 3", "Option 4"],
  "correctOption": 0, // Index of the correct option
  "points": 10 // Points for this question
}
```

## 🙏 Acknowledgements

- [React Documentation](https://react.dev/)
- [Create React App](https://create-react-app.dev/)
- [JSON Server](https://github.com/typicode/json-server)
- [Google Fonts (Codystar)](https://fonts.google.com/specimen/Codystar)

---

Made with ❤️ by Abdallah Zeiada
