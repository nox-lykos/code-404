# code-404
# 🤖 Intelligent Rubrics-Based Evaluator (Hackathon Project)

**Challenge:** SI no. 19 - Intelligent Rubrics-Based Evaluator for Flowcharts, Algorithms, and Pseudocode (Digital Products Domain)

## 💡 Idea and Uniqueness

This project solves the critical problem of **slow, inconsistent, and delayed grading** for conceptual assignments like pseudocode.

Our solution is a unique, full-featured tutoring platform defined by its **multimodal intelligence** and **actionable feedback loop**:

1. **Multimodal AI Input:** We use the **Gemini Vision API** to accurately read and extract code from **uploaded images (photos, PDFs)**, eliminating the barrier of manual text entry.

2. **Integrated AI Correction:** Beyond just scoring, we use a second **Gemini API call** to analyze the user's biggest error and instantly generate a **corrected, clean block of pseudocode**, providing immediate, expert-level remediation.

3. **Full-Stack Persistence:** The application uses **Firebase Firestore** for anonymous user authentication and persistent history management, allowing students to save, rename, and review their past evaluations.

## ✨ Features

* **Multimodal Input:** Evaluate pseudocode pasted directly or extracted from uploaded images/documents (PNG, JPG, PDF).

* **Three Algorithms:** Supports detailed evaluation for Factorial, Find Max Value in Array, and Bubble Sort.

* **Dual Feedback System:**

  * **Live Linting:** Provides instant, basic syntax feedback as the user types.

  * **AI Correction:** Generates a corrected code block upon submission for major errors.

* **Rubrics-Based Scoring:** Grades submissions objectively on **Correctness, Efficiency, and Style**.

* **Dark Mode UI:** Features a high-contrast dark theme for improved ergonomics and aesthetic appeal.

* **Data Persistence:** Saves evaluation scores, code, and feedback history to **Firebase Firestore**. Users can view, rename, and delete past sessions.
