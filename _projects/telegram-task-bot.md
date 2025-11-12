---
layout: project
title: Python Telegram Task Bot
permalink: /projects/telegram-task-bot/
description: A personal task management bot built with Python and the python-telegram-bot library, designed for easy deployment via Docker.
category: fun
# Add a custom image here (e.g., img: assets/img/telegram-bot.png)
# img: 
github: jordialt/python-telegram-task-bot
# website: # Add a link to the bot's Telegram channel or a demo video
---

This project is a fully functional **task management bot** for Telegram, built as a personal tool to manage to-do lists directly from the messaging app.

It is implemented in Python and leverages the `python-telegram-bot` library. The bot uses a separate file for database operations (likely using SQLite or similar) to handle user data and task persistence.

Key features and deployment aspects include:
* **Core Functionality:** Task creation, listing, and deletion managed via Telegram commands.
* **Data Persistence:** Tasks are stored and retrieved using the `database.py` module.
* **Containerization:** The project is configured for easy and repeatable deployment using `Dockerfile` and `docker-compose.yml`.

This was a fun project to learn about API integration, asynchronous programming, and container-based deployment for microservices.
