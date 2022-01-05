✳ Atrocious_Mirror_Bot.

✳ First for this repo .
Before deploying you must need to collect all required config and token.pickle and credentials.json. 

✳ First fork this repo . Then upload token.pickle and credentials.json in bot root folder . Then go to herokou and add all config on config vars option . Then go to your apps deploy option and select your forked repo and connect and click deploy branch and wait for deploying . 
If bot not working then check herkou log .


✳ Required Config :

AUTHORIZED_CHATS = Fill user_id and chat_id (not username) of groups/users you want to authorize. Separate them by space, Examples: -0123456789 -1122334455 6915401739.

BOT_TOKEN = The Telegram Bot Token that you got from @BotFather.

GDRIVE_FOLDER_ID = A google drive folder id for uploading file.

OWNER_ID = The Telegram User ID (not username) of the Owner of the bot.

SUDO_USERS = Fill user_id (not username) of users whom you want to give sudo permission. Separate them by space, Examples: 0123456789 1122334455 6915401739.

TELEGRAM_API = This is to authenticate your Telegram account for downloading Telegram files. You can get this from https://my.telegram.org.

TELEGRAM_HASH = TELEGRAM_HASH: This is to authenticate your Telegram account for downloading Telegram files. You can get this from https://my.telegram.org


✳ Heroku config. 

HEROKU_API_KEY = Your Heroku accounts api key.

HEROKU_APP_NAME = Your Heroku app name . Write yur app name that you already wrote in appname .

BASE_URL_OF_BOT = Valid BASE URL where the bot is deployed to use qbittorrent web selection. Format of URL should be http://myip, where myip is the IP/Domain(public) of your bot or if you have chosen port other than 80 so write it in this format http://myip:port (http and not https). This Var is optional on VPS and required for Heroku specially to avoid app sleeping/idling. For Heroku fill https://yourappname.herokuapp.com. Still got idling? You can use http://cron-job.org to ping your Heroku app..


✳ Index config. 

INDEX_URL = Your index url .


✳ Mega download config.

MEGA_API_KEY = Your mega account api key . Mega account with api key will help you for unlimited download from mega. If you have then put api key or leave it.

MEGA_EMAIL_ID = E-Mail ID used to sign up on mega.nz for using premium account (Leave though).

MEGA_PASSWORD = Password for mega.nz account. 

BLOCK_MEGA_FOLDER = you want to remove mega.nz folder support, set it to True .

BLOCK_MEGA_LINKS = If you want to remove mega.nz mirror support, set it to True.

✳ Team drive config. 

IS_TEAM_DRIVE = Set to False or leave it empty to get public google drive links else True so only who have access to your Folder/TeamDrive can open the links. 

For queries or any issues regarding the bot please open an issue ticket or visit us at [AtrociousBotSupport](https://t.me/AtrociousBotSupport)

✳ Others Optional config : 

Credits : This is a Telegram Bot written in Python for mirroring files on the Internet to your Google Drive or Telegram. Based on python-aria-mirror-bot.

Main Repo : https://github.com/lzzy12/python-aria-mirror-bot

Some features updated from  mirror leech telegram bot.

https://github.com/anasty17/mirror-leech-telegram-bot
