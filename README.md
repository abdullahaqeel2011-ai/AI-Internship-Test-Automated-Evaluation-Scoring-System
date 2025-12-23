# AI-Internship-Test-Automated-Evaluation-Scoring-System
🚀 AI Internship Test – Automated Evaluation & Scoring System

An end-to-end automation workflow built with n8n that manages the complete lifecycle of an internship assessment — from form submission to automated scoring, Google Sheets synchronization, and instant personalized email notifications.

This project is designed to eliminate manual evaluation, reduce human error, and scale seamlessly for internship programs, hiring tests, and online assessments.

🎯 Key Features

✅ Fully automated test evaluation
✅ Real-time scoring using JavaScript logic
✅ Google Sheets integration for structured data storage
✅ Duplicate-safe score updates using email as a unique identifier
✅ Personalized email notifications via Gmail API
✅ Scalable and production-ready workflow

🔄 Workflow Overview (Step-by-Step)
📝 1. Form Submission Trigger

• Candidates submit the AI Internship Test form
• Captures name, email, and 20 MCQ responses
• Acts as the entry point for the automation

📊 2. Response Storage (Google Sheets)

• Automatically appends candidate responses
• Maintains a clean, structured, and auditable record
• Enables easy tracking and reporting

🧠 3. Automated Scoring Logic (JavaScript)

• Validates answers against predefined correct responses
• Supports checkbox and multi-select questions
• Normalizes input to avoid formatting mismatches
• Calculates total score dynamically (out of 20)

📈 4. Score Management (Append or Update)

• Stores results in a dedicated Scores sheet
• Uses email as a unique key
• Prevents duplicate entries
• Updates existing candidate scores automatically

📧 5. Personalized Email Notification

• Sends an instant email to each candidate
• Includes candidate name and final score
• Fully automated — no manual follow-up required

🛠️ Tech Stack

• n8n – Workflow Automation
• JavaScript – Scoring & validation logic
• Google Forms – Test data collection
• Google Sheets – Data storage & reporting
• Gmail API – Automated email delivery

📌 Use Cases

✔ Internship & hiring assessments
✔ Candidate screening automation
✔ Online quizzes and evaluations
✔ HR and recruitment workflows
✔ Educational testing systems

📈 Benefits

🚀 Saves significant manual effort
🎯 Ensures accurate and consistent evaluation
🔁 Prevents duplicate processing
📬 Provides instant candidate feedback
📊 Centralizes assessment data

🧩 Future Enhancements

• Pass / Fail email logic
• Automated certificate generation
• Leaderboard and analytics dashboard
• Admin alerts for top candidates
• API-based webhook integration

📄 License

This project is licensed for both educational and commercial use.

You are permitted to:

Use, modify, and deploy this workflow in personal, educational, or commercial projects

Customize the logic for client-specific requirements

Restrictions:

Reselling the workflow as-is without modification is not permitted

Author attribution must be retained in derivative works

👤 Author

Abdullah Aqeel

AI Automation Engineer | Software Quality Assurance Engineer (SQAE)
