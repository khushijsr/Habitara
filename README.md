##Habitara – AI-Powered Habit Tracker

Habitara is a multi-page AI-powered habit tracking web app built with Python, Streamlit, and SQLite. It helps users build and maintain habits with a professional dashboard, AI insights, reminders, and progress tracking.

✨ Features
🔑 Authentication

User login and new account creation

Credentials and data securely stored in SQLite

🏠 Dashboard

Sidebar navigation with icons and labels (SaaS-style)

Smooth multi-page navigation

📋 Habits Management

Add, edit, and delete habits

Predefined categories: Learning, Saving, Health, Fitness, Productivity, Mindfulness, Reading, Social, Custom

Linked to each logged-in user

✅ Tracking

Daily, Weekly, and Monthly habit checklists

Save progress (SQLite storage) or Reset responses

Proper checklist format for usability

📊 Progress Analytics

Visualizations using Plotly/Matplotlib

Charts: Line, Bar, Pie

Metrics: Daily completions, streaks, success rate, summaries

Export data as CSV

🤖 AI Insights

Monthly analysis with risk levels: High, Medium, Low

Personalized AI-based suggestions

Badges for milestones and streaks

⚙️ Settings

Profile: Edit username, upload/reset profile picture

Theme: Dark/Light mode with slider toggle

Language: English / Hindi (auto-translate UI)

Privacy & notifications (future-ready placeholders)

Reset all settings to default

🔔 Notifications

Pop-up reminders for incomplete habits

(Optional) Scheduled notifications

🎨 Design & UX

Professional SaaS layout

Responsive for desktop & mobile

Sidebar with icons + labels

Color scheme: Blue, Green, White with highlights

🛠️ Tech Stack

Frontend & UI: Streamlit (Python-based), HTML, CSS

Database: SQLite

Data Visualization: Plotly, Matplotlib

AI Insights: Rule-based / LLM-powered analysis

🚀 Installation & Setup

Clone this repository

git clone https://github.com/khushijsr/Habitara.git
cd Habitara


Create a virtual environment & activate it

python -m venv venv
source venv/bin/activate    # Mac/Linux
venv\\Scripts\\activate     # Windows


Install dependencies

pip install -r requirements.txt


Run the app

streamlit run app.py


Open in browser at:
👉[ http://localhost:8501](https://habitara-habit-angle.my.canva.site/)

📂 Project Structure
Habitara/
│── app.py              # Main Streamlit app
│── database.db         # SQLite database
│── requirements.txt    # Python dependencies
│── assets/             # Images, logo, profile pictures
│── README.md           # Project documentation

📊 Future Enhancements

Push notifications (email/WhatsApp)

AI-powered adaptive habit suggestions

Cloud database support (PostgreSQL/Firebase)

Mobile app integration (React Native/Flutter frontend)
