# Gemini_Telegram_Bot
A Telegram Bot using Gemini API
# Demo
[Click](https://t.me/gemini_telegram_demo_bot)

# How to Install
## (1) On Linux
1. Install dependencies
```
pip install -r requirements.txt
```
2. Obtain Telegram Bot API at [BotFather](https://t.me/BotFather)
3. Get Gemini API keys from [Google AI Studio](https://makersuite.google.com/app/apikey)
4. To run the bot, execute:
```
python main.py ${Telegram Bot API} ${Gemini API keys}
```
## (2)Deploy Using Docker
### build
1. Get Telegram Bot API at [BotFather](https://t.me/BotFather)
2. Get Gemini API keys on [Google AI Studio](https://makersuite.google.com/app/apikey)
3. Clone repository
```
git clone https://github.com/H-T-H/Gemini-Telegram-Bot.git
```
4. Enter repository directory.
```
cd Gemini-Telegram-Bot
```
5. Build images
```
docker build -t gemini_tg_bot .
```
6. run
```
docker run -d --restart=always -e TELEGRAM_BOT_API_KEY={Telegram Bot API} -e GEMINI_API_KEYS={Gemini API Key} gemini_tg_bot
```

## (3)Deploy on Railway
Click on the button below for a one-click deployment.

[![Deploy on Railway](https://railway.app/button.svg)]([https://railway.app/template/HIsbMv?referralCode=4LyW6R](https://railway.app/template/CawDJP?referralCode=-fN2Db))



# How to Use
1. If you want to communicate with the bot in a group, your chat must start with **/gemini** or **/gemini_pro**.
```
/gemini Who is John Lennon?
```
```
/gemini_pro Who is John Lennon?
```
2. If you are having a private chat with the bot, you can directly send what you want.
```
Who is John Lennon?
```
3. You can use the **/clear** command to delete the current conversation history.

4. You can use the **/switch** command to switch the model.
