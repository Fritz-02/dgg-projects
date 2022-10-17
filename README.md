# dgg-projects

## [DGG-Bot](https://github.com/Fritz-02/dgg-bot)
A python library for interacting with Destiny.gg's chat websocket. Besides just being able to make a chat bot (such as the [Emotes bot](https://github.com/tenacious210/dgg-emotes-bot) by [tena](https://tena.dev)), it can be used to just connect to and read chat in general (e.g. [dgg-relay](https://github.com/tenacious210/dgg-relay) by tena).

## [DGG Scripts](https://github.com/Fritz-02/dgg-scripts)
Various userscripts for DGG. I only use Tampermonkey so there may be issues with other userscript extensions. All settings for each script are in DGG settings (cog wheel below chat, scroll down to see all settings).

 - [Ignore Except When Tagged](https://raw.githubusercontent.com/Fritz-02/dgg-scripts/main/ignoreExceptWhenTagged.js): does what /ignore does, except you'll see messages you're tagged in. Ignores are separated into regular ignores and harsh ignores.
 - [NSFW ignorer](https://raw.githubusercontent.com/Fritz-02/dgg-scripts/main/ignoreNSFW.js): don't want to see a specific chatter's NSFW links, but don't want to flat out /ignore them? Go into settings and plop their name under "Ignored NSFW posters".
 - [Link Shortener](https://raw.githubusercontent.com/Fritz-02/dgg-scripts/main/linkShortener.js): tired of nnn's extremely long NSFW links? This will shorten all links longer than a certain length (by default 150 characters), and optionally you can have it just shorten NSFW links if you enjoy super long SFW links.
 - [No White Links](https://github.com/Fritz-02/dgg-scripts/blob/main/noWhiteLinks.js): afraid of clicking a random white name's link and accidently seeing something that will make the FBI come visit you? This will redact those links.
 - [Mentions/Stalk Fixed](https://raw.githubusercontent.com/Fritz-02/dgg-scripts/main/mentionsStalkFixed.js): while OverRustle is down, this brings back the /mentions and /stalk commands using Rustlesearch.dev
