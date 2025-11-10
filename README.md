# 💰 Expense Tracker

**Personal Expense Tracker with CI/CD - Assignment 11 SESD**

## 📋 Project Overview

This project is a web-based expense tracker application that allows users to manage their personal expenses with an intuitive interface. The project demonstrates CI/CD practices using GitHub and GitHub Pages for automatic deployment.

## 🎯 Assignment Details

- **Course**: Software Engineering and System Design (SESD)
- **Assignment**: Assignment 11/12 - Tuesday: Expense Tracker Web App with Automated Testing
- **Academic Year**: 2025-26
- **Course Code**: 23CS201PC302

## ✨ Features

### Version 1.0 - Basic
- Add expense name and amount
- View list of all expenses
- Automatic total calculation
- Clean and responsive UI

### Version 2.0 - Advanced
- **Expense Categories**: Food, Transport, Entertainment, Bills, Shopping, Health, Other
- **Chart.js Integration**: Visual doughnut chart showing expense distribution by category
- **Category Breakdown**: Detailed statistics with percentages for each category
- **Responsive Design**: Two-column grid layout that adapts to different screen sizes

## 🧪 Testing

### Unit Tests Included (tests.html)
- ✅ **Total Calculation Tests**: Empty array, single expense, multiple expenses, decimal values
- ✅ **Expense Name Validation**: Valid names, empty strings, whitespace, non-string values
- ✅ **Expense Amount Validation**: Valid amounts, zero, negative numbers, NaN, string values
- ✅ **Combined Validation**: Testing both name and amount validation together
- **Total**: 16 comprehensive unit tests
- **Test Framework**: Custom-built with assert() and assertEquals() functions
- **Visual Results**: Pass/fail indicators with summary statistics

## 🚀 Live Demo

**Main Application**: [https://2303a52496.github.io/expense-tracker/](https://2303a52496.github.io/expense-tracker/)

**Unit Tests**: [https://2303a52496.github.io/expense-tracker/tests.html](https://2303a52496.github.io/expense-tracker/tests.html)

## 📁 Project Structure

```
expense-tracker/
├── index.html          # Main expense tracker application (Version 2.0)
├── tests.html          # Unit tests with visual results
└── README.md           # Project documentation
```

## 🔄 CI/CD Workflow

### Development Workflow

1. **Version Control**: All code is managed using Git
2. **Commits**: Each iteration (Version 1, Version 2, Tests) committed separately with descriptive messages
3. **GitHub Repository**: Central code repository at `github.com/2303A52496/expense-tracker`
4. **Continuous Deployment**: Automatically deploys to GitHub Pages on every push to main branch

### Deployment Process

1. **Push to GitHub**: Code changes pushed to main branch
   ```bash
   git add .
   git commit -m "commit message"
   git push origin main
   ```

2. **GitHub Actions**: Automatically triggered on push
3. **Build**: GitHub Pages builds the site
4. **Deploy**: Site deployed to `https://2303a52496.github.io/expense-tracker/`
5. **Live**: Changes are live within seconds

## 💻 Technologies Used

- **HTML5**: Structure and markup
- **CSS3**: Styling with gradients, flexbox, and grid layout
- **JavaScript (ES6)**: Application logic and DOM manipulation
- **Chart.js**: Data visualization library for doughnut charts
- **GitHub Pages**: Static site hosting and CI/CD
- **Git**: Version control

## 📊 Commit History

1. **Initial commit** - Repository setup
2. **Add Version 1: Basic Expense Tracker** - Basic functionality with expense list and total
3. **Add Version 2: Advanced Features with Categories and Charts** - Added categories and Chart.js visualization
4. **Add Unit Tests for Expense Tracker** - Comprehensive test suite with 16 tests

## 🎓 Learning Outcomes

✅ **CI/CD Pipeline Understanding**: Automated workflow from code commit to deployment

✅ **Version Control**: Effective use of Git and GitHub for project management

✅ **Testing**: Importance of unit tests for code reliability

✅ **Web Development**: Building responsive and interactive web applications

✅ **DevOps Practices**: Continuous integration and deployment in real-world scenarios

## 👨‍💻 Developer

**Student ID**: 2303A52496

**Course**: B.Tech CSE, SR University

**Instructor**: Dr. C. Madan Kumar

---

*This project demonstrates understanding of CI/CD practices, automated testing, and modern web development techniques as part of the Software Engineering and System Design course.*
