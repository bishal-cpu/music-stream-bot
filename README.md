# music-stream-bot
advance music with video streaming
# Telegram Music and Video Streaming Bot

## Features:
- Stream YouTube, Spotify, and SoundCloud to Telegram group voice chats.
- Manage music queues, skip, and stop playback.
- Easily deployable on Heroku.

## Setup:

1. **Clone the repository**:
2. **Install dependencies**:
3. **Create a `.env` file** and fill in your `API_ID`, `API_HASH`, and `BOT_TOKEN` from Telegram:

4. **Deploy on Heroku**:
- Install the [Heroku CLI](https://devcenter.heroku.com/articles/heroku-cli).
- Log in to Heroku: `heroku login`
- Create a new Heroku app: `heroku create your-app-name`
- Add environment variables on Heroku:
  ```
  heroku config:set API_ID=YOUR_API_ID API_HASH=YOUR_API_HASH BOT_TOKEN=YOUR_BOT_TOKEN
  ```
- Push to Heroku:
  ```
  git init
  git add .
  git commit -m "Initial commit"
  git push heroku master
  ```

5. **Enjoy the bot** in your Telegram group!

