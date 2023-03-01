# Basic discord music bot using discord js and discord-player

![image](https://user-images.githubusercontent.com/58798908/222283239-93f6938b-5a43-47fd-bb46-4055c56949e5.png)


![image](https://user-images.githubusercontent.com/58798908/222283359-417bf9f8-bdec-43ec-97b8-92f9d66c0700.png)


After you have cloned the repo make sure to create a `.env` file with the `TOKEN` and `CLIENT_ID` specified for example

```
TOKEN=xxx
CLIENT_ID=xxx
```

# Commands

- play
  - song {url}       - plays the song from the youtube url
  - search {keyword} - searches for the keyword on youtube and plays the first result
  - playlist {url}   - plays the playlist from url

- skip   - Skips the current song
- queue  - Displays the first 10 songs in the queue
- pause  - pauses the current song
- resume - resumes playing the current song
- exit   - kicks the bot from the voice channel
