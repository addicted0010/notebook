# notebook

***20260327 Workshop***

---Download Wuying EDS Client App:

https://www.alibabacloud.com/en/product/cloud-desktop/download-client?_p_lc=1

---Login EDS

Org ID: Xa749426


---Download and Install Telegram Desktop/Mobile App

https://telegram.org/


---Install Homebrew

curl -fsSL https://raw.githubusercontent.com/Homebrew/install/HEAD/install.sh | bash

echo >> ~/.bashrc

echo 'eval "$(/home/linuxbrew/.linuxbrew/bin/brew shellenv bash)"' >> ~/.bashrc

eval "$(/home/linuxbrew/.linuxbrew/bin/brew shellenv bash)"

sudo apt-get install build-essential

brew install gcc


---Install OpenClaw

https://openclaw.ai/
Install: 
curl -fsSL https://openclaw.ai/install.sh | bash


---Skills

https://clawhub.ai/


---Add a new agent and paring with Telegram bot

1) Go to Terminal, run: "openclaw agents add \<AgentName>"
2) Go to OpenClaw Dashboard WebUI - Chat - Switch to target agent - send 'Set up Telegram with this bot token: <BotToken>'
3) In Telegram, find your bot, send first message. This will trigger pairing.
4) Go to Terminal, run: "openclaw pairing approve telegram \<code>"

