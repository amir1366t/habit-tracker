# Habit Tracker

A powerful and intuitive habit tracking application to help you build better habits, stay consistent, and achieve your goals.

## Features

- ✅ **Track Daily Habits** - Monitor your daily habits with ease
- 📊 **Progress Visualization** - View your habit streaks and completion rates
- 📈 **Analytics** - Get insights into your habit patterns
- 🎯 **Goal Setting** - Set and track personal goals
- 🔔 **Reminders** - Get notified to complete your habits
- 💾 **Data Persistence** - All your data is saved locally
- 🎨 **Beautiful UI** - Clean and intuitive interface

## Quick Start

### Installation

```bash
# Clone the repository
git clone https://github.com/amir1366t/habit-tracker.git

# Navigate to the project directory
cd habit-tracker

# Install dependencies
npm install
```

### Usage

```bash
# Start the development server
npm start

# Build for production
npm run build
```

## Project Structure

```
habit-tracker/
├── src/
│   ├── components/      # React components
│   ├── pages/          # Page components
│   ├── hooks/          # Custom React hooks
│   ├── utils/          # Utility functions
│   ├── styles/         # CSS and styling
│   └── App.jsx         # Main App component
├── public/             # Static assets
├── package.json        # Project dependencies
└── README.md          # This file
```

## Technologies Used

- **Frontend**: React.js
- **Styling**: CSS / Tailwind CSS (optional)
- **State Management**: React Hooks / Context API
- **Storage**: Local Storage
- **Build Tool**: Vite / Create React App

## Key Features Explained

### 1. Daily Habit Tracking
- Add, edit, and delete habits
- Mark habits as completed each day
- Track completion history

### 2. Streak Calculation
- Automatic streak counting
- Best streak tracking
- Consistency visualization

### 3. Analytics Dashboard
- Weekly/Monthly progress charts
- Habit completion rates
- Habit statistics and insights

### 4. Local Data Storage
- All data stored in browser's Local Storage
- No backend required
- Automatic data synchronization

### 5. Reminder Notifications
- Desktop notifications
- Scheduled reminders
- Customizable notification times

## Getting Started with Development

### Prerequisites
- Node.js (v14.0 or higher)
- npm or yarn

### Installation Steps

1. **Clone the repository**
   ```bash
   git clone https://github.com/amir1366t/habit-tracker.git
   cd habit-tracker
   ```

2. **Install dependencies**
   ```bash
   npm install
   ```

3. **Start development server**
   ```bash
   npm start
   ```

4. **Open in browser**
   Navigate to `http://localhost:3000`

### Building for Production

```bash
npm run build
```

The optimized build will be created in the `build/` directory.

## API Reference

### Habit Management

#### Create Habit
```javascript
const newHabit = {
  id: uniqueId(),
  name: "Morning Workout",
  description: "30 minutes exercise",
  frequency: "daily",
  createdAt: new Date(),
  completedDates: []
};
```

#### Update Habit Completion
```javascript
habit.completedDates.push(new Date().toISOString());
```

#### Delete Habit
```javascript
habits = habits.filter(h => h.id !== habitId);
```

## Contributing

We welcome contributions! Here's how you can help:

1. Fork the repository
2. Create a feature branch (`git checkout -b feature/amazing-feature`)
3. Commit your changes (`git commit -m 'Add amazing feature'`)
4. Push to the branch (`git push origin feature/amazing-feature`)
5. Open a Pull Request

### Code Style
- Use ES6+ syntax
- Follow React best practices
- Write meaningful commit messages
- Add comments for complex logic

## Roadmap

- [ ] User authentication system
- [ ] Backend integration (Node.js/Express)
- [ ] Database storage (MongoDB/PostgreSQL)
- [ ] Mobile app (React Native)
- [ ] Dark mode support
- [ ] Social features (share progress)
- [ ] Export data as PDF
- [ ] Advanced analytics

## License

This project is licensed under the MIT License - see the [LICENSE](LICENSE) file for details.

## Support

For support, email us at support@habittracker.com or open an issue on GitHub.

## Authors

- **Amir** - Initial work - [amir1366t](https://github.com/amir1366t)

## Acknowledgments

- Thanks to all contributors
- Inspired by popular habit tracking applications
- Community feedback and suggestions

## Change Log

### Version 1.0.0
- Initial release
- Core habit tracking features
- Local storage implementation

---

**Last Updated**: July 2026

Happy Habit Tracking! 🚀
