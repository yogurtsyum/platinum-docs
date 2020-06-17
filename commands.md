# Commands

The default bot prefix is `?`. Forgot the prefix? `@Platinum#1240` \(mentioning the bot\) will always work as a prefix.

**Server Verification**

`verify` - Verifies on the server if verification is enabled. You must have DM's enabled to use this command.

`set-verified-role [role id]` - Sets the verification role on a server. Leave empty to disable verification.

**Tickets**

`new [ticket topic]` - Creates a ticket on the server if tickets are enabled.

`set-ticket-category [category id]` - Sets the ticket category. Leave empty for no category.

`set-ticket-channel [channel id]` - Sets the ticket channel where all messages sent are turned into tickets with that as the topic message. Leave empty for no channel.

`set-ticket-log-channel [channel id]` - Sets the channel where tickets are logged. Leave empty for no ticket logs.

`ticket-toggle <true/false>` - Toggles the ticket module. Leave empty for no ticket logs.

`set-ticket-role [role id]` - Sets the role that can view tickets. Leave empty for none, which will only let people with the Administrator permission view tickets.

**Tags**

`tag create <tag> <text>` - Creates a tag.

`tag edit <tag> <text>` - Edits a tag.

`tag delete <tag>` - Deletes a tag.

`tag info <tag>` - Displays info about a tag.

`tag <tag>` - Displays a tag.

`set-tag-log-channel [channel id]` - Sets the tag log channel. Leave empty to disable tag log channel.

`set-tag-role [role id]` - Sets the role that can manage tags. People with the Manage Guild permissions can even if they don't have this role.

`toggle-tag-embed <true/false>` - Toggles tags being displayed in embeds.

**General Bot Commands**

`help` - Displays some bot information such as the command list command, the link to this page, the link to invite the bot, and an invite link to the support server.

`cmds` - Lists all of the bot commands in Discord. Not as detailed as this page.

`prefix [prefix]` - Sets the server prefix. Leave empty to view the current server prefix.

