✳ Atrocious_Mirror_Bot.

✳ Deploy to Heroku directly.

✳ First of all upload token.pickle and credentials.json in bots root folder otherwise google drive link clone and upload in Google drive will not work.

Before deploying you must need to collect all config.

✳ Required Config :

AUTHORIZED_CHATS = Your group id where bot added as admin. You can add many groups id with a space. 

BOT_TOKEN = Your telegram bot api.

GDRIVE_FOLDER_ID = A google drive folder id for uploading file.

OWNER_ID = Your telegram id number .

TELEGRAM_API = Your telegram api .

TELEGRAM_HASH = Your telegram hash .


✳ Heroku config. 

HEROKU_API_KEY = Your Heroku accounts api key.

HEROKU_APP_NAME = Your Heroku app name . Write yur app name that you already wrote in appname .

BASE_URL_OF_BOT = Your herkou app url . Like [  https://1234.herokuapp.com  ] Here 1234 is heroku app name . On 1234 write your  heroku app name [ HEROKU_APP_NAME ] config.


✳ Index config. 

INDEX_URL = Your index url .


✳ Mega download config.

MEGA_API_KEY = Your mega account api key . Mega account with api key will help you for unlimited download from mega. If you have then put api key or leave it.

MEGA_EMAIL_ID = Your mega account email id .

MEGA_PASSWORD = Your mega account password. 

BLOCK_MEGA_FOLDER = If you dont want to disable mega folder uploading then set it True or leave it empty .

BLOCK_MEGA_LINKS = If you don't want to mega upload then set it True or leave it empty . If you dont have mega account and password then Set it also True .

✳ Team drive config. 

IS_TEAM_DRIVE = [ True Or False ] If you put team drive folder id in [ GDRIVE_FOLDER_ID ] then set it true otherwise leave it.


Deploy to Herkou now . 
<p><a href="https://heroku.com/deploy"> <img src="https://img.shields.io/badge/Deploy%20To%20Heroku-blueviolet?style=for-the-badge&logo=heroku" width="200""/></a></p>
