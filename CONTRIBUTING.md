# Contributing to Smart To-Do List App

First off, thank you for considering contributing to Smart To-Do List App! It's people like you that make this project better for everyone.

## 🤝 How Can I Contribute?

### Reporting Bugs

Before creating bug reports, please check the existing issues to avoid duplicates. When creating a bug report, include as many details as possible:

- **Use a clear and descriptive title**
- **Describe the exact steps to reproduce the problem**
- **Provide specific examples** to demonstrate the steps
- **Describe the behavior you observed** and what you expected to see
- **Include screenshots** if applicable
- **Note your browser and version**

### Suggesting Enhancements

Enhancement suggestions are tracked as GitHub issues. When creating an enhancement suggestion:

- **Use a clear and descriptive title**
- **Provide a detailed description** of the suggested enhancement
- **Explain why this enhancement would be useful**
- **List any alternative solutions** you've considered

### Pull Requests

1. **Fork the repository** and create your branch from `main`
2. **Make your changes** following the coding standards below
3. **Test your changes** thoroughly
4. **Update documentation** if needed
5. **Commit your changes** with clear, descriptive commit messages
6. **Push to your fork** and submit a pull request

## 📝 Coding Standards

### HTML
- Use semantic HTML5 elements
- Keep proper indentation (2 spaces)
- Add comments for complex sections
- Ensure accessibility with proper ARIA labels

### CSS
- Follow the existing naming conventions
- Keep selectors specific but not overly complex
- Comment complex CSS rules
- Maintain consistent spacing and formatting
- Use CSS variables for repeated values

### JavaScript
- Use ES6+ features where appropriate
- Follow camelCase naming convention
- Add JSDoc comments for functions
- Keep functions small and focused
- Handle errors appropriately
- Use meaningful variable names

### Example:
```javascript
/**
 * Calculate priority score for a task
 * @param {Object} task - The task object
 * @returns {number} Priority score
 */
function calculatePriority(task) {
    let score = 0;
    // Implementation
    return score;
}
```

## 🔍 Code Review Process

1. All pull requests require review before merging
2. Reviewers will check for:
   - Code quality and standards compliance
   - Functionality and bug fixes
   - Documentation updates
   - Test coverage (if applicable)

## 🎯 Development Setup

1. Fork and clone the repository
```bash
git clone https://github.com/sbongakonkemkhabela/smart-todo-list.git
cd smart-todo-list
```

2. Create a new branch
```bash
git checkout -b feature/your-feature-name
```

3. Make your changes and test locally

4. Commit your changes
```bash
git add .
git commit -m "Add: Brief description of your changes"
```

5. Push to your fork
```bash
git push origin feature/your-feature-name
```

6. Open a Pull Request

## 📋 Commit Message Guidelines

Use clear and meaningful commit messages:

- **Add:** New feature or functionality
- **Fix:** Bug fix
- **Update:** Changes to existing features
- **Remove:** Removing features or files
- **Refactor:** Code refactoring
- **Docs:** Documentation changes
- **Style:** Formatting, missing semicolons, etc.

Examples:
```
Add: Keyboard shortcuts for task management
Fix: Timer not resetting after session completion
Update: Improve priority calculation algorithm
Docs: Add installation instructions to README
```

## 🐛 Testing

Before submitting a pull request:

1. Test all functionality manually
2. Check browser compatibility (Chrome, Firefox, Safari, Edge)
3. Test responsive design on different screen sizes
4. Verify localStorage persistence works correctly
5. Test the Pomodoro timer thoroughly

## 📚 Additional Resources

- [Project README](README.md)
- [Issue Tracker](https://github.com/sbongakonkemkhabela/smart-todo-list/issues)
- [Pull Requests](https://github.com/sbongakonkemkhabela/smart-todo-list/pulls)

## ❓ Questions?

Feel free to open an issue with the "question" label if you need clarification on anything.

## 📜 Code of Conduct

- Be respectful and inclusive
- Welcome newcomers
- Focus on what's best for the community
- Show empathy towards others

Thank you for contributing! 🎉