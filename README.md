# Kursova-MedClinicBot

**Description:**
This project is a Telegram bot designed to assist users in scheduling appointments with doctors, filling out declarations, and asking questions. The bot also provides an admin panel for managing the bot and viewing statistics.

**Features:**
- Schedule appointments with doctors
- Fill out declarations
- Ask questions and receive answers from doctors
- Admin panel for managing the bot and viewing statistics

**Installation:**
1. Clone the repository `git clone https://github.com/romchhh/Kursova-MedClinicBot/`
2. Install the required dependencies by running `pip install -r requirements.txt`.
3. Set up your Telegram bot token, group ID, admin IDs, session name, API hash, API ID, and other configurations in the `config.py` file.

```python
TOKEN = 'your_telegram_bot_token'
GROUP_ID = 'your_telegram_group_id'
ADMIN_IDS = ['admin_user_id1', 'admin_user_id2']
```

4. Run the bot using `python main.py`.



**Usage:**
**User:**
- Start the bot by sending the `/start` command.
- Choose an option from the main menu:
- Declaration: fill out a declaration form
- Schedule: schedule an appointment with a doctor
- Ask a question: ask a question and receive an answer from a doctor
- Follow the prompts to complete the desired action.

**Admin:**
- Start the bot by sending the `/admin` command.
- Choose an option from the admin panel:
- Statistics: view statistics about the bot's usage
- Export database: export the bot's database to an Excel file
- Broadcast: send a message to all users of the bot
- Questions: view and answer questions from users

**Screenshots:**
- [Main Menu](screenshots/main_menu.png)
- [Declaration Form](screenshots/declaration_form.png)
- [Schedule Appointment](screenshots/schedule_appointment.png)
- [Admin Panel](screenshots/admin_panel.png)

**Contributing:**
Pull requests are welcome. For major changes, please open an issue first to discuss what you would like to change.

**License:**
MIT

**Contact:**
...

**Project Link:**
[TelegramBot](https://t.me/PortMedClinicBot)


