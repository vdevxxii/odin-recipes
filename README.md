# odin-recipes

A small multi-page HTML site built as part of a deliberate practice routine.
The goal wasn’t complexity — it was discipline: clean structure, clear markup, consistent formatting, correct relative paths, and an atomic Git workflow.
The project showcases three Mexican recipes—Cochinita Pibil, Chiles en Nogada, and Tamales—each written and structured directly in HTML.

📍 Live Demo: https://vdevxxii.github.io/odin-recipes/

## 📌 Objective

• Build a multi-page site using only fundamental HTML tools.
• Maintain a clean folder structure and correct relative navigation.
• Improve clarity, grammar, and descriptive writing directly in HTML.
• Practice a consistent Git workflow with atomic, meaningful commits.

## 📚 Background

This project is part of my Foundations practice through The Odin Project.
Rather than copying templates, I focused on writing structured pages from scratch and reinforcing HTML fundamentals.

Odin Project:
https://www.theodinproject.com/paths/foundations/courses/foundations

Recipes lesson:
https://www.theodinproject.com/lessons/foundations-recipes

## 🛠️  Technologies Used

• HTML5
• Git & GitHub
• VS Code

## 🔥 Lesson Learned

Working on this project helped reinforce:

• Why relative paths matter
• How to structure folders intentionally
• Writing clear and descriptive HTML content
• Committing in small, focused steps

A single mistake — using ./images/... instead of ../images/... — broke image loading and forced me to re-understand directory navigation.
Small bug, big lesson.

## 🚧 Challenges & Solutions

# Relative Paths

Incorrect path:

# ./images/cochinitapibil.png

Correct path:

# ../images/cochinitapibil.png

Understanding when to “step out” of a folder (..) is essential for scalable file structures.

## 🧪 Git Workflow 

git clone git@github.com:USER-NAME/REPOSITORY-NAME.git
git status
git add .
git commit
git push origin main

## 📂 File Structure

odin-recipes/
│
├── index.html
│
├── recipes/
│   ├── chiles-en-nogada.html
│   ├── cochinita-pibil.html
│   └── tamales.html
│
└── images/
    ├── chiles-en-nogada.png
    ├── cochinitapibil.png
    └── tamal.png

## ✔️ Result

A clean, organized HTML project demonstrating fundamentals and correct file handling.



