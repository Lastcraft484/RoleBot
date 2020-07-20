# RoleBot

# Bot creation. 
First a Discord bot must be created using Discord's  [Developer Portal](https://discord.com/developers/applications).

Click the **New Application** Button in the top right.

![New Application Image](https://cdn.discordapp.com/attachments/707320637026336799/734870107888681020/unknown.png)

Next choose a name for the bot **(you can change this later)**.

![Bot Name](https://cdn.discordapp.com/attachments/707320637026336799/734870582109274163/unknown.png)

After a name is entered this page will be brought up.

![bot page](https://cdn.discordapp.com/attachments/707320637026336799/734871335716651168/unknown.png)

Here is where the application name and icon are changed. **The application** name and icon are not  After that is configured click the bot tab on the left.

![Add a bot](https://cdn.discordapp.com/attachments/707320637026336799/734871830061645904/unknown.png)

Here you will select **Add Bot**

![Select Yes](https://cdn.discordapp.com/attachments/707320637026336799/734872232425422919/unknown.png)

Once **Yes, do it!** is selected you will be brought to this page:

![Bot config](https://cdn.discordapp.com/attachments/707320637026336799/734875049445556335/unknown.png) 

Here is where the bot name and icon are changed. Below the name there is the token. The token is what the code uses to talk to Discord's servers. Click on *Click to Reveal Token* or click on **Copy** . The token is needed later. Next click on the **OAuth2** tab

![OAuth2 Page](https://cdn.discordapp.com/attachments/707320637026336799/734878141255909397/unknown.png)

Here, click **bot** in the table below. This will bring up the table blow:

![Perms table](https://cdn.discordapp.com/attachments/707320637026336799/734878415827501126/unknown.png)
Here is where the bot's permissions are assigned. Make the table look like this:

![Finished Perm table](https://cdn.discordapp.com/attachments/707320637026336799/734878748226093076/unknown.png)
This assures the bot has the correct permissions to perform all the tasks required. In the next step python will be installed to run the bot. 
# Token

- [Python Download](https://www.python.org/ftp/python/3.8.5/python-3.8.5.exe)

- **Add Python to path**

- Open cmd and paste: `py -3 -m pip install -U discord.py` This installs discord.py

- Open a text editor and paste the token from before in place of `token` on line 41
`client.run('token')` in `rolebot.py`

## Enabling Developer Mode
Now Make sure Discord developer mode is enabled on your Discord client. Here is how to do it on pc. 

Click *User Settings* in the bottom left 

![usersettings](https://cdn.discordapp.com/attachments/707320637026336799/734882935026483320/unknown.png)

Click Appearance under the **APP SETTINGS** tab 

![apperance](https://cdn.discordapp.com/attachments/707320637026336799/734883384475779142/unknown.png) 

Scroll down and locate **Developer Mode** and flip the toggle.

![dev mode](https://cdn.discordapp.com/attachments/707320637026336799/734896739605282816/unknown.png)

This allows the user to see information that would not normally be visible (like user ids and message ids).

# Message Creation.
Here is an example of a message that uses the role bot. 
![message](https://cdn.discordapp.com/attachments/707320637026336799/734897516478201916/unknown.png)
T
his message works very well because it lets the members know what to do with the message and it shows the members what roles correspond with what emoji. In this example I have reacted to each message with my discord account then disabled adding reactions in the channel permissions. This allows users to react with the emojis that I have added but not choose any more to react with.
![perms](https://cdn.discordapp.com/attachments/707320637026336799/734898350452768840/unknown.png)

To allow this turn off **Add Reactions** and **Use External Emojis** in the settings for the channel. 

Once the message is set up. Click the 3 dots in the top right of the message labeled **more**
and click **Copy ID**

![copy id](https://cdn.discordapp.com/attachments/707320637026336799/734899515756118056/unknown.png)

Note this ID somewhere it is needed in the next step.

Open 

## Example Emojis and role set up.
Here is a simple set up for how to assign roles to emoji.
|     Description           |Role                          |Emoji                         |
|----------------|-------------------------------|-----------------------------|
|Add role for DiRT|`DiRT`            |:DiRT:            |
|Add role for Forza|`Forza`            |:Forza:            |
|Add role for CitiesSkylines|`CitiesSkylines`|:CitiesSkylines:|



<!--stackedit_data:
eyJoaXN0b3J5IjpbNTkwODg3NjA5LDEyNDAzMjk2MDMsLTMyMD
I5NDAyMSwxNzkwOTAzMjUwLDE3OTYwNjI4ODIsLTEwOTg2NTIw
MjgsMjEwMDg5Mjk3NywtMTYwMjIyMDMwN119
-->