El-Amel – AI Appointment Booking (n8n)
Overview
This project is an n8n automation workflow that uses an AI Agent to manage appointment bookings for El-Amel.

The AI assistant:

Welcomes patients politely
Collects full name, phone number, and visit day
Saves booking data to Google Sheets
Ensures the doctor does not exceed 20 appointments per day
Refuses to answer questions outside appointment booking
Technologies Used
n8n
OpenAI (Chat Model)
Google Sheets
LangChain AI Agent
Workflow Logic
A chat message is received

AI Agent responds with a welcome message

AI collects booking information:

Full name
Phone number
Visit day
AI checks daily appointment limit (20 per day)

Booking is saved to Google Sheets

Conversation remains strictly about booking only

