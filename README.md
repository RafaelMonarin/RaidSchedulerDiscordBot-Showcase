# Destiny 2 Raid Scheduler - Discord Bot  

A Discord bot designed to easily organize **Destiny 2 raids**.  
The bot has a single command `/raid`, which guides players through creating raid groups, managing schedules, and sending automatic reminders.  

---

## ✨ Features  

- **Create raids with `/raid`**  
  - Autocomplete for the 3 required fields:  
    - Raid name  
    - Day  
    - Time  
  - Optional fields for raid modifiers  

- **Thematic embed**  
  - Displays the raid name, image, color, and information  
  - Shows selected fields: raid, day, time, and modifiers  
  - Interactive buttons:  
    - ➕ Join (up to 6 players)  
    - ➖ Leave  

- **Player management**  
  - Maximum of **6 players** per raid  
  - Real-time updated list  

- **Automatic DM reminders**  
  - Message when the group is completed  
  - Reminder with **raid date and time**  
  - Notification **30 minutes before** the scheduled raid  

- **Database (MongoDB)**  
  - All raids are stored  
  - Raids are **automatically deleted 2h after the scheduled time**  

---

## 🚀 Technologies Used

- [Discord.js](https://discord.js.org/) – Discord API integration  
- [Node.js](https://nodejs.org/) – Runtime environment  
- [MongoDB](https://www.mongodb.com/) – Database for raid persistence  

---

## 📸 Demo  

### 🖼️ Screenshot
![Raid Embed Example](https://i.imgur.com/KKhLqMz.png)

### 🎥 Video Demo
Click the image below to watch the demo
[![Watch the video](https://i.imgur.com/IzF6vRt.png)](https://youtu.be/uspux7ntepQ)
