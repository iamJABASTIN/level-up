# 🎓 Academic Hub — AI-Powered Student Portfolio Platform

![Stack](https://img.shields.io/badge/stack-MERN-green)

![Home screen](./client/src/assets/Screenshot%202025-11-25%20120706.png)

> **A centralized academic portfolio system that helps students track achievements effortlessly and receive AI-driven career guidance.**

---

## 📖 Table of Contents
- [Overview](#-overview)
- [Key Features](#-key-features)
- [Tech Stack](#-tech-stack)
- [System Architecture](#-system-architecture)
- [Installation & Setup](#-installation--setup)
- [Environment Variables](#-environment-variables)
- [Usage](#-usage)
- [Future Improvements](#-future-improvements)
- [Contact](#-contact)

---

## 🧐 Overview

**The Problem:** Students often struggle to manage and present their various achievements (certifications, hackathons, projects) in a single, cohesive place. Furthermore, they rarely receive personalized feedback or guidance based on their specific activity history.

**The Solution:** **Academic Hub** is a comprehensive platform that allows students to upload and manage their academic and extracurricular portfolio. Integrated with the **ChatGPT API**, the system analyzes the student's data to provide personalized career suggestions, skill gap analysis, and actionable recommendations.

---

## ✨ Key Features

* **🗂 Centralized Portfolio Management:**
    * Upload and organize Certifications, Event participations, Projects, and Coding Profiles.
    * CRUD operations for all achievement types.
* **🤖 AI-Powered Guidance:**
    * Integrates **OpenAI's ChatGPT API** to analyze the user's portfolio.
    * Provides personalized suggestions for projects to build, skills to learn, and certifications to acquire based on current progress.
* **📊 Visual Dashboards:**
    * Interactive charts and graphs to visualize academic progress and consistency.
* **👤 Student Profile:**
    * Showcase coding profiles (LeetCode, GitHub, etc.) alongside academic achievements.

---

## 🛠 Tech Stack

| Component | Technology |
| :--- | :--- |
| **Frontend** | React.js, Tailwind CSS |
| **Backend** | Node.js, Express.js |
| **Database** | MongoDB |
| **AI Integration** | OpenAI API (ChatGPT) |
| **Authentication** | JWT (JSON Web Tokens) |
| **Version Control** | Git & GitHub |

---

## 🏗 System Architecture


1.  **Client:** React application handles the UI and displays dashboards.
2.  **Server:** Express.js server handles API requests and business logic.
3.  **Database:** MongoDB stores user profiles, achievements, and logs.
4.  **AI Engine:** The backend sends sanitized user data prompts to the OpenAI API and retrieves career advice.

---

## 🚀 Installation & Setup

Follow these steps to run the project locally.

### Prerequisites
* Node.js (v14 or higher)
* MongoDB (Local or Atlas URI)
* An OpenAI API Key

### 1. Clone the Repository
```bash
git clone [https://github.com/your-username/academic-hub.git](https://github.com/your-username/academic-hub.git)
cd academic-hub