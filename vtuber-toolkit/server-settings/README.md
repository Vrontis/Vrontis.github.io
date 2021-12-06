---
title: Server settings
description:
---
# Server settings
## Overview
### Server Name
You can change your server name here.
### Image
You can change your server icon here.
### Inactive Channel
This is used to set after how many minutes people will be moved to an AFK VC.
### System Messages Channel
Channel where stuff like boosts, tips and welcome messages will get posted by Discord

See [Bots](../bots/README.md).
### Default Notification Settings
If you do not want to annoy everyone, set this to "Only @mentions".

It has to be toggled off for [community](./community-server.md).
### Display
- Show Boost progress bar
    - Depends on you, whether you want to have it shown. It does what it says: Shows progress on your Boost level
- Server Banner Background
    - From Boost lvl 2 onwards you can have a banner on top of your channel list. Neat.
## Roles
See [Roles](../roles/README.md)
## Emoji
- Here you can upload, rename and delete Emojis.
## Sticker
- Needs server boosts. Allows to manage server stickers.
## Moderation
- Verification Level
    - This lets you choose, what the basic requirement(s) for an account are, so that it's able to do anything.
    - Can't be used with a simple auto-join-role, since that would just override the requirement
    - Will also not affect users, who already got a role
    - Can be used, to stop *more* raiders successfully joining though.
    - I advise *at the very least* "Low". Personally I'd probably use High though. (Highest only during raids/big events that could attract the wrong people)
- Explicit Media Content Filter
    - You probably want to use "Scan media content from all members." Since most if not all will have a role.
    - What it does? Well, not even what it's supossed to do, but it's still a nice safety net.
- 2FA Requirement for moderation
    - Turn this on. Believe me. Too many servers got nuked by simple email+password scams/leaks. (Doesn't help against a certain QR feature though *sigh*)
## Audit Log
- Your basic Discord log. Neat, but bots are a bit more informative
## Integrations
- Allows you to access webhooks (refer to a different tutorial for that), channels followed (Did you know you can follow announcement channels? Now you do~) and get an overview over bots and different apps (This part seems new. Never needed it, never wanted it, but probably still nice?).
- Will also be used to configure slash command permissions sometime in the future:tm:.
## Widget
- Only if you've got a website. In this case, it should be easy enough to understand.
## Server template
- Useful for server backups.
- Believe me, you want one of these after you're done with 4).
- Use the template on a different account though, in case your primary account ever gets compromised, and your server gets deleted.
## Community
Here you can turn your server into a community server. Gives you a bunch of neat features.

For more information see [Community-Server](./community-server.md)