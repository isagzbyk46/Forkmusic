# Gitarist Music Bot <img src="https://img.shields.io/github/v/release/TeamYukki/YukkiMusicBot?color=black&logo=github&logoColor=black&style=social" alt="RELEASE">

[GitaristMusicBot](https://github.com/isagzbyk46/Forkmusic) is a Powerful Telegram Music+Video Bot written in Python using Pyrogram and Py-Tgcalls by which you can stream songs, video and even live streams in your group calls via various sources.

## Features
- Youtube, Soundcloud, Apple Music, Spotify, Resso, Live Streams and Telegram Audios & Videos support.
- Written from scratch, making it stable and less crashes with attractive thumbnails.
- Loop, Seek, Shuffle, Specific Skip, Playlists etc support.
- Multi-Language support.

## 🚀 Deployment

### Deploy to Heroku

You can easily deploy the bot to Heroku using the button below:

[![Deploy](https://www.herokucdn.com/deploy/button.svg)](https://heroku.com/deploy?template=https://github.com/isagzbyk46/Forkmusic)

### Manual Deployment on Heroku

1. Clone the repository:
   ```bash
   git clone https://github.com/isagzbyk46/Forkmusic.git
   cd Forkmusic
   ```
2. Create a new Heroku app:
   ```bash
   heroku create your-app-name
   ```
3. Set up the required environment variables:
   ```bash
   heroku config:set API_ID=your_api_id
   heroku config:set API_HASH=your_api_hash
   heroku config:set BOT_TOKEN=your_bot_token
   ```
4. Deploy the app:
   ```bash
   git push heroku main
   ```
5. Scale the dyno:
   ```bash
   heroku ps:scale worker=1
   ```
6. Start the bot:
   ```bash
   heroku logs --tail
   ```

## ⚡️ Getting Started [[Documentation](https://notreallyshikhar.gitbook.io/yukkimusicbot/)]

The official [documentation site](https://notreallyshikhar.gitbook.io/yukkimusicbot/) contains a lot of information. The best place to start is from the deployment section.

## 🏷 Support / Assistance

Reach out to the maintainer at one of the following places:

- [GitHub Issues](https://github.com/isagzbyk46/Forkmusic/issues/new?assignees=&labels=question&template=SUPPORT_QUESTION.md&title=support%3A+)
- Contact options listed on [this GitHub profile](https://github.com/isagzbyk46)
- [Telegram Support](https://t.me/gitaristmusic12)

If you want to say **thank you** or/and support active development of GitaristMusicBot:

- Add a [GitHub Star](https://github.com/isagzbyk46/Forkmusic) to the project.
- Fork the Repo :)
- Write interesting articles about the project on [Dev.to](https://dev.to/), [Medium](https://medium.com/) or your personal blog.

Together, we can make **GitaristMusicBot** better!

## 📑 Acknowledgement / Credits

Special thanks to these amazing projects/people which/who help power Gitarist Music Bot:

- [Pyrogram](https://github.com/pyrogram/pyrogram)
- [Py-Tgcalls](https://github.com/pytgcalls/pytgcalls)
- [CallsMusic Team](https://github.com/Callsmusic)
- [TheHamkerCat](https://github.com/TheHamkerCat)
- [Aarav Arora](https://github.com/axrav)

---
**Reminder:** You are great, you are enough, and your presence is valued. If you are struggling with your mental health, please reach out to someone you love and consult a professional.

