# 🎮 Study RPG Syllabus Tracker

A gamified study tracker that transforms learning into an RPG experience! Track your progress through JEE/NEET syllabus with XP points, levels, and competitive features.

## ✨ Features

- **🎯 RPG-Style Progress Tracking**: Earn XP and level up as you complete study tasks
- **⚔️ Dual-Player System**: Track progress for two study partners with competitive leaderboard
- **📚 Complete Syllabus Coverage**: 
  - Physics (Class 11 & 12)
  - Chemistry (Class 11 & 12)
  - Mathematics (Class 11 & 12)
  - Computer Science (Class 12)
  - English (Class 12)
- **🏆 Task Categories**:
  - Topic Concept (10 XP)
  - NCERT Exercises (30 XP)
  - PYQ Conquest (50 XP)
  - Chapter Legend (100 XP)
- **💪 Behemoth Chapters**: Tough chapters award 1.5x XP
- **💾 Auto-Save**: Progress automatically saved to browser localStorage
- **🎨 Beautiful UI**: Dark theme with gradient effects and smooth animations
- **📱 Mobile Responsive**: Works seamlessly on all devices
- **🎆 Level-Up Animations**: Celebrate achievements with visual effects

## 🚀 Quick Start

### Option 1: GitHub Pages (Recommended)

1. **Fork or Clone this repository**
   ```bash
   git clone https://github.com/YOUR_USERNAME/study-rpg-tracker.git
   cd study-rpg-tracker
   ```

2. **Enable GitHub Pages**
   - Go to repository Settings
   - Navigate to Pages section
   - Select `main` branch as source
   - Click Save

3. **Access your app**
   - Visit: `https://YOUR_USERNAME.github.io/study-rpg-tracker/`

### Option 2: Run Locally

1. **Download the repository**
   ```bash
   git clone https://github.com/YOUR_USERNAME/study-rpg-tracker.git
   ```

2. **Open in browser**
   - Simply open `index.html` in any modern web browser
   - No server or installation required!

## 🔐 Login Credentials

- **Username**: `partnerA` or `partnerB`
- **Password**: `study123`

> **Note**: Change credentials in the code for production use!

## 📖 How to Use

1. **Login** with your username and password
2. **Select a Subject** from the tabs (Physics, Chemistry, etc.)
3. **Expand Chapters** to view tasks
4. **Check Tasks** to earn XP and level up!
5. **Track Progress** on the dashboard
6. **Compete** with your study partner

## 🎮 XP System

### Task XP Values
- **Topic Concept**: 10 XP
- **NCERT Exercises**: 30 XP  
- **PYQ Conquest**: 50 XP
- **Chapter Legend**: 100 XP

### Behemoth Chapters (1.5x XP)
Challenging chapters that award bonus XP:
- Rotational Motion
- Electric Charges & Fields
- Current Electricity
- Chemical Bonding
- And more...

### Level Progression
- Level 1: 0 XP
- Level 2: 300 XP
- Level 3: 750 XP
- Level 4: 1,500 XP
- ... up to Level 20!

## 🛠️ Technical Details

### Technologies Used
- Pure HTML5
- CSS3 (Grid, Flexbox, Animations)
- Vanilla JavaScript (ES6+)
- localStorage API for data persistence

### Browser Support
- Chrome/Edge (recommended)
- Firefox
- Safari
- Any modern browser with localStorage support

### Data Storage
All progress is saved locally in your browser using localStorage. Data persists across sessions but is device-specific.

## 🎨 Customization

### Change Credentials
Edit the `USERS` object in `index.html`:
```javascript
const USERS = {
    partnerA: { password: 'your_password', name: 'Your Name' },
    partnerB: { password: 'your_password', name: 'Partner Name' }
};
```

### Add More Subjects
Add to the `CHAPTERS` object:
```javascript
newSubject: {
    class11: [
        { name: "Chapter Name", desc: "Description", behemoth: false }
    ]
}
```

### Modify XP Values
Edit the `TASK_XP` object:
```javascript
const TASK_XP = {
    concept: 10,
    ncert: 30,
    pyq: 50,
    legend: 100
};
```

## 📱 Mobile Experience

The app is fully responsive and optimized for mobile devices:
- Touch-friendly interface
- Adaptive layouts
- Smooth scrolling
- Full functionality on all screen sizes

## 🔒 Privacy

- No data is sent to any server
- All progress stored locally in browser
- No analytics or tracking
- Works completely offline after first load

## 🤝 Contributing

Contributions are welcome! Here's how:

1. Fork the repository
2. Create a feature branch (`git checkout -b feature/AmazingFeature`)
3. Commit changes (`git commit -m 'Add AmazingFeature'`)
4. Push to branch (`git push origin feature/AmazingFeature`)
5. Open a Pull Request

## 📝 License

This project is licensed under the MIT License - see the [LICENSE](LICENSE) file for details.

## 🐛 Known Issues

- Data is device-specific (doesn't sync across devices)
- Browser cache clearing will reset progress
- No data export/import feature (yet!)

## 🚀 Future Enhancements

- [ ] Cloud sync for cross-device progress
- [ ] Export/Import progress data
- [ ] Dark/Light theme toggle
- [ ] More subjects and syllabi
- [ ] Achievement badges
- [ ] Study streak tracking
- [ ] Time tracking per chapter
- [ ] Study statistics and analytics

## 💡 Tips

1. **Backup Your Progress**: Export localStorage data regularly
2. **Use Same Browser**: Progress is browser-specific
3. **Set Goals**: Try to complete one chapter per day
4. **Compete**: Challenge your partner to stay motivated!

## 📞 Support

Found a bug or have a suggestion?
- Open an [Issue](https://github.com/YOUR_USERNAME/study-rpg-tracker/issues)
- Submit a Pull Request
- Contact the developer

## 🌟 Acknowledgments

- Designed for JEE/NEET aspirants
- Inspired by RPG game mechanics
- Built with ❤️ for students

---

**Made with 🎮 for students who love gaming and learning!**

## 🎯 Pro Tips for Maximum XP

1. Start with easier chapters to build momentum
2. Complete all tasks in Behemoth chapters for maximum XP
3. Use the competitive leaderboard to stay motivated
4. Celebrate your level-ups!
5. Review completed chapters periodically

Happy Studying! 🚀📚