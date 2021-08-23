# Pissu-Bota
  Pissu bota is a very simple discord bot which I developed for fun.</br>
  It will respond to specific words in your messages which you send in the discord chat. You can add, view & delete the responses as you wish using the commands also the respondings of the bot can be turned on or off using a simple command.</br>
  Also using a specific command you can send some inspirational quotes into the chat.
# Basic commands
  - $new : Add new phrase to your bot's db
  - $delete : Delete existing phrase
  - $view : View the existing phrases in the db
  - $inspire : Randomly generated inspirational quote will appear. 
  - $responding [true/false] : If true the bot will respond. If false bot will not.
# How to setup
 Create a bot in the discord application section and copy the token of the bot. </br>
 Then replace it with the 'TOKEN' in the last line of the code of the file main.py. </br>
 client.run(os.environ['Your token here']) </br>
 Then run the code and enjoy :)

PS :- Do not share the token of your bot with anyone. If someone get hand on the token they can control the bot as they want. 😬
