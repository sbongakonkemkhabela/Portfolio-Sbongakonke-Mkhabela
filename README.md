# 🎯 Smart To-Do List App

A modern, intelligent task management application with AI-powered priority sorting and built-in Pomodoro timer for enhanced productivity.

![Smart To-Do List App](![alt text](image.png))


## ✨ Features

### 🧠 Smart Priority System
- **Auto-Priority Calculation**: Tasks are automatically prioritized based on multiple factors
- **Deadline Detection**: Closer deadlines receive higher priority
- **Postponement Tracking**: Tasks you keep postponing move higher in priority
- **Important Tagging**: Mark critical tasks for immediate attention
- **Dynamic Sorting**: "Today's Priorities" section shows top 5 most important tasks

### ⏱️ Built-in Pomodoro Timer
- **Focus Mode**: Dedicated timer for distraction-free work
- **Customizable Duration**: Choose from 15, 25, 30, 45, or 60-minute sessions
- **Time Tracking**: Monitor total time spent on each task
- **Session Counter**: Track completed focus sessions per task
- **Completion Alerts**: Sound notifications, visual popups, and device vibration

### 📊 Statistics Dashboard
- **Today's Focus Time**: Track your daily productivity
- **Weekly Overview**: Monitor your weekly focus hours
- **Completion Tracking**: See how many tasks you've completed

### 🎨 Modern UI/UX
- Clean, professional design with gradient themes
- Responsive layout for all devices
- Smooth animations and transitions
- Color-coded task categories
- Intuitive task management

## 🚀 Demo

[Live Demo](#) 

## 📸 Screenshots

### Main Dashboard
![alt text](image-1.png)

### Focus Mode
![alt text](image-2.png)

### Today's Priorities
![alt text](image-3.png)

## 🛠️ Technologies Used

- **HTML5**: Semantic markup structure
- **CSS3**: Modern styling with Flexbox and Grid
- **Vanilla JavaScript**: Pure JS, no frameworks
- **LocalStorage API**: Data persistence
- **Web Audio API**: Notification sounds
- **Vibration API**: Haptic feedback

## 📦 Installation

1. Clone the repository:
```bash
git clone https://github.com/sbongakonkemkhabela/smart-todo-list.git
```

2. Navigate to the project directory:
```bash
cd smart-todo-list
```

3. Open `index.html` in your browser:
```bash
open index.html
# or
start index.html  # Windows
```

That's it! No build process or dependencies required.

## 💡 Usage

### Adding a Task
1. Fill in the task title (required)
2. Optionally set a deadline for auto-priority
3. Choose a category (Work, Personal, Urgent, Study)
4. Add a description if needed
5. Check "Mark as Important" for high-priority tasks
6. Click "Add Task"

### Using Focus Mode
1. Click the 🎯 icon on any task
2. Select your preferred focus duration
3. Click "Start" to begin the timer
4. Stay focused until the timer completes
5. Receive notification when session ends

### Task Management
- ✓ **Complete**: Mark tasks as done
- 🎯 **Focus**: Enter focus mode for the task
- 🗑️ **Delete**: Remove task permanently

### Filtering Tasks
- Use category filters to view specific task types
- View all tasks or filter by Work, Personal, Urgent, or Study

## 🎯 Smart Priority Algorithm

Tasks are automatically scored based on:

| Factor | Points | Description |
|--------|--------|-------------|
| Important Flag | +50 | Tasks marked as important |
| Overdue | +100 | Past deadline |
| Due in 24h | +80 | Deadline within 24 hours |
| Due in 48h | +60 | Deadline within 48 hours |
| Due in 1 week | +40 | Deadline within 7 days |
| Future Deadline | +20 | Deadline beyond 1 week |
| Postpone Count | +10 per | Each time you skip the task |
| Urgent Category | +30 | Tagged as urgent |

## 📱 Browser Compatibility

- ✅ Chrome 90+
- ✅ Firefox 88+
- ✅ Safari 14+
- ✅ Edge 90+
- ✅ Opera 76+

## 🤝 Contributing

Contributions are welcome! Here's how you can help:

1. Fork the repository
2. Create a feature branch (`git checkout -b feature/AmazingFeature`)
3. Commit your changes (`git commit -m 'Add some AmazingFeature'`)
4. Push to the branch (`git push origin feature/AmazingFeature`)
5. Open a Pull Request

## 📝 Future Enhancements

- [ ] Task categories customization
- [ ] Recurring tasks
- [ ] Task notes and attachments
- [ ] Export/Import tasks (JSON)
- [ ] Dark mode toggle
- [ ] Multiple priority views
- [ ] Task templates
- [ ] Collaboration features
- [ ] Calendar integration
- [ ] Mobile app version

## 📄 License

This project is licensed under the MIT License - see the [LICENSE](LICENSE) file for details.

## 👨‍💻 Author

**Your Name**
- GitHub: [@sbongakonkemkhabela](https://github.com/sbongakonkemkhabela)
- LinkedIn: [Sbongakonke Mkhabela](https://linkedin.com/in/sbongakonkemkhabela)


## 🙏 Acknowledgments

- Inspiration from Pomodoro Technique by Francesco Cirillo
- Modern UI design trends from Dribbble and Behance
- Icon concepts from various open-source projects

## 📞 Support

If you encounter any issues or have questions:
- Open an [Issue](https://github.com/sbongakonkemkhabela/smart-todo-list/issues)
- Contact me via email: mkhabelafefe@gmail.com

---

⭐ Star this repository if you find it helpful!