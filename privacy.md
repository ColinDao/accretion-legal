---
title: Privacy Policy
---

# Privacy Policy

Last updated: October 9, 2026

This policy explains what data the Clash of Clans Discord bot (the "Bot") stores, why, and how you can have it deleted. The Bot is run by an individual hobbyist, not a company.

## What the Bot stores

The Bot only stores what its features need to run.

- **Discord identifiers:** server (guild) IDs, channel IDs, role IDs, message IDs of panels the Bot posted, and the user IDs of members who use certain features.
- **Linked Clash of Clans accounts:** when a member links an account, the Bot stores their Discord user ID with the account's player tag and in-game name, and whether the link was verified. An account verified with its in-game API token is copied automatically to every other server the Bot shares with that member (still marked verified), so a member who joins another clan's server does not have to link again. Members can unlink it in any server, and it is not put back there.
- **Clan War League signups:** the accounts a member signed up, who submitted the signup, and roster assignments.
- **Support tickets:** the ticket channel ID, the ticket creator's Discord user ID, and the ticket's status. The Bot does not store the contents of ticket conversations.
- **Server settings:** tracked clan tags, feature toggles, custom welcome and rules text set by server leaders, configured YouTube channels, and the public X (Twitter) account handles a server leader chooses to follow, with the rule chosen for each.
- **Leader action log:** when a server leader changes a setting or takes a leader action through the Bot, the Bot records the actor's Discord user ID and display name at the time, what they did, and when. It also mirrors selected entries from the server's own Discord audit log for that server's leaders to see.
- **Reposted feed posts:** when a member reposts something to a server's Base Feed or Social Feed (see below), or a followed X account posts, the Bot posts a copy (the text, pictures and Clash of Clans base links) as an ordinary message in that server's feed channel. The Bot does not keep its own copy in its database. The post then lives in Discord like any other message and is governed by Discord and that server's leaders.
- **Public game data:** war and Clan War League attack history and ranked ladder history for tracked clans and linked players, obtained from the Supercell Clash of Clans API. This is public in-game data.

## What the Bot does not do

- It does not read or store the contents of your messages. It does not request the Message Content intent, so it cannot see messages in the background. The only message it ever receives is one a member deliberately selects with the **Repost to Feed** command (see below).
- It does not sell, rent, or share your data with advertisers or data brokers.
- It does not use your data for advertising or profiling.

## Repost to Feed

Repost to Feed is a right-click command on a message. It can be used by people holding a server's Manager or Moderator role, or the Manage Server permission, in a server that has set a Base Feed channel.

- When a member runs it, Discord sends the Bot that one message: its text, pictures, embeds, buttons and links, who posted it, and the server and channel it was in. The Bot receives nothing else from that server and does not see which servers the member is in.
- The Bot reposts the picture, the text and the Clash of Clans base link to the Base Feed channel of a server the member leads, and credits the member who shared it. It does not store the message, and it does not post anything in, reply to, or react in the server the message came from.
- If the message has a PDF (a base pack), the Bot downloads that file from Discord, reads the base links, pictures and text out of it while it processes it, and posts each base as its own message. It does not keep the PDF or a copy of its contents in its database. If the PDF says that sharing it is not allowed, the Bot shows the member that notice before posting, but it is the member's choice to go ahead.
- A member can use it on messages from servers the Bot has not been added to. To do that they add the Bot to their own Discord account (a "user install"). A user install gives the Bot only the ability to respond to commands that person runs. They can remove it at any time from their Discord settings.
- The Bot does not check whether a message's author agrees to it being reposted. The member who shares a post is responsible for having the right to share it (see the Terms).

## Why the data is used

Solely to provide the Bot's features to the server it was collected in: war and CWL stats, rosters, account linking, tickets, notifications, and the leader action log. Data collected in one server is not shown to another server, except that a member's token-verified accounts follow them into the other servers they are in, and public game data about a clan or player may appear in any server that tracks the same clan.

## Third parties

- **Discord:** the Bot runs on Discord and is subject to Discord's own terms and privacy policy.
- **Supercell Clash of Clans API:** the Bot sends clan and player tags to this API to retrieve public game data.
- **YouTube Data API:** used only if a server leader configures a YouTube feed, to check a public channel for new videos.
- **X (Twitter) posts through FxTwitter:** used only if a server leader follows an X account. The Bot sends that public account's handle to the third-party FxTwitter service (api.fxtwitter.com) every few minutes to read its recent public posts. No Discord user data is sent. This is an unofficial service, so it may stop working at any time.
- **Hosting:** the Bot and its database run on a privately controlled cloud virtual machine. Data is not sent to any analytics service. Copies of the database may also be kept in a separate private storage location for maintenance and debugging, and are deleted when no longer needed.

## Retention and deletion

- **Server removal:** when the Bot is removed from a server, all data stored for that server (settings, followed X accounts, links, signups, tickets, and the leader action log) is deleted automatically. Posts the Bot already made in your server's channels stay there, since they are ordinary Discord messages.
- **Leaders** can clear a server's data at any time using the Bot's Clear Database option (public war and ranked history is not part of this, see below), and can unlink accounts.
- **Members** can unlink their own accounts through the Bot. To have any other data tied to your Discord user ID deleted, contact us using the details below and include your Discord user ID.
- Public war and ranked history keyed by clan or player tag is kept as public game data and is not tied to a Discord server. You may request removal of history for a player tag you own.
- Daily backups of the database are kept for 14 days and then deleted. They are stored on the hosting server, and a copy of the newest backup is also kept each day in a separate private storage location, likewise for 14 days. Data deleted from the live database leaves the backups within that window.
- When you ask for deletion, your linked accounts, your own signups, and your tickets are deleted. Your name and ID are removed from leader action log entries. The rest of the log stays, since it belongs to the server's leaders.

## Security

Data is stored on a server with restricted access, and the Bot's credentials are kept out of public code. No system is perfectly secure, and we cannot guarantee absolute security.

## Children

The Bot is only available through Discord, which requires users to be at least 13 (or the minimum age in their country). We do not knowingly collect data from anyone younger.

## Your rights

Depending on where you live, you may have the right to access, correct, or delete the data we hold about you. Contact us and we will respond within a reasonable time.

## Changes

If this policy changes, the "Last updated" date above will change. Continued use of the Bot after a change means you accept it.

## Contact

Email: accretion.support@gmail.com  
Discord: limmeru

This Bot is not affiliated with, endorsed by, or sponsored by Supercell or Discord.
