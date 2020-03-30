# Basic Setup of Django With Websockets and Celery Workers
This is a simple test project for using web sockets with Django 2.2 using Django Channels. It includes a simple task for checking status of a URL using Celery and Redis.

This isn't a production ready web app - that's not the intention. It's a test to better learn how to interact with web sockets, and delay tasks to the Celery queue from web sockets.

## Installation and setup
To Do

## Core Tech Used

* Django 2.2
* Django Channels for web socket support
* Celery task queue
* Docker
* Javascript for client web sockets integration

## Suggested improvements
* Add database backend for users, urls and tasks/rules
* Use websockets to communicate with Slack board or HTTP for Telegram bot
* Docker settings for production environment with NGINX
