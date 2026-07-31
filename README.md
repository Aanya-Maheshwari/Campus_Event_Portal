# Campus Event & Workshop Portal 🎓

A centralized web application designed for college students to discover, filter, and register for campus workshops, hackathons, and cultural events.

---

## 📌 Project Overview
In many university campuses, event information is scattered across messaging groups, social media stories, and physical notice boards. Students frequently miss registration deadlines due to fragmented communication. 

The **Campus Event & Workshop Portal** solves this issue by bringing all upcoming campus events into a single, clean, and intuitive interface.

---

## ✨ Key Features
- **Responsive Event Grid Layout:** Displays dynamic event cards showcasing event banners, host clubs, dates, venues, and live seat counts.
- **Dynamic Search & Category Filter:** Real-time search bar and filter buttons (*Tech, Design, Cultural, Hackathons*) using JavaScript array methods (`filter()`, `includes()`).
- **Interactive Event Detail Modal:** Pop-up window to view full event schedules, speaker profiles, and prerequisites without leaving the page.
- **Multi-Step Registration Form:** Online form with client-side validation for student name, roll number, and academic branch.
- **LocalStorage Persistence:** Saves student registrations in browser `localStorage` so data remains saved across browser refreshes.

---

## 🛠️ Tech Stack & Concepts Applied
- **HTML5:** Semantic layout structuring (`<header>`, `<main>`, `<section>`, `<article>`).
- **CSS3:** Custom variables (theming), CSS Grid, Flexbox, Glassmorphism, and hover animations.
- **JavaScript (ES6+):** Dynamic DOM manipulation, event handling, array processing, and LocalStorage API.

---

## 📁 Project Structure
```text
campus-event-portal/
├── index.html           # Main HTML structure, layout container, and modals
├── styles.css           # Custom CSS variables, responsive grid, and card styling
├── script.js            # Dynamic card rendering, search/filter logic handling
└── README.md            # Project description and documentation
