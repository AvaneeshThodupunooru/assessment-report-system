# 🧠 Assessment Report Generation System

A full-stack web application designed to automate psychological assessment report generation based on standardized test inputs.

---

## 🚀 Overview

This system allows professionals to:
- Input patient details
- Enter test scores (Verbal & Performance)
- Automatically calculate TQ Scores and IQ
- Generate structured reports (Preview + Download)

---

## 🏗️ Tech Stack

### Frontend
- React (Vite)
- Tailwind CSS
- React Hook Form

### Backend
- Node.js
- Express.js
- REST API

---

## ✨ Features

### 📋 Patient Information
- Personal details form
- Informant selection
- School selection with "Other" option

### 🧪 Test Information
- Multiple standardized tests:
  - MISIC
  - WISC
  - WAIS
  - BKT
  - CAS
- Dynamic "Other Test" input

### 🧠 Verbal Assessment
- Inputs:
  - Information
  - Comprehension
  - Arithmetic
  - Similarities
  - Vocabulary / Digit Span (selectable)
- Automatic:
  - TQ score calculation
  - Average VIQ

### ⚙️ Performance Assessment
- Inputs:
  - Picture Completion
  - Block Design
  - Object Assembly
  - Coding
  - Mazes
- Automatic:
  - TQ score calculation
  - Average PIQ

### 📊 Final Output
- Total Scores
- VIQ, PIQ, Final IQ
- Report generation:
  - 📄 Preview (HTML)
  - ⬇️ Download (PDF)

---

## 🖥️ How to Run the Project

### 1️⃣ Clone the repository
```bash
git clone https://github.com/YOUR_USERNAME/assessment-report-system.git
cd assessment-report-system
