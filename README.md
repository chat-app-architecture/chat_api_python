# Real Time Chat Django API

This repository contains the API codebase of the Real Time Chat developed with Django Channels and React.

It uses Django Channels on the API side with React and Websockets on the frontend. Here is an image explaining the message flow between the API and the frontend:

## Requirements

- API
- python 3
- pip
- redis-server
- PostgreSQL
- Frontend
- yarn
- Setup
- API

You can check the API code here.

Then execute the following commands to run the API:

- First, set up `python`, `redis` and `virtualenv`:

```bash
$ brew install python
$ brew install redis
$ pip3 install virtualenv
```
- Clone this repository and run it locally:

```bash
$ git clone https://github.com/chat-app-architecture/chat_api_python
$ cd chat_api_python
$ source venv/bin/activate
$ pip3 install -r requirements.txt
$ redis-server & python3 manage.py runserver 0:8000
```
