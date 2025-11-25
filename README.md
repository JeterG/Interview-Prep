

## 📚 Contents

- **index.html** - Main landing page with navigation to all resources
- **interview_crash_course.html** - Quick reference with all technical Q&A
- **csharp_basics.html** - C# fundamentals crash course
- **javascript_basics.html** - JavaScript basics for Electron development
- **java_basics.html** - Java fundamentals and OOP concepts
- **Study_Guide.html** - Comprehensive study guide (Part 1)
- **Study_guide_2.html** - Advanced topics study guide (Part 2)
- **GUI_interview_crash_course.html** - GUI-specific interview preparation

## 🚀 Deploy to GitHub Pages

### Option 1: Using GitHub Web Interface

1. Create a new repository on GitHub (e.g., `interview-study-guide`)
2. Upload all HTML files to the repository
3. Go to Settings → Pages
4. Under "Source", select "Deploy from a branch"
5. Select "main" branch and "/" (root) folder
6. Click Save
7. Your site will be live at: `https://yourusername.github.io/interview-study-guide/`

### Option 2: Using Git Command Line

```bash
# Create a new repository on GitHub first, then:
git init
git add .
git commit -m "Initial commit: Interview study guide website"
git branch -M main
git remote add origin https://github.com/yourusername/interview-study-guide.git
git push -u origin main

# Enable GitHub Pages
# Go to Settings → Pages → Source → main → / (root) → Save
```

### Option 3: Quick Deploy with GitHub CLI

```bash
gh repo create interview-study-guide --public --source=. --remote=origin --push
# Then enable Pages in Settings
```

## 📖 How to Use

1. Open `index.html` as your starting point
2. Navigate through different sections using the navigation bar
3. Study guides are organized by topic and difficulty
4. Use the crash courses for quick syntax review before interviews

## 🎯 Study Strategy

### Week Before Interview
- **Day 1-2:** C# Basics and JavaScript Basics (required for role)
- **Day 3-4:** Interview Crash Course + coding practice
- **Day 5:** Study Guides 1 & 2 for comprehensive coverage
- **Day 6:** GUI Interview Guide and system design
- **Day 7:** Review weak areas and practice mock interviews

### Day Before Interview
- Review Interview Crash Course
- Practice 5-10 coding problems
- Read through your resume and prepare stories
- Review questions to ask them

## 🔗 Local Testing

To test locally before deploying:

```bash
# Option 1: Python
python -m http.server 8000

# Option 2: Node.js
npx http-server

# Then visit: http://localhost:8000
```

## ✨ Features

- Responsive design (works on mobile/tablet/desktop)
- Dark theme optimized for coding
- Code syntax highlighting
- Copy buttons for all code blocks
- Quick navigation between topics
- Comparison tables (Python vs C# vs JavaScript vs Java)

## 📝 Notes

- All pages are static HTML - no server required
- No external dependencies - works offline after downloading
- Optimized for GitHub Pages hosting
- Mobile-friendly responsive design

## 🎓 Interview Prep Checklist

- [ ] Review C# basics syntax
- [ ] Practice JavaScript async/await
- [ ] Solve 10+ LeetCode medium problems
- [ ] Review data structures (arrays, hashmaps, trees, linked lists)
- [ ] Practice explaining your resume projects
- [ ] Prepare questions to ask interviewer
- [ ] Study GUI development patterns
- [ ] Review system design basics
- [ ] Practice whiteboard coding
- [ ] Mock interview with friend/mentor

## 🤝 Good Luck!

Remember:
- They're looking for learning ability, not just existing C# knowledge
- Emphasize your strong backend foundation and quick learning
- Connect your Python/API experience to GUI development needs
- Show enthusiasm for medical device software and quality practices

---

**Created for:** Jeter Gutierrez  
**Position:** GUI Software Engineer @ Soterix Medical  
**Date:** November 2024
