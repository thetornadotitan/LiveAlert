# LiveAlert
Bot to send notifications to discord channels when watched streamers go live!

Only server owners can use these commands. Anyone else, regardless of role, will be ignored by the bot. <br />
The bot will post the live notification message to the channel from where they received these commands. <br />
The notification will mention @everyone. <br />

Commands:

!LA-watch [streamers] - Add streamer(s) to the watched list. When they go live after about 1 or so the notification they are live will be posted. Once they go offline a message will be posted as well. If the user already exists or the user doesn't exist a reply will be given notifying the poster of such.

!LA-remove [streamers] - Remove streamer(s) from the watched list.
