# Student Council Election System

A secure, logic-driven web application built to manage school-wide elections. This system was designed for the 2025-26 academic year to digitize the entire election process from candidate setup to result computation.

## 🚀 Project Overview
This platform handles two distinct voting workflows:
* **Class Representative (CR) Elections:** Secure teacher login to configure class-specific ballots (Stream, Standard, Division) for male and female candidates.
* **Core Council Elections:** A dedicated flow for school-wide positions like General Secretary and Cultural Secretary.

## 🧠 Development Approach
* **System Architecture:** Designed the core logic flow, data state management, and security gates (including password-protected result viewing).
* **AI Integration:** Leveraged AI coding assistants to accelerate UI boilerplate generation and CSS styling, allowing focus on core JavaScript election logic and functional integration.

## ⚙️ Key Features
* **Dynamic Ballot Setup:** Teachers can dynamically generate inputs for any number of candidates.
* **State Management:** Tracks active voting sessions, prevents duplicate submissions, and stores total vote counts locally.
* **Visual Analytics:** Integrates `Chart.js` to automatically render interactive pie charts of the final vote distributions.
* **Data Export:** Built-in functionality to download final election results directly to a CSV file for administrative record-keeping.

## 🛠️ Tech Stack
* **Frontend:** HTML5, CSS3, Vanilla JavaScript
* **Data Management:** Browser LocalStorage API
* **Libraries:** Chart.js (Data Visualization)
