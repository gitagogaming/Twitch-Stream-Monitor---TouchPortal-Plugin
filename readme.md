
# Better-Raids
- [Better Raids](#Better-Raids)
  - [Description](#description) 
  - [Settings Overview](#Settings-Overview)
  - [Features](#Features)
    - [Actions](#actions)
        - [Category: BE | Better Raids](#gitago.better_raids.mainactions)
    - [States](#states)
        - [Category: BE | Better Raids](#gitago.better_raids.mainstates)
  - [Bugs and Support](#bugs-and-suggestion)
  - [License](#license)
  
# Description

Making it easier to find out who to Raid.<br>
<b>You will be able to see:<br></b>
Who is Online<br>
What are they Playing<br>
Is it a Mature Stream?<br>
How many viewers do they have?<br>
How long have they been streaming?<br>

This documentation generated for Better Raids V120 with [Python TouchPortal SDK](https://github.com/KillerBOSS2019/TouchPortal-API).

## Settings Overview
| Read-only | Type | Default Value |
| --- | --- | --- |
| False | text | ON |

| Read-only | Type | Default Value | Min. Value |
| --- | --- | --- | --- |
| False | number | 45 | 45 |


# Features

## Actions
<details open id='gitago.better_raids.mainactions'><summary><b>Category:</b> BE | Better Raids <ins>(Click to expand)</ins></summary><table>
<tr valign='buttom'><th>Action Name</th><th>Description</th><th>Format</th><th nowrap>Data<br/><div align=left><sub>choices/default (in bold)</th><th>On<br/>Hold</sub></div></th></tr>
<tr valign='top'><td>Check Raid List for People</td><td> </td><td>Check Raid List for People</td><td><ol start=1><li>Type: text &nbsp; 
&lt;empty&gt;</li>
</ol></td>
<td align=center>No</td>
</tr></table></details>
<br>

## States
<details open id='gitago.better_raids.mainstates'><summary><b>Category:</b> BE | Better Raids <ins>(Click to expand)</ins></summary>


| Id | Description | DefaultValue | parentGroup |
| --- | --- | --- | --- |
| .state.raidcheck.Channels_Online | BR | --- Total Channels Online | Un-Checked |   |
| .state.raidcheck.Total_Raid_List | BR | --- Total Channels |  |   |
| .state.raidcheck.AutoUpdate_Status | BR | --- Auto Update Status (ON/OFF) |  |   |
| .state.raidcheck.AutoUpdate_TIMELEFT | BR | --- Auto Update Time Left) |  |   |
</details>

<br>

# Bugs and Suggestion
Open an issue on github or join offical [TouchPortal Discord](https://discord.gg/MgxQb8r) for support.


# License
This plugin is licensed under the [GPL 3.0 License] - see the [LICENSE](LICENSE) file for more information.

