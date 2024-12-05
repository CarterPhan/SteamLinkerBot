# SteamLinkerBot

A Discord bot made in Python that takes a link with a steam header, passes it through a custom github website, and returns a button that contains the link, allowing the user to click and join a lobby without having to copy paste to their browser.

# Usage

![ ](https://github.com/CarterPhan/SteamLinkerBot/blob/main/images/steamlinker.gif)

Simply copy and paste your steam link into any channel that the bot can see, and the bot will put a message underneath with a clickable button!

If you are done with your lobby, feel free to delete the link message. The bot will read this and delete its own message too!

# Development

-   Fork and/or clone this repository
-   Install python3 and pip3 locally
-   Run "pip3 install -r requirements.txt"
-   Replace the environment variables in config.py with your own keys
-   Run "python3 main.py" from the src folder

# Adding the Bot to your Server:

By default, the bot requires the permissions to Send Messages, Manage Messages, and Embed Links. The Send Messages and Embed Links permission is to send the link into the chat, while the Manage Messages permission is so that the bot can delete its own message once it sees the original message deleted. Outside of that, the bot does nothing more to your messages. If you are still afraid of this however, feel free to modify your channel permissions such that the bot is unable to read or access any channel other than the one that steam links are fed through.

# Privacy Policy:

This is mainly here for Discord's legal purposes. We collect 0 data. The only data that is fed into the bot is your account and message if it contains a steam link. There is no information saved or used for any purposes, good or bad here.

# Terms of Service:

This is mainly here for Discord's legal purposes, and if this gets enough traction I will make a more in-depth terms of service. Essentially, we collect no data, you are not allowed to use this bot or any fork of this bot for malicious purposes, and we cannot guarantee that this bot will be free of any errors. If you understand and agree with these terms, then you are free to use and fork the bot as you would like.
