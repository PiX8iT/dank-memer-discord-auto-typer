# Dank memer auto typing macro -
Inspired by [Swayx's auto typer](https://github.com/Swayx113/dank-memer-auto-typer), this includes more features and flexibility. Can use this to auto gamble or even increase command usage 
- Let's you choose which commands should run
- Cooldown can be customised and waiting period(cooldown + delay) is randomised to mimic a regular user
- Commands are randomised but also optimised to have the least waiting time before running the command again

## Download and install  -
1. Download and install python from the [official website](https://www.python.org/downloads/)
2. Download the files `mainfile.py`, `config.py`, and `cooldowns.py` from this repository
3. Open command prompt in the directory containing the files and send `pip install -r requirements.txt`
<br> This will download the library `pynput` through which we can send the messages 

## To run -
- Move into dank memer auto typer directory
- Open the `config.py` file and set the commands you want to send as `True` and the rest as `False` 
- Click on `mainfile.py` to start the auto typer, you will have 5 seconds to click on the discord channel where you want to send messages
  <br>Note: the window where the message needs to be sent should be active; in other words, have your cursor blinking

## Requirements for the dank memer account - 
- Hunting Rifle (keep extra as it might break!)
- Fishing Rod (keep extra as it might break!)
- Laptop(s) (keep extra as it might break!)
- A couple pinks
- A couple life savers incase of death from dragons

# Notes
- If you do the same single command too amny times in a row, or constantly hit cooldowns on the bot, your account will get flagged for macro
- if you use it for too long (more than 2 hours?) or level up more than 600(they can change this number) levels in a row, you'll get bot banned
- You can customize the cooldowns as you see fit in `cooldowns.py`. Sometimes they'll need to be changed because of bot lag
- As of 31-Jan-2021, sending a dank memer command after rare catches from fish and hunt will not kill the user. But if the bug is fixed, life savers will be needed to not lose coins
- This is not the typical self bot as it does not use discord's bot features (using discord API), it's a macro that can type anywhere. It also cannot read any messages, it only sends what it is told to
- This very much mimics a real human being. If you do get caught, it's either because someone talked to you but you ignored the person which gaveaway the fact that it was a macro, or you used it for too long that the bot picked you up as an auto typer. 

## To Tereminate the macro -
- Just terminate the program window without touching any other places where the bot can be given the opportunity to type!

## Future improvements 
- Due to the bot devs having certain plans to combat auto typers, we'll soon require the ability to read messages and reply accordingly. <br>Hence I'll work on a better solution that can do everything a real human being can
- Make it so that the user can multi task while the macro does its work
 
 Feel free to suggest changes or open issues
