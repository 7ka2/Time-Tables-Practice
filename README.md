🧠 Times Tables Practice App
This is a simple, single-page, static web application designed to help users practice their multiplication tables interactively. It features adjustable difficulty and an AI-powered Math Explainer for educational context.

This application is entirely self-contained within a single HTML file and requires no backend server or database (like Firebase) to run.

✨ Features
Customizable Practice: Select which multiplication tables (1-12) you want to practice.

Difficulty Modes:

Simple: Multiple-choice format with 3 options.

Normal: Type the answer manually for a greater challenge.

Session Scoring: Track your score for the current practice session.

Gemini Math Explainer: Access a context-aware AI tutor that provides fun, simple explanations of the current times table being asked. (Requires a valid Gemini API key to function).

🚀 How to Play
Select Tables: On the initial screen, check the boxes for the tables you want to focus on (e.g., 6, 7, and 8).

Choose Difficulty: Select between 'Simple' (multiple choice) or 'Normal' (type answer).

Start Practice! Click the green 'Start Practice!' button.

Answer Questions: Input your answer or select the correct option.

View Score: Your session score is updated in real-time.

Need Help? Click the "✨ Explain the Tables!" button to get a simple, friendly explanation of the current table from the Gemini AI.

🛠️ Deployment and Setup
This is a static site, making deployment straightforward:

Clone/Download this repository.

Ensure the file is named index.html.

Host on GitHub Pages: Use the GitHub Pages feature (found in the repository settings) to deploy the index.html file from the main branch's root directory.

API Key: The Gemini Explainer feature requires a Gemini API key to be set within the <script> block in the index.html file where GEMINI_API_KEY = "" is defined.

🔗 Live Demo
Once deployed to GitHub Pages, the app will be accessible at:
https://[Your-Username].github.io/[Your-Repository-Name]/

