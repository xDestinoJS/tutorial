# Getting a Discord bot token
1. Go to the [Discord Developer Portal](https://discord.com/developers) and click on the "New Application" button. Then, give the application a name and click "Create":<br>![Image](https://i.imgur.com/PCiPgqU.png)
2. Then, create a Bot User by navigating to the "Bot" tab under settings and clicking "Add Bot":<br>
![Image](https://i.imgur.com/P49mTj5.png)<br>
Click "Yes, do it!" to continue.
3. Disable public bot if you don't want other people to invite your bot:<br>
![image](https://user-images.githubusercontent.com/39455804/111617285-33b8b100-87e3-11eb-8514-ffea2b106444.png)
4. Then, copy your bot token:<br>
![image](https://user-images.githubusercontent.com/39455804/111616751-8d6cab80-87e2-11eb-983a-b7656f3d7654.png)

#### ⚠️ Always keep the token a secret, as that is the equivalent to your bot's password. Anyone with the token can log in as your bot.

# Inviting your bot to your server
1. Get the Client ID by navigating to the "General Information" tab under settings<br>
2. Click "Copy" under Client ID<br>
![image](https://user-images.githubusercontent.com/39455804/111648559-c8330b80-8803-11eb-920e-7f4d8d1ae41f.png)<br>
3. Replace "INSERT_CLIENT_ID_HERE" with your Client ID:<br>https://<span></span>discord.com/oauth2/authorize?client_id=`INSERT_CLIENT_ID_HERE`&scope=bot&permissions=3072
4. Go to that URL
