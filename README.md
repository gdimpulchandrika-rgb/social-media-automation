# AI Social Media Content Automation System using n8n

## 📌 Project Overview

This project is a low-code AI-powered social media automation system built using n8n. The workflow automates social media content generation, data management, and real-time notifications using AI and cloud technologies.

The project integrates AI APIs, Google Sheets, Telegram, PostgreSQL, Docker, and Render cloud deployment into a single automated workflow.

---

# 🚀 Features

- AI-generated social media content
- Automated workflow execution
- Google Sheets integration
- Telegram notifications
- Low-code workflow automation
- Cloud deployment support
- PostgreSQL database integration
- Docker-based deployment

---

# 🛠️ Technologies Used

| Technology | Purpose |
|------------|---------|
| n8n | Workflow automation |
| Groq AI | AI content generation |
| Google Sheets | Data storage |
| Telegram | Notifications |
| Docker | Containerization |
| PostgreSQL | Database |
| Render | Cloud deployment |

---

# 📌 Workflow Architecture

```text
Schedule Trigger
        ↓
HTTP Request to AI API
        ↓
Groq Chat Model
        ↓
Edit & Format Data
        ↓
Store in Google Sheets
        ↓
Decision Making (IF Node)
        ↓
Telegram Notification

📂 Workflow Explanation
The workflow starts automatically using a Schedule Trigger.
An HTTP Request sends prompts to the AI API.
Groq Chat Model generates social media content.
The generated content is formatted and processed.
Data is stored in Google Sheets.
IF node adds decision-making logic.
Telegram sends real-time notifications.

🎯 Objectives
Automate social media content generation
Reduce manual work
Improve productivity
Integrate multiple services into one workflow
Enable cloud-based automation
Demonstrate AI-powered workflow systems

📊 Key Insights
Automation reduces repetitive tasks.
AI speeds up content generation.
Low-code platforms simplify workflow development.
Cloud deployment improves accessibility.
Integrated workflows improve efficiency.

⚠️ Challenges Faced
Docker deployment setup
PostgreSQL SSL/TLS configuration
Environment variable management
Database connectivity issues
Cloud deployment troubleshooting

📈 Results
Automated social media content generation
Faster workflow execution
Reduced manual effort
Real-time notification system
Scalable cloud-hosted solution

☁️ Deployment

The project is deployed using:

Docker
Render
PostgreSQL database integration

🔐 Environment Variables
DB_TYPE=postgresdb
DB_POSTGRESDB_HOST=your-render-db-host
DB_POSTGRESDB_PORT=5432
DB_POSTGRESDB_DATABASE=your_database
DB_POSTGRESDB_USER=your_user
DB_POSTGRESDB_PASSWORD=your_password
DB_POSTGRESDB_SSL=true

N8N_BASIC_AUTH_ACTIVE=true
N8N_BASIC_AUTH_USER=admin
N8N_BASIC_AUTH_PASSWORD=your_password

WEBHOOK_URL=https://your-app.onrender.com

▶️ Run Locally

Clone Repository
git clone <your-repository-url>
cd <project-folder>

Run with Docker
docker build -t n8n-social-automation .
docker run -p 5678:5678 n8n-social-automation

📌 Future Enhancements
Multi-platform social media posting
AI image generation
Analytics dashboard
Scheduled publishing
Multi-user support

📖 Conclusion

This project demonstrates how AI and low-code workflow automation can simplify social media management by reducing manual work, improving productivity, and enabling scalable cloud-based automation.

👩‍💻 Author

Gudapati Dimpul Chandrika
