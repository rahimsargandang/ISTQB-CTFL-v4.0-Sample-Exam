# ISTQB CTFL v4.0 Practice Exam

A web-based practice exam application for the **ISTQB Certified Tester Foundation Level (CTFL) v4.0** certification. Built with React and Vite, featuring 240 questions across 6 exam sets with detailed per-option explanations.

## About

This app helps aspiring ISTQB CTFL candidates prepare for the certification exam by providing an interactive, timed-exam-like experience. All questions, answers, and explanations are cross-checked verbatim against the official ISTQB and ASTQB sample exam PDFs to ensure accuracy.

The pass mark is **65%** (26 out of 40 questions), matching the real ISTQB CTFL exam.

## Exam Sets & Source PDFs

Each exam set contains **40 questions** sourced from official ISTQB/ASTQB sample exam documents compatible with **Syllabus v4.0**.

| Exam Set | Source PDF (Questions) | Source PDF (Answers) |
|----------|----------------------|---------------------|
| **Set A** | ISTQB CTFL v4.0 Sample Exam A – Questions | ISTQB CTFL v4.0 Sample Exam A – Answers |
| **Set B** | ISTQB CTFL v4.0 Sample Exam B – Questions | ISTQB CTFL v4.0 Sample Exam B – Answers |
| **Set C** | ISTQB CTFL v4.0 Sample Exam C – Questions | ISTQB CTFL v4.0 Sample Exam C – Answers |
| **Set D** | ISTQB CTFL v4.0 Sample Exam D – Questions | ISTQB CTFL v4.0 Sample Exam D – Answers |
| **Set E** | CTFL 4.0 Sample Exam 3-2 – Questions (ASTQB) | CTFL 4.0 Sample Exam 3-2 – Answers (ASTQB) |
| **Set F** | CTFL 4.0 Sample Exam 4-3 – Questions (ASTQB) | CTFL 4.0 Sample Exam 4-3 – Answers (ASTQB) |

- **Sets A–D** are from the official ISTQB sample exams
- **Sets E–F** are from the American Software Testing Qualifications Board (ASTQB) sample exams
- All questions, options, diagrams, tables, and explanations have been verified against the original PDFs

## Features

### Two Study Modes
- **Practice Mode** — No time limit. Get instant feedback and detailed explanations after each question. Perfect for learning and understanding concepts.
- **Exam Mode (60 min)** — Timed like the real ISTQB exam. No feedback until you finish. You can change answers anytime. Auto-submits when time runs out. Timer turns red at 5 minutes remaining.

### Exam Experience
- **240 total questions** across 6 exam sets (40 questions each)
- **Question navigation** — jump to any question via the numbered grid at the top
- **Progress tracking** — progress bar shows how many questions have been answered
- **Finish anytime** — the Finish Exam button is always available between Previous and Next buttons
- **Unanswered questions** are marked as incorrect when you finish

### Explanations
- **Per-option rationale** for every question, matching the official ISTQB/ASTQB answer PDFs verbatim
- **Bold correct answer** — the correct answer's explanation is highlighted in bold for quick identification
- **Diagrams and tables** — decision tables, control flow graphs, state transition diagrams, and other visual elements rendered inline

### Results & Review
- **Score summary** with percentage, pass/fail status, and correct/wrong breakdown
- **Review all questions** after completing an exam — see your answer, the correct answer, and the full explanation
- **Download PDF** — export your exam results as a PDF file with score summary and per-question breakdown

### Score History
- **Automatic tracking** — every exam attempt is saved with date, score, percentage, and pass/fail status
- **Best score per set** — badges on the home page show your highest score for each attempted exam set
- **Full history table** — view all past attempts sorted by most recent
- **Clear history** — reset your score history with a confirmation prompt
- **Persistent storage** — history is saved in localStorage and survives browser restarts

### Theme & Responsiveness
- **Dark/Light mode** — toggle between dark and light themes; preference is saved in localStorage
- **Mobile responsive** — tables and diagrams scroll horizontally on small screens; navigation buttons and option cards adapt to narrow viewports
- **Smooth transitions** — fade animations between screens
- **Hover effects** — interactive buttons with color fills and lift animations for better UX

## Getting Started

### Prerequisites
- Node.js (v16 or higher)
- npm

### Installation

```bash
# Clone the repository
git clone https://github.com/rahimsargandang/ISTQB-CTFL-v4.0-Sample-Exam.git

# Navigate to the project directory
cd ISTQB-CTFL-v4.0-Sample-Exam

# Install dependencies
npm install

# Start the development server
npm run dev
```

### Build for Production

```bash
npm run build
npm run preview
```

## Tech Stack

- **React** — UI framework
- **Vite** — Build tool and dev server
- **jsPDF** + **jspdf-autotable** — PDF export
- **localStorage** — Theme preference and score history persistence

## Disclaimer

This application is intended for educational and exam preparation purposes only. All questions and answers are sourced from publicly available ISTQB and ASTQB sample exam documents. ISTQB is a registered trademark of the International Software Testing Qualifications Board.

## License

This project is for personal use and exam preparation. Please refer to the ISTQB copyright notice regarding the use of their sample exam materials.
