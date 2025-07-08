# Discord-Developer-Badge
A minimal Discord bot using Python and slash commands – perfect for testing, learning, or claiming your Active Developer Badge. Created by kuronami-dev

Built by [kuronami.dev](https://github.com/kuronami-dev)

## ⚙️ Features

- Slash command support
- Minimal setup
- Great for claiming the Active Developer Badge


## 🚀 Setup Instructions

### 1. Clone the Repository

```bash
git clone https://github.com/kuronami-dev/discord-developer-badge.git
cd discord-developer-badge
```
### 2. Install Dependencies

Make sure you're using Python 3.10+ and then install:
```bash
pip install -U discord.py
```

### 3. Create your Bot

- Go to the [Discord Developer Portal](https://discord.com/developers/applications)
- Create a new application
- Add a Bot to it
- Copy the Token


### 4. Enable Slash Commands

 **Under OAuth2 → URL Generator, select:**
- `bot`
- `applications.commands`

**Under Bot Permissions, choose at least:**
- `Send Messages`
- `Use Slash Commands`


Paste the generated URL into your browser and invite the bot to your server.

### 5. Edit the Code

Replace the line in `run.py`:

`bot.run("YOUR_BOT_TOKEN")`

with your actual token.

### 6. Run the Bot

Type in your IDE's Terminal:
`python main.py`

Alternative:

Open cmd and set the directory to your file and start it with:
`python main.py` again.

---

### ✅ Claiming the Active Developer Badge
Once your bot successfully responds to a slash command, visit:

👉 https://discord.com/developers/active-developer

Follow the instructions to claim your badge.


### 🧊 Notes
- Make sure the bot is added to a server you own or have permission to test on.

- The first time slash commands are registered, it might take a few minutes to appear.


### 💬 Author
Built with ❤️ by kuronami.dev
