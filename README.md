# SonakshiTestResult
Static web app to manage and display Sonakshi test results with question/answer images.
# SonakshiTestResult

A simple and responsive **static test result dashboard** to track daily test scores, questions, and answers — built using **HTML**, **CSS**, **JavaScript**, and **Bootstrap**.

## 📌 Features

- 🗓️ Date-wise test history tracking
- ✅ Displays correct and incorrect answers
- 🖼️ Upload and preview question and answer images
- 📱 Fully responsive for mobile and desktop
- 🔍 Filter by subject
- 📝 Form to generate test entry objects for static inclusion

✅ What goes in which file?
| File Name             | Purpose                                                                |
| --------------------- | ---------------------------------------------------------------------- |
| `index.html`          | Dashboard summary cards (Registered Students, Results, Subjects, etc.) |
| `average-marks.html`  | Subject-wise average marks viewer (7, 14, 28 days + custom range)      |
| `tests.html`          | Test history table with subject, date, marks, correct/incorrect, etc.  |
| `test-details.html`   | Shows question & answer images for a specific test date                |
| `css/style.css`       | Optional custom styles for colors, spacing, shadows                    |
| `js/average-marks.js` | JS logic for averages, filtering by subject and date range             |
| `images/2025-07-16/`  | Folder for question/answer images for that date                        |

## 📁 Folder Structure
SonakshiTestResult/
│
├── index.html              → Dashboard home (summary cards)
├── average-marks.html      → Subject-wise average marks (with dropdown, date filters)
├── tests.html              → Daily test history table
├── test-details.html       → View questions & answers (images) for one test
├── css/
│   └── style.css           → Custom styles (optional)
├── js/
│   └── average-marks.js    → Script for subject average marks logic
├── images/
│   └── (date-wise folders or images for questions/answers)

