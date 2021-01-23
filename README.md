# DiscordEncourgingBot_Project
Hi,
In this project, I used Python to program an autonomous bot runs on the Discord server to reply to negative messages in the chat using encouraging quotes and comments.

First, I created an chat bot in Discord server. Next I use the 'discord' package in Python and the bot's TOKEN to connect to the bot. 
Encouraging quotes from the bot are obtained through the web API: https://zenquotes.io/api/random. This API generates a random quote everytime it is called.
I also store some cheer-up statements in a No-SQL database in Repl.it.
When a user type a message containing negative words such as 'sad','depressed','unhappy', etc., the bot will respond with a positive quote. 
A user can also help update or review quotes using special commands.

To avoid server shutdown due to inactive, I used Flask server that connects to Repl.it to auto-refresh the server every 5 minutes: https://encourage-bot--vanhuycx.repl.co/
Thank you,
Van

