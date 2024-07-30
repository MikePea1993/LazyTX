# LazyTX Discord Bot

LazyTX is a Discord bot designed to help manage warnings and bans in your server. It features an auto-update system to keep the bot current with the latest features and improvements.

## Features

- Create structured warning and ban messages
- Customizable warning levels
- Optional warning reference numbers
- Auto-update system
- Configurable update notification channel per server
- shitter percentage auto calculator
- optional notes for tx template
- command to send only a note to the select channel of choice

### Setting up the bot for the first time

To set up:

1. Go to the desired channel in your Discord server but don't worry no one else can see these messages while you are setting it up.
2. set a channel you wish for updates to go to, these messages will appear when the bot has restarted to give you information on the update change log etc
3. first set the roles that can use the commands by doing `/set_allowed_role` you can select up to 6 at a time.
4. if you wish to see what roles are added you can do so by doing the `/list_allowed_roles`
5. if you need to remove roles use `remove_allowed_role` and select the role you wish to remove.
6. set the channel you wish for the `/tx` templates to be sent to you can do this by using the `/set_post` and selecting the channel

Note: Only users with administrator permissions can use these setup commands.

### Creating Warning/Ban Messages

Use the `/tx` command with the following parameters:

- `level`: Warning level (1-11)
- `ref`: Reference number
- `warn_ref`: Warning reference number (optional)
- `name`: User's name
- `reason`: Reason for warning/ban
- `notes`: add any additional notes needed
- `Shitter`: when looking into doing a shitter check you can use this to calculate the % of shitter rating.

Example:

[WARNING] DAY/MONTH/YEAR | Ref: #00000  | Timothy
RB: FailRP

[WARNING] DAY/MONTH/YEAR | Ref: #00000 Warn Ref: # | Timothy
RB: FailRP

[BAN | 1 DAY] 29/07/2024 | Ref: #123455 | Timothy
RB: FTI, CL, FailRP

Notes:
The player has repeated offences in FTI's CL and Failrps

Shitter Check:
Results 200 | Non RP Results 160 | [80.00%]
