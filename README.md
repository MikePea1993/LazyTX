# LazyTX Discord Bot

LazyTX is a Discord bot designed to help manage warnings and bans in your server. It features an auto-update system to keep the bot current with the latest features and improvements.

## Features

- Create structured warning and ban messages
- Customizable warning levels
- Optional warning reference numbers
- Auto-update system
- Configurable update notification channel per server

### Setting Up Update Notifications

To set up the channel where update notifications will be sent:

1. Go to the desired channel in your Discord server.
2. Type `/set_update_channel` and send the command.
3. You'll receive a confirmation message if it's set up successfully.

Note: Only users with administrator permissions can use this command.

### Creating Warning/Ban Messages

Use the `/tx` command with the following parameters:

- `level`: Warning level (1-11)
- `ref`: Reference number
- `warn_ref`: Warning reference number (optional)
- `name`: User's name
- `reason`: Reason for warning/ban

Example:

[WARNING] DAY/MONTH/YEAR | Ref: #00000  | Timothy RB: FailRP

[WARNING] DAY/MONTH/YEAR | Ref: #00000 Warn Ref: # | Timothy RB: FailRP
