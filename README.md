# 📅 Smart Habit Tracker

A comprehensive habit tracking system built with Python, showcasing advanced Object-Oriented Programming concepts. Track your goals, maintain daily streaks, and build better habits!

## 📖 About

Smart Habit Tracker is an educational project that demonstrates OOP principles through a practical habit tracking application. Built for Google Colab, this virtual planner helps you:

- 🎯 **Create Goals** - Set up custom habits and track them
- 📊 **Track Progress** - Monitor daily completion rates
- 🔥 **Build Streaks** - Maintain consecutive days of completion
- 📈 **View Statistics** - Analyze your habit patterns
- 🏆 **Earn Achievements** - Get rewarded for consistency

## 🚀 Getting Started

### Prerequisites

- A Google account to access Google Colab
- Basic understanding of Python (helpful but not required!)

### How to Run

1. Open the notebook in Google Colab:
   - Click on `SmartHabitTracker.ipynb` in this repository
   - Click the "Open in Colab" badge at the top of the notebook
   
2. Run all cells sequentially by clicking `Runtime > Run all`

3. Follow the interactive prompts to start tracking your habits!

## 🎓 Learning Objectives

This project demonstrates:

- **Classes and Objects**: Multiple interacting classes (Habit, HabitTracker, Statistics)
- **Methods**: Instance methods, class methods, and helper methods
- **Attributes**: Managing complex state across multiple objects
- **Encapsulation**: Organizing related functionality into cohesive classes
- **Data Persistence**: Storing and retrieving habit data
- **Date/Time Handling**: Working with Python's datetime module

## ✨ Features

### Habit Management
- Create unlimited custom habits
- Set different frequencies (daily, weekly)
- Add descriptions and categories
- Archive or delete habits

### Tracking System
- Mark habits as complete for the day
- Automatic streak calculation
- Miss tracking with streak reset
- Historical completion data

### Analytics Dashboard
- View all habits at a glance
- Individual habit statistics
- Overall completion rates
- Best streaks and achievements
- Calendar view of completions

### Motivation Features
- Streak milestones (3, 7, 30, 100 days)
- Motivational messages
- Progress percentages
- Visual progress indicators

## 📂 Project Structure

```
SmartHabitTracker/
│
├── SmartHabitTracker.ipynb    # Main Google Colab notebook
├── README.md                   # Project documentation
├── LICENSE                     # MIT License
├── .gitignore                 # Git ignore file
└── examples/                  # Example screenshots (optional)
```

## 💡 Usage Examples

```python
# Create a new habit tracker
tracker = HabitTracker()

# Add a new habit
tracker.add_habit("Morning Exercise", "Health", "Daily routine workout")

# Mark habit as complete
tracker.complete_habit("Morning Exercise")

# View your dashboard
tracker.view_dashboard()

# Check statistics
tracker.view_statistics()
```

## 🎯 Sample Habits to Track

- 💪 Exercise routines
- 📚 Reading daily
- 💧 Water intake
- 🧘 Meditation practice
- 💻 Coding practice
- 🌱 Learning a new language
- 📝 Journaling
- 🛏️ Sleep schedule

## 🤝 Contributing

This is an educational project, but improvements are welcome! Feel free to:

1. Fork the repository
2. Create a feature branch (`git checkout -b feature/NewFeature`)
3. Commit your changes (`git commit -m 'Add NewFeature'`)
4. Push to the branch (`git push origin feature/NewFeature`)
5. Open a Pull Request

## 🔮 Future Enhancements

- Export data to CSV
- Habit reminders and notifications
- Habit chains visualization
- Social features (share progress)
- Weekly/monthly reports
- Habit difficulty levels
- Custom streak recovery options

## 📝 License

This project is licensed under the MIT License - see the [LICENSE](LICENSE) file for details.

## 🙏 Acknowledgments

- Created as an educational project to demonstrate OOP concepts
- Inspired by popular habit tracking apps like Habitica and Streaks

## 📧 Contact

Have questions or suggestions? Feel free to open an issue in this repository!

---

**Build Better Habits, One Day at a Time! 🌟**
