# 🔍 GitHub Finder

A modern, high-performance GitHub user search application built as part of a professional web development workshop. This project demonstrates advanced **React** patterns, **TypeScript** integration, and efficient data fetching using **TanStack Query**.

## 🚀 Key Features

* **Real-time Search:** Instantly fetch and display GitHub user profiles using the official REST API.
* **Search Suggestions:** Dynamic dropdown with suggestions as you type, optimized with **Debouncing** to reduce API overhead.
* **Persistent Search History:** A "Recent Searches" list with local persistence (`LocalStorage`) to maintain history across sessions.
* **Performance Optimization:** Implements **Prefetching** on hover to deliver near-instant results and a seamless user experience.
* **Type Safety:** Developed with 100% **TypeScript**, ensuring robust code and structured data models.
* **Modern UI:** A clean, responsive interface with real-time feedback for loading and error states.

## 🛠️ Tech Stack & Skills

* **Framework:** React 18
* **Language:** TypeScript
* **State Management & Data Fetching:** [TanStack Query](https://tanstack.com/query/latest) (React Query)
* **Optimization:** `use-debounce` for input handling
* **Icons:** React Icons (Font Awesome)
* **Styling:** CSS3 (Responsive Design)

## 💡 Learning Outcomes

Through this project, I implemented several advanced frontend concepts:
* **Custom Hook Integration:** Efficiently managing asynchronous states (loading, error, data).
* **Advanced State Logic:** Creating a unique search history (no duplicates, auto-limiting to the last 5 entries).
* **Caching Strategies:** Leveraging React Query for automatic caching and manual cache invalidation (`refetch`).
* **Deployment & Build:** Resolving complex TypeScript compilation errors to ensure a clean production build.

---

### 🎓 Acknowledgments
This project was developed as part of the **"Modern React from the Beginning"** course by **Brad Traversy** on **Udemy**.
