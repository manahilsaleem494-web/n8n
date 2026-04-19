# n8n Appointment System Workflow

## 📌 Project Overview
This project implements an automated Appointment System using n8n.  
The system interacts with users, checks availability in Google Calendar, schedules appointments, and stores data in Google Sheets.

---

## 🔹 Features:
- Collects user information:
  - Name
  - Mobile Number
  - Date & Time
- Checks time slot availability using Google Calendar
- Automatically creates an event if the slot is available
- Stores appointment details in Google Sheets
- Handles unavailable time slots by asking for another time

---

## ⚙️ Tools Used:
- n8n (Workflow Automation)
- Google Calendar API
- Google Sheets API
- OpenAI Chat Model

---

## 🔄 Workflow Steps:
1. User provides appointment details
2. System checks availability in Google Calendar
3. If slot is available:
   - Appointment is confirmed
   - Event is created in Google Calendar
4. If slot is not available:
   - User is asked to select another time
5. Appointment details are saved in Google Sheets

---

## 📊 Output:
- Appointment successfully scheduled in Google Calendar
- Data stored in Google Sheets including:
  - Name
  - Phone Number
  - Date & Time
  - Status (Confirmed)

---

## ⚠️ Challenges Faced:
- Setting up Google Calendar API
- Handling time format issues
- Managing unavailable slots

---

## ✅ Conclusion:
This workflow automates the complete appointment booking process, reducing manual effort and ensuring efficient scheduling.
