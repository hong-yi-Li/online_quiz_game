# 🧠 Online Quiz Game (在线问答小游戏)

A fun and interactive quiz game built with HTML, CSS, and JavaScript featuring 150 Chinese trivia questions.

## 🌟 Features

- **150 Unique Questions**: Comprehensive collection of trivia questions covering various topics
- **No Repeat Questions**: Smart algorithm ensures questions don't repeat until all have been shown
- **Interactive UI**: Beautiful gradient design with smooth animations and hover effects
- **Responsive Design**: Works perfectly on both desktop and mobile devices
- **Chinese Language Support**: Built with Chinese language support and cultural content
- **Score Tracking**: Track your progress through question numbers
- **Answer Reveal**: Get immediate feedback with correct answers displayed

## 🎯 How to Play

1. **Start the Game**: Click the "开始答题" (Start Quiz) button
2. **Read Questions**: Each question is displayed with 4 multiple-choice options
3. **Select Answer**: Click on your chosen option (it will be highlighted)
4. **Check Answer**: Click "显示答案" (Show Answer) to see the correct answer
5. **Continue**: Click "下一题" (Next Question) to proceed to the next question
6. **No Repeats**: Each question appears only once until all 150 questions are completed

## 🚀 Getting Started

### Prerequisites
- A modern web browser (Chrome, Firefox, Safari, Edge)
- No additional software installation required

### Installation
1. Clone or download this repository
2. Open `quiz_game.html` in your web browser
3. Start playing immediately!

### File Structure
```
online_quiz_game/
├── quiz_game.html      # Main game file (HTML + CSS + JavaScript)
├── quiz_150.csv        # Question database (150 questions)
└── README.md           # This documentation file
```

## 🎨 Technical Details

### Technologies Used
- **HTML5**: Semantic structure and content
- **CSS3**: Modern styling with gradients, animations, and responsive design
- **JavaScript (ES6+)**: Game logic and interactivity

### Key Features
- **Question Randomization**: Questions are randomly selected without repetition
- **State Management**: Tracks used questions to prevent duplicates
- **Responsive Grid**: CSS Grid layout for optimal option display
- **Smooth Transitions**: CSS transitions for enhanced user experience
- **Mobile-First Design**: Responsive breakpoints for all screen sizes

### Browser Compatibility
- Chrome 60+
- Firefox 55+
- Safari 12+
- Edge 79+

## 📱 Responsive Design

The game automatically adapts to different screen sizes:
- **Desktop**: Full-width layout with side-by-side buttons
- **Tablet**: Optimized spacing and touch-friendly elements
- **Mobile**: Stacked layout with full-width buttons

## 🎲 Question Categories

The 150 questions cover various topics including:
- Chinese history and culture
- Geography and landmarks
- Science and technology
- Literature and philosophy
- World knowledge
- Traditional customs and festivals

## 🔧 Customization

### Adding New Questions
To add more questions, modify the `quizData` array in the JavaScript section:

```javascript
const quizData = [
    {
        question: "Your question here?",
        options: ["Option A", "Option B", "Option C", "Option D"],
        answer: "B"  // A, B, C, or D
    },
    // ... more questions
];
```

### Styling Changes
Modify the CSS section to customize:
- Colors and gradients
- Fonts and typography
- Animations and transitions
- Layout and spacing

## 🐛 Troubleshooting

### Common Issues
1. **Questions not loading**: Ensure JavaScript is enabled in your browser
2. **Styling issues**: Check if CSS is properly loaded
3. **Mobile display problems**: Verify viewport meta tag is present

### Browser Support
If you experience issues, try:
- Updating your browser to the latest version
- Clearing browser cache and cookies
- Using a different browser

## 📈 Future Enhancements

Potential improvements for future versions:
- [ ] User authentication and progress saving
- [ ] Multiple difficulty levels
- [ ] Timer-based challenges
- [ ] Leaderboard system
- [ ] Question categories and filtering
- [ ] Sound effects and music
- [ ] Multi-language support
- [ ] Offline mode with service workers

## 🤝 Contributing

Contributions are welcome! Feel free to:
- Report bugs or issues
- Suggest new features
- Submit pull requests
- Improve documentation

## 📄 License

This project is open source and available under the [MIT License](LICENSE).

## 👨‍💻 Author

Created with ❤️ for educational and entertainment purposes.

## 🎉 Acknowledgments

- Inspired by traditional Chinese trivia games
- Built with modern web development best practices
- Designed for accessibility and user experience

---

**Enjoy playing the quiz game! 🎮✨** 