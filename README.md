# Ethos-GroupchatForensics

### Pre-requisites 
- As always, the ```PLANNING.md``` file must be gone through first to understand the way to build out this module.
  - By all EthosProject modules using the same ```PLANNING.md``` file, we can consistently build out each module to be like the rest of them and easily able to interchange and share data and work together to perform more complex functions over time.
 
### Ethos-GroupchatForensics Summary
Ethos-GroupchatForensics will be a utility that EthosProject operators are able to add in Telegram Groupchat links which will be monitored and harvested for several types of information.

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


