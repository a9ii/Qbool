
# 🎓 University Selection Telegram Bot

Welcome to the **University Selection Bot** – the ultimate Telegram bot that helps you choose the best universities and institutes based on your academic score and chosen stream! 🚀

---

## 📝 Overview

This bot is built using **PHP** and the **Telegram Bot API**. It offers a smooth and interactive experience where users can select their study stream (Scientific or Literary), input their academic score, and receive a tailored list of universities. Additionally, if the Scientific stream is chosen, the bot will also display a list of the top 10 institutes based on the entered score.

---

## ✨ Features

- **Stream Selection:** Easily choose between Scientific and Literary streams with interactive buttons.
- **Score Input:** Users can input their academic score, which is stored and used for filtering options.
- **University Filtering:** Displays a list of up to 40 universities that match the user’s score and selected stream.
- **Institute Listings:** For Scientific stream users, shows a top 10 list of institutes based on the score.
- **Channel Membership Check:** Ensures that users are members of the designated Telegram channel before using the bot. 📢
- **Support:** Provides a support button to contact the technical support bot directly.

---

## ⚙️ Requirements

- **PHP 7.0+**
- **A web server that supports PHP** (e.g., Apache or Nginx)
- **SSL/HTTPS** (required for setting up the Telegram webhook)
- **File write permissions:** The bot creates a `user_data` directory to store user data.

---

## 🚀 Installation and Setup

1. **Clone the Repository:**

   ```bash
   git clone https://github.com/a9ii/Qbool.git
   cd Qbool
   ```

2. **Configure Basic Settings:**

   Open the main PHP file (e.g., `bot.php`) and update the following variables:
   - `$botToken`: Insert your Telegram bot token.
   - `$channelUsername`: Enter your channel username (e.g., `@Tele2IQ`).
   - `$contactBotUrl`: Provide the URL for your support bot.

3. **Set Up the Webhook:**

   Set the webhook for your bot using the following URL (replace `<YourToken>`, `YourDomain`, and `bot.php` accordingly):

   ```bash
   https://api.telegram.org/bot<YourToken>/setWebhook?url=https://YourDomain/path/to/bot.php
   ```

4. **File Permissions:**

   Ensure that the `user_data` directory exists in the same path as your PHP file, or it will be created automatically when needed.

5. **Test the Bot:**

   Open a chat with your Telegram bot, send the `/start` command, and follow the on-screen options to use the bot.

---

## 📚 How It Works

1. **Start Command:**
   - When a user sends `/start`, the bot displays a menu with options:
     - **Input Score** (📥 Input Score)
     - **Show Universities** (🔍 Show Universities)
     - **Choose Stream** (📝 Choose Stream)
     - **Help** (❓ Help)

2. **Stream Selection:**
   - Upon selecting "📝 Choose Stream", users are presented with inline buttons to choose between Scientific and Literary.
   - The selection is stored in the `user_data` directory for later use.

3. **Score Input:**
   - Users input their academic score, which is then saved for subsequent filtering.

4. **Displaying Results:**
   - Based on the user’s score and selected stream, the bot filters and displays a list of up to 40 universities.
   - If the Scientific stream is selected, a list of the top 10 institutes is also appended.

5. **Help:**
   - The **Help** button provides a direct link to contact the support bot if assistance is needed.

---

## 🤝 Contributing

Contributions are welcome! If you have suggestions or improvements, feel free to open an **Issue** or submit a **Pull Request**.

---

## 📄 License

This project is licensed under the [MIT License](LICENSE). See the LICENSE file for more details.

---

## 📞 Contact

If you encounter any issues or have any questions, please reach out via the [Support Bot](https://t.me/ContactMAI_bot) or open an Issue on GitHub.

---

Enjoy using the bot, and let’s shape a brighter academic future together! 🌟
