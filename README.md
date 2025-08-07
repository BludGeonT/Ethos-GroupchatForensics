# Ethos-GroupchatForensics

### Pre-requisites 
- As always, the ```PLANNING.md``` file must be gone through first to understand the way to build out this module.
  - By all EthosProject modules using the same ```PLANNING.md``` file, we can consistently build out each module to be like the rest of them and easily able to interchange and share data and work together to perform more complex functions over time.
 
### Ethos-GroupchatForensics Summary
Ethos-GroupchatForensics will be a utility that EthosProject operators are able to add in Telegram Groupchat links which will be monitored and harvested for several types of information.
- There are two methods of watching channels.  We want to extract as much information from them as possible, focusing on obtaining as many UIDs as possible inside of them.
  - One method is to observe the channel without joining it.  This can be done with the Telegram desktop client and can be done for public groupchat channels.  Information from reaction emoji within groupchat comments, people joining the channel, who sends messages, and message contents should all be viewable without actually joining a channel.  This is the preferred method for most cases.
  - Another method is to have to Join a room by clicking join.  This is a little more risky towards bot detection as the bot information will show up in their spambot log channel (if they have one set up).  From experience, most channels don't really say much upon joining for these crypto scammer channels and on occasion they will send out DMs which you can just ignore.
  - Yet another method is to have to click an invite request link, where an admin of the groupchat will have to manually approve you to get in.  In this and sometimes in the case above, you will need to engage with an admin and you can not have "bot" in your name.  You can, but chances are if the admins know what they're doing they'll recognize the bot in the name and instaban.
    - This is not something to consider right now and will be done later on with some intelligent Agentic workflows or, manually joining these channels by hand and getting inside, and then kicking off the GroupchatForensics bot on the implanted account.

### Ethos-GroupchatForensics Layout
The layout for this module will be similarly laid out like the other EthosProject modules (eg:  Ethos-OCR, Ethos-BotManager).
- There will be a Groupchat Visualizer at the bottom, like the other modules have similar visualizers, which will display all of the channels that are registered in the Ethos-GroupchatForensics module database and when one is clicked it will expand the record above like Ethos-BotManagement does.


#### Ethos-GroupchatForensics - Adding Channels Into The Database
This module will have a button that says "Add A Groupchat"

##### Ways To Join A Telegram Groupchat
- From a generated invite link from the channel.
  - Channel invite links can be deactivated and changed and big spammer channels will do this often.  These links are usually removed instantly by @missrose_bot and the links can be viewed in a Channel's Recent Actions section.
  - Channel invite links will be a record in the database for their respective channel
- From doing a search on Telegram to find the channel if you know the name of it.


