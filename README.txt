A txt version of README.md

# Dankmemer-Coin-Farmer-Bot
A script that you can use to farm coins with the Dankmemer coin in Discord.
Warning: your antivirus may mark this software as untested and thus unsafe. The code is open so if you want to look there to ensure the program is safe, go ahead.

This is an autohotkey automated script for farming coins with Dankmemer.  After clicking OK when you launch the program you have 9 seconds to get to the discord typing field. You need to select the typing field for the bot to work.
Press [F1] to pause the bot. Press [F1] again to resume the bot. If the bot is paused you cant use other commands. Press [F2] to withdraw all your money from the bank. Press [F3] to deposit all your money to the bank. (all that fits.) Press OK to start the bot. If you do so you have 9 seconds to get to the typing field and to select the typing field. Press [F12] to quit the program at any time. Press [F5] to view the changelog. Make sure the chat doesnt have slow mode and allows links to be sent. WARNING: This product is not complete and you may encounter problems. If you pause and unpause the bot starts from the beginning so you may encounter a cooldown error. Do you have any questions or suggestions? Send an e-mail to info.sergistudios@gmail.com  This product is in beta. ©Sergi Studios 2021. WARNING: SLOW MODE WILL START IMMEDIATELY!!

LINUX:
I dont have a Linux version of this, however you may be able to run this program with Wine for linux. https://www.winehq.org/

CODE: (written in Autohotkey.)

#NoEnv ; Recommended for performance and compatibility with future AutoHotkey releases.

; #Warn ; Enable warnings to assist with detecting common errors.

SendMode Input ; Recommended for new scripts due to its superior speed and reliability.

SetWorkingDir %A_ScriptDir% ; Ensures a consistent starting directory.

sleep 500
MsgBox Welcome to Dankmemer Coin Farmer bot v.0.35. Press [F1] to pause the bot. Press [F1] again to resume the bot. If the bot is paused you cant use other commands. Press [F2] to withdraw all your money from the bank. Press [F3] to deposit all your money to the bank. (all that fits.) Press OK to start the bot. If you do so you have 9 seconds to get to the typing field and to select the typing field. Press [F12] to quit the program at any time. Press [F5] to view the changelog. Make sure the chat doesnt have slow mode and allows links to be sent. WARNING: This product is not complete and you may encounter problems. If you pause and unpause the bot starts from the beginning so you may encounter a cooldown error. Do you have any questions or suggestions? Send an e-mail to info.sergistudios@gmail.com  This product is in beta. ©Sergi Studios 2021. WARNING: SLOW MODE WILL START IMMEDIATELY!!
InputBox, NumVar,Enter 0 or 1,Would you like to enable slow mode? (5 sec between all messages.) Please enable this if your chat has a slow mode of 5 seconds or less. Please note: You cant use any commands with slowmode. An update in the future will allow you to use commands in slow mode. Press 0 to use normal mode and press 1 to use slow mode.
InputBox, RandomNumber,Type a random number,Please type something random to prevent your account from being blacklisted from the bot. (like pls meme or i want a ps5:(

if (NumVar < 1)
sleep 9000
loop, 99999
{
send, pls{space}beg{enter}
sleep 49200
send, pls{space}beg{enter}
sleep 1000
send, pls{space}dep{space}all{enter}
sleep 1000
send, bot{space}by{space}Sergi{space}Studios.{enter}
sleep 1000
send, Go{space}to{space}https://github.com/SergiStudios/Dankmemer-Coin-Farmer-Bot{space}to{space}download{space}the{space}bot.{enter}
sleep 600
send, %RandomNumber%{enter}
sleep 49210
}
return

elseif (NumVar > 0)
sleep 9000
loop, 99999
{
send, pls{space}beg{enter}
sleep 49200
send, pls{space}beg{enter}
sleep 5100
send, pls{space}dep{space}all{enter}
sleep 5100
send, bot{space}by{space}Sergi{space}Studios.{enter}
sleep 5200
send, Go{space}to{space}https://github.com/SergiStudios/Dankmemer-Coin-Farmer-Bot{space}to{space}download{space}the{space}bot.{enter}
sleep 5200
send, %RandomNumber%{enter}
sleep 49210
}
return

F1::Pause

F2::
sleep, 155
send, pls{space}with{space}all{enter}
sleep 300
MsgBox Bot will continue in 5 seconds after you click OK. Select text field in discord.
sleep 5000
loop, 99999
{
send, pls{space}beg{enter}
sleep 49200
send, pls{space}beg{enter}
sleep 1000
send, pls{space}dep{space}all{enter}
sleep 1000
send, bot{space}by{space}Sergi{space}Studios.{enter}
sleep 1000
send, Go{space}to{space}https://github.com/SergiStudios/Dankmemer-Coin-Farmer-Bot{space}to{space}download{space}the{space}bot.{enter}
sleep, 633
send, %RandomNumber%{enter}
sleep 49210
}
return


F3::
sleep, 155
send, pls{space}dep{space}all{enter}
sleep 300
MsgBox Bot will continue in 5 seconds after you click OK. Select text field in discord.
sleep 5000
loop, 99999
{
send, pls{space}beg{enter}
sleep 49200
send, pls{space}beg{enter}
sleep 1000
send, pls{space}dep{space}all{enter}
sleep 1000
send, bot{space}by{space}Sergi{space}Studios.{enter}
sleep 1000
send, Go{space}to{space}https://github.com/SergiStudios/Dankmemer-Coin-Farmer-Bot{space}to{space}download{space}the{space}bot.{enter}
sleep 600
send, %RandomNumber%{enter}
sleep 49210
}
return



F6:: ;debug
MsgBox debug mode activated. development procent = 35. state = beta. showing change logs and exiting program.

F5:: ;changelog
MsgBox v0.35 - Added a disclamer in the main text and a warning not to use any special characters in the security section.                                                  v0.30 - Fixed a bug. And improved the security measures.                               V0.27 - Fixed grammar mistake: pauze--> pause. Added support for slow mode. (5 sec). Added security measure to prevent your accout from being blacklisted. Future update will improve this.                                      v0.21 - First English version and the first public version.

F12::ExitApp
