
# Twitch-Stream-Monitor
- [Twitch Stream Monitor](#Twitch-Stream-Monitor)
  - [Description](#description) 
  - [Settings Overview](#settings-overview)
  - [Features](#features)
    - [Actions](#actions)
    - [States](#states)
  - [Installation](#Installation)
  - [F.A.Q](#FAQ)
  - [Bugs and Support](#bugs-and-suggestion)
  
# Description
### A Plugin created for TouchPortal in order to monitor your choice of Twitch Streamers.

 **Useful in determinining who is the best choice for you to Watch/Host/Raid without going to 20+ different Twitch Pages!**

Useful when you are ready to shut down your stream for the night but don't know who to raid 
or host or just not sure what streamer to watch and just want to see your favorite list

* Streamer Name
* Streamer Picture 
* Total Viewers
* Time Online
* Game Title Icon
* Game Art Icon
* Live Preview Icon
* Is the Stream 18+ ?




## Settings Overview

  
## Settings Overview
| Name  | Type | Default Value |
| --- | --- | --- |
| Auto Update | text | OFF |
| Auto Update Seconds | number | 60 |
| Liv Preview Size  | text | 250x140 |
| Game Art Size | text | 128x128 |
| Live Image Preview Refresh Rate | number | 240 |





# Plugin Features

## Actions

| Action Name | Description | On Hold |
| --- | --- | --- |
| Toggle Auto Update | Turn Auto Update On or Off | False 
| Manually Check Raid / Host List | Checks the Raid_List.txt and Updates States |  False |
| Force Refresh State Updates | Allows you to force refresh your UI  | False |
| Open RaidList File | Easy access to your raidlist file to remove/add names | False



## States
<details id='gitago.tw_stream_monitor.mainstates'><summary><b>Category:</b> SM | Twitch Stream Monitor <small><ins>(Click to expand)</ins></small></summary>


| Id | Description | DefaultValue | parentGroup |
| --- | --- | --- | --- |
| .state.raidcheck.Channels_Online | Total Channels Online | 0 | Un-Checked |   |
| .state.raidcheck.Total_Raid_List | Total Channels from List | 0 |  |   |
| .state.raidcheck.AutoUpdate_Status | Auto Update Status (TRUE/FALSE) | FALSE |  |   |
| .state.raidcheck.AutoUpdate_Switch | Auto Update Switch (ON/OFF) | OFF |  |   |
| .state.raidcheck.AutoUpdate_TIMELEFT | Auto Update Time Left | 0 |  |   |
</details>

<details id='gitago.tw_stream_monitor.Raidcheck_1states'><summary><b>Category:</b> SM | Raid #1 <small><ins>(Click to expand)</ins></small></summary>


| Id | Description | DefaultValue | parentGroup |
| --- | --- | --- | --- |
| .state.raidcheck_1.user_name | Channels User Name | None |
| .state.raidcheck_1.game_name | Game Playing | None | 
| .state.raidcheck_1.is_mature | Is Stream Rated Mature | None |
| .state.raidcheck_1.title | Stream Title | None |
| .state.raidcheck_1.viewer_count | Viewer Count | None | 
| .state.raidcheck_1.livetime | Total Time Live | None |
| .state.raidcheck_1.live_thumb | Live Icon Preview | None |
| .state.raidcheck_1.user_thumb | User Icon Preview | None |
| .state.raidcheck_1.game_thumb | Game Icon Preview | None |
</details>

<details id='gitago.tw_stream_monitor.raidcheck_2states'><summary><b>Category:</b> SM | Raid #2 <small><ins>(Click to expand)</ins></small></summary>


| Id | Description | DefaultValue | parentGroup |
| --- | --- | --- | --- |
| .state.raidcheck_2.user_name | Channels User Name | None |
| .state.raidcheck_2.game_name | Game Playing | None | 
| .state.raidcheck_2.is_mature | Is Stream Rated Mature | None |
| .state.raidcheck_2.title | Stream Title | None |
| .state.raidcheck_2.viewer_count | Viewer Count | None | 
| .state.raidcheck_2.livetime | Total Time Live | None |
| .state.raidcheck_2.live_thumb | Live Icon Preview | None |
| .state.raidcheck_2.user_thumb | User Icon Preview | None |
| .state.raidcheck_2.game_thumb | Game Icon Preview | None |
</details>

<details id='gitago.tw_stream_monitor.raidcheck_3states'><summary><b>Category:</b> SM | Raid #3 <small><ins>(Click to expand)</ins></small></summary>


| Id | Description | DefaultValue | parentGroup |
| --- | --- | --- | --- |
| .state.raidcheck_3.user_name | Channels User Name | None |
| .state.raidcheck_3.game_name | Game Playing | None | 
| .state.raidcheck_3.is_mature | Is Stream Rated Mature | None |
| .state.raidcheck_3.title | Stream Title | None |
| .state.raidcheck_3.viewer_count | Viewer Count | None | 
| .state.raidcheck_3.livetime | Total Time Live | None |
| .state.raidcheck_3.live_thumb | Live Icon Preview | None |
| .state.raidcheck_3.user_thumb | User Icon Preview | None |
| .state.raidcheck_3.game_thumb | Game Icon Preview | None |
</details>

<details id='gitago.tw_stream_monitor.raidcheck_4states'><summary><b>Category:</b> SM | Raid #4 <small><ins>(Click to expand)</ins></small></summary>


| Id | Description | DefaultValue | parentGroup |
| --- | --- | --- | --- |
| .state.raidcheck_4.user_name | Channels User Name | None |
| .state.raidcheck_4.game_name | Game Playing | None | 
| .state.raidcheck_4.is_mature | Is Stream Rated Mature | None |
| .state.raidcheck_4.title | Stream Title | None |
| .state.raidcheck_4.viewer_count | Viewer Count | None | 
| .state.raidcheck_4.livetime | Total Time Live | None |
| .state.raidcheck_4.live_thumb | Live Icon Preview | None |
| .state.raidcheck_4.user_thumb | User Icon Preview | None |
| .state.raidcheck_4.game_thumb | Game Icon Preview | None |
</details>

<details id='gitago.tw_stream_monitor.raidcheck_5states'><summary><b>Category:</b> SM | Raid #5 <small><ins>(Click to expand)</ins></small></summary>


| Id | Description | DefaultValue |
| --- | --- | --- |
| .state.raidcheck_5.user_name | Channels User Name | None |
| .state.raidcheck_5.game_name | Game Playing | None | 
| .state.raidcheck_5.is_mature | Is Stream Rated Mature | None |
| .state.raidcheck_5.title | Stream Title | None |
| .state.raidcheck_5.viewer_count | Viewer Count | None | 
| .state.raidcheck_5.livetime | Total Time Live | None |
| .state.raidcheck_5.live_thumb | Live Icon Preview | None |
| .state.raidcheck_5.user_thumb | User Icon Preview | None |
| .state.raidcheck_5.game_thumb | Game Icon Preview | None |
</details>

**Up to 15 Total Pre-Created User Folders**

<br>

# Installation
Download latest version of plugin for your system under `Releases`
Import the downloaded .TPP file by clicking the gear button next to email/notification icon on the desktop application.
If this is first plugin, you will need to restart TouchPortal for it to work.

# FAQ
  
### **Q)** How do I add names to the List to search for?
**A)** There is a plugin action called #SET-CHANNELS you can utilize to open the raid_list.txt file
 
### **Q)** Why arent my states aren't updating?
**A)** If your set to Auto Update and see the update timer ticking, then try a manual refresh. 
  
### **Q)** Why are the images blurry?
**A)** You may adjust the size of the icon displayed in the plugin settings.<br />
  Please be aware this may take up CPU usage when it retrieves a new photo.
  
### **Q)** The plugin seems to not work anymore?
**A)** Please check your plugin settings and make sure its approved/running.<br />
  If you have confirmed it is running then a quick restart of TouchPortal may be needed to make it work properly again. 
  
  
# Bugs and Suggestion
Open an issue on github or join offical [TouchPortal Discord](https://discord.gg/MgxQb8r) for support.



