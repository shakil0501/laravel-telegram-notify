# 🚀 Laravel Telegram Notifier

This Laravel project sends instant notifications to a Telegram bot whenever a new event is triggered (e.g., new user, form submission, etc.). Great for real-time alerts and monitoring.

![Laravel](https://img.shields.io/badge/Laravel-9.x-red?style=for-the-badge&logo=laravel)
![PHP](https://img.shields.io/badge/PHP-%23797FB3.svg?style=for-the-badge&logo=php&logoColor=white)
![Telegram](https://img.shields.io/badge/Telegram%20Bot-%2326A5E4.svg?style=for-the-badge&logo=telegram&logoColor=white)

---

## 📦 Features

- 🔔 Send custom messages to your Telegram bot
- ⚙️ Easy setup with `.env` file
- 📬 Reusable Notification class
- 🔐 Secure token management
- 🧰 Built with Laravel best practices

---

## 🛠️ Installation

```bash
git clone https://github.com/shakil0501/laravel-telegram-notify.git
cd laravel-telegram-notify
composer install
cp .env.example .env
php artisan key:generate
