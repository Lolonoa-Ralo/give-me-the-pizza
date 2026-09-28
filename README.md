<p align="right">
  <strong>English</strong> | <a href="README_KR.md">한국어</a>
</p>

# 🍕 Give Me The Pizza - Code Lounge

> **"Ready to collaborate? All you need is a 6-digit code."**  
> A lightweight, aesthetic, and interactive sticky note board platform that lets you create instant shared spaces and exchange ideas without the friction of sign-ups.

[![Live Demo](https://img.shields.io/badge/Live_Demo-GitHub_Pages-2bb379?style=for-the-badge&logo=github)](https://lolonoa-ralo.github.io/give-me-the-pizza/)
[![Vanilla JS](https://img.shields.io/badge/Vanilla-HTML5%20%2F%20CSS3%20%2F%20JS-F7DF1E?style=for-the-badge&logo=javascript&logoColor=black)](#-tech-stack)

---

## 🌐 Live Demo
Experience the platform instantly in your browser without any installation:  
👉 **[https://lolonoa-ralo.github.io/give-me-the-pizza/](https://lolonoa-ralo.github.io/give-me-the-pizza/)**

---

## ✨ Key Features

### 🔑 1. Frictionless 6-Digit Entry Code System
* **No Account Required**: Create and enter rooms immediately using simple 6-digit random codes—no tedious registration or sign-in flows.
* **Dual Permission Model**: Automatically generates both a **Standard Entry Code** (to invite peers) and an **Admin Code** (for host management).

### 📌 2. Interactive Sticky Board
* **Intuitive Note Cards**: Post memos, brainstormed ideas, to-do lists, and greetings as modern cards on a collaborative canvas.
* **One-Click Copy**: Quickly copy any note's text content straight to your clipboard with a single click.
* **Instant Keyword Search**: Filter and locate specific cards on the board in real time as more notes accumulate.
* **Edit & Remove**: Easily refine sticker content or clean up expired notes.

### 👑 3. Host Administration & Control
* **Rotate Entry Code**: Instantly generate a new entry code if the current code is leaked or needs refreshing.
* **Safe Room Deletion**: Completely terminate the room and clear all data with safety confirmation (`삭제하겠습니다` / verification prompt).

### 🎨 4. Refined UX & Design
* **Light / Dark Mode**: Toggle smoothly between clean daylight and easy-on-the-eyes dark themes.
* **Built-in Internationalization (i18n)**: Seamless bilingual support for both Korean (KO) and English (EN).
* **Responsive Layout**: Designed to provide an optimal experience across mobile, tablet, and desktop viewports.

---

## 🚀 Quick Start Guide

Built purely with **Vanilla Web Technologies**—no build tools, bundlers, or package managers required.

### Option A: Open Directly
Clone or download the repository, then double-click `index.html` to open it directly in any modern browser.

### Option B: Run a Local Static Server
```bash
# Using Python 3 built-in static HTTP server
python -m http.server 8000
```
Then visit `http://localhost:8000` in your web browser.

---

## 📖 How to Use

1. **Create a Space (Host)**
   - Click **"무작위 코드 만들기" (Generate Random Code)** on the lounge screen.
   - Note down the generated codes and share the general code with your friends or teammates.
2. **Join a Space (Participants)**
   - Click **"코드 입력하기" (Enter Code)**, enter the 6-digit code and a display nickname.
3. **Collaborate with Stickers**
   - Click the **`+` (Add Sticker)** button on the top toolbar to post thoughts and interact with participants.

---

## 🛠️ Tech Stack

* **Markup**: HTML5 (Accessible, semantic layout)
* **Styling**: Pure Vanilla CSS3 (Custom CSS Properties, Flexbox/Grid, Glassmorphism, Theme Switcher)
* **Scripting**: Pure Vanilla JavaScript (Modern ES6+, Zero external dependencies)
* **Deployment**: GitHub Pages

---

## 📂 Repository Structure

```text
give-me-the-pizza-main/
├── favicon.png       # Web app favicon
├── index.html        # Monolithic SPA frontend (UI, styling, and logic included)
├── README.md         # English documentation (Default display)
└── README_KR.md      # Korean documentation
```

---

## 🍕 Associated Project: PizzaC2
The entry code and sticker board architecture from this project also serves as the trusted relay channel for **[PizzaC2](https://github.com/lolonoa-ralo/Pizza-C2)**, a Living Off Trusted Sites (LOTS) Proof-of-Concept Command & Control framework.