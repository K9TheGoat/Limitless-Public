![K9's Little Helper](https://github.com/K9TheGoat/Limitless-Public/blob/main/K9's%20Little%20Helper%20Banner.png)

![GitHub issues](https://img.shields.io/github/issues/K9TheGoat/Limitless-Public)
![GitHub pull requests](https://img.shields.io/github/issues-pr/K9TheGoat/Limitless-Public)
![GitHub Repo stars](https://img.shields.io/github/stars/K9TheGoat/Limitless-Public)
![GitHub forks](https://img.shields.io/github/forks/K9TheGoat/Limitless-Public)
![GitHub code size in bytes](https://img.shields.io/github/languages/code-size/K9TheGoat/Limitless-Public)
![Lines of code](https://tokei.queeniemella.cc/b1/github/K9TheGoat/Limitless-Public?style=flat&category=code&type=Python)
![GitHub](https://img.shields.io/github/license/K9TheGoat/Limitless-Public)
![Discord](https://img.shields.io/discord/1000727526194298910?label=Support%20Server&color=5865F2)
[![Ruff](https://img.shields.io/endpoint?url=https://raw.githubusercontent.com/astral-sh/ruff/main/assets/badge/v2.json)](https://github.com/astral-sh/ruff)

# K9's Little Helper

Official website: <Coming Soon!>

## Add Bot

[**Bot invitation link**](https://github.com/k9thegoat/limitless-public/)

Available as both a user and server app.  
When installed as a user app, you can right click a message to fix its embed or extract its media.

## Support

- [Request new fix](https://github.com/k9thegoat/limitless-public)
- [Report a bug](https://github.com/k9thegoat/limitless-public)
- [Request a new feature](https://github.com/k9thegoat/limitless-public)
- [Contribute to translations](https://github.com/k9thegoat/limitless-public)
- [Contact me on Discord](https://discord.com/invite/FTBQWCsVvq) (my username is @k9thegoatt)

## Motive

As we know, social media embeds on Discord are bad:

- Pixiv embeds don't show the full artwork
- X/Twitter sometimes doesn't embed
- Instagram doesn't show the image/video
- Reddit doesn't show the images
- Tiktok doesn't show the video
- Twitch clip doesn't play the clips
- And so on...
  
Worry no more, this Discord bot fixes all of those issues.

# Features

## Embed Fixing

Fixings are currently available for:

- **Twitter/X**: [FxEmbed](https://github.com/FxEmbed/FxEmbed)/[BetterTwitFix](https://github.com/dylanpdx/BetterTwitFix)/[EmbedEZ](https://embedez.com)
- **Pixiv**: [Phixiv](https://github.com/thelaao/phixiv)
- **TikTok**: [fxTikTok](https://github.com/okdargy/fxTikTok)/[EmbedEZ](https://embedez.com)/[KKTikTok](https://kkscript.com/)
- **Reddit**: [FixReddit](https://github.com/MinnDevelopment/fxreddit)/[vxReddit](https://github.com/dylanpdx/vxReddit)/[EmbedEZ](https://embedez.com)
- **Instagram**: [InstaFix](https://github.com/Wikidepia/InstaFix)/[EmbedEZ](https://embedez.com)/[KKInstagram](https://kkscript.com/)/[vxinstagram](https://github.com/Lainmode/InstagramEmbed-vxinstagram)/[InstaEmbedRouter](https://github.com/Knoppiix/InstaEmbedRouter)/[OGInstagram](https://github.com/LilasKR/OGInstagram)
- **FurAffinity**: [xfuraffinity](https://github.com/FirraWoof/xfuraffinity)/[fxraffinity](https://fxraffinity.net/)
- **Twitch Clips**: [fxtwitch](https://github.com/seriaati/fxtwitch)
- **Iwara**: [fxiwara](https://github.com/seriaati/fxiwara)
- **Bluesky**: [VixBluesky](https://github.com/Lexedia/VixBluesky)/[FxEmbed](https://github.com/FxEmbed/FxEmbed)
- **Kemono**: Media extraction only, no embed fixing
- **Facebook**: [EmbedEZ](https://embedez.com)/[fxfacebook](https://github.com/seriaati/fxfacebook)/[facebed](https://github.com/4pii4/facebed)
- **Bilibili**: [fxbilibili](https://github.com/seriaati/fxbilibili)/[EmbedEZ](https://embedez.com)/[BiliFix](https://vxbilibili.com)
- **Bilibili Opus**: [BiliFix](https://vxbilibili.com)
- **Tumblr**: [fxtumblr](https://github.com/knuxify/fxtumblr)
- **Threads**: [FixThreads](https://github.com/milanmdev/fixthreads)/[vxThreads](https://github.com/everettsouthwick/vxThreads)/[FixEmbed](https://fixembed.app)
- **PTT**: [fxptt](https://github.com/seriaati/fxptt)
- **DeviantArt**: [fxdeviantart](https://github.com/Tschrock/fixdeviantart)
- **Pinterest**: [EmbedEZ](https://embedez.com)
- **YouTube**: [Koutube](https://github.com/iGerman00/koutube) ([disabled by default](#about-youtube-embed-fixing))

If your message contains link(s) that are of any of the social medias above, it gets deleted and resent using a webhook with your name and avatar containing the fix. You can customize this behavior to reply instead of delete with `/settings`.

If webhook mode was used, a ❌ reaction will be added to the message, so that the author of the message can click on and delete the message. The emoji used can be changed with `/settings`.

![image](https://github.com/user-attachments/assets/e7c4469b-c5dd-44e8-b923-c8137397a64b)

> [!TIP]
> You can disable embed fixing for a specific link by adding `$` at the beginning of the link, or wrapping the link with `<>`. For example, `$https://twitter.com/...` and `<https://twitter.com/...>` will not be fixed.

### About NSFW Embed Fixing

For Pixiv and Twitter/X links, the bot checks if the artwork/post is marked as NSFW. For kemono links, posts are always assumed to be NSFW. If the channel doesn't have NSFW turned on and the artwork/post is marked as NSFW, the bot will not fix the embed.

### About EmbedEZ

Turn on "Show original link button" in `/settings` when using EmbedEZ fixes if you want to go to the original post without seeing the ads.

EmbedEZ is a service that covers many platforms for embed fixing; however, it is closed-source and has ads. I originally made a [proxy](https://github.com/seriaati/embedez) to it to bypass the ads, but it stopped working after the site owner changed some stuff.

### About YouTube Embed Fixing

YouTube embed fixing (using [Koutube](https://github.com/iGerman00/koutube)) is disabled by default. Despite having ads and a shitty player, YouTube's embed is guaranteed to work all of the time, while Koutube's embed, at least at the time of testing, sometimes doesn't get generated, or if it does, sometimes doesn't contain the video. If you want to enable it, use `/settings` and go to "Disable Embed Fixes for Websites" and uncheck YouTube.

### Opt Out of Embed Fixing

Use the `/ignore-me` command.

### Fixing Manually

Use the `/fix` command or right click a message and click "Fix Embed".

## Webhook Replying

When you reply to a webhook, it replies to the webhook, not the original author. The bot fixes this by tagging the original author with the same name of the webhook.

![image](https://iili.io/2RPjJ0Q.png)

> [!TIP]
> Add `$` at the beginning of your message to disable this feature.

## Media Extracting

The following platforms are supported:

- Twitter/X
- Pixiv
- Iwara
- Kemono
- Bluesky
- Instagram

When you send a link that is from one of the platforms above in channel(s) with this feature on, the bot resends all of the images/videos in the link in a nice gallery-like layout.  

![image](https://github.com/user-attachments/assets/2b66ed5c-bbe2-450b-92f6-d36f01bf9102)

If the link is sent in a NSFW channel, then the extracted media will be spoilered automatically (changeable).

Also, if you wrap the URL with spoiler tags, like ||<https://x.com/...>||, the extracted image(s) will be spoilered automatically.

## Very Customizable

The most powerful part about **K9's Little Helper** is that almost every behavior of the bot can be customized or toggled to your liking. It also supports niche features derived from real user demands that you probably won't find in other bots.

All settings are unique to each server, and you can use `/reset` to reset them to default values.

Below are settings you can change with the `/settings` command:

- **Language**: Change the language of the bot.
- **Disable Embed Fixes for Websites**: Disable embed fixes for specific websites. [YouTube is disabled by default](https://github.com).
- **Media Extraction Channels**: Images/Videos from Twitter/X/Pixiv/Instagram/Bluesky/Kemono links sent in these channels will be extracted.
- **Disable Media Extraction for Websites**: Links from websites selected here will not have their media extracted in media extraction channels.
- **Embed Fix Channel Blacklist**: Channels here will not receive embed fixes; whitelist has priority over blacklist.
- **Embed Fix Channel Whitelist**: Only channels set here will receive embed fixes; whitelist has priority over blacklist.
- **Disable Webhook Reply**: Disable the ping to the original author when replying to a webhook.
- **Disable Automatic Spoilering in NSFW Channels**: For the media extraction feature, NSFW channels selected here will not have media automatically spoilered.
- **Disable Delete Message Reaction**: Disable the emoji reaction on webhook messages that lets the original author delete them by reacting.
- **Show Post Content Channels**: If media extraction is enabled, channels selected here will show the content of the post.
- **Change Delete Message Reaction Emoji**: Change the emoji used to delete messages.
- **Choose Embed Fix Service**: Choose the embed fix service to use for different websites.
- **Bot Visibility**: If enabled, K9's Little Helper will fix embeds sent by other bots. If disabled, it will only fix embeds sent by users.
- **Funnel to Target Channel**: If set, all fixed embeds and extracted media will be sent to the target channel instead of the original channel.
- **Whitelist Roles**: If set, only users that have one of these roles will have their embeds fixed. Leave empty to disable.
- **Original Link Button**: Show a button linking to the original post in fixed embed messages.
- **Fix Mode**: How fixed embeds are sent.
- **Remove Reactions After**: Set the number of seconds after which the delete and switch fix reaction emojis are automatically removed. Leave a field empty to disable.
- **Rotate Fix Reaction**: When enabled, the bot adds a 🔄 reaction to fixed messages. The original author can click it to cycle to the next available embed fix service.
- **Disable Original Embed Suppression**: For the "reply" and "resend as bot" fix modes, the bot suppresses the embeds of the original message. When enabled, the original embeds are kept instead, and removing them is left to users and moderators.
- **Hide Webhook Username Suffix**: When enabled, messages resent through webhooks show the original author's name without the `" (K9's Little Helper)"` suffix.

## Post Content Translation

![Post content translation](https://githubusercontent.com)

Currently only supports Twitter/X, and only when the fix provider is [FxEmbed](https://github.com/FxEmbed/FxEmbed).

Use `/translang` to set the target language, or choose **"Disable"** to turn it off.

## Self Hosting

K9's Little Helper is powered by the open-source [Embed Fixer](https://github.com) engine by seriaati. To run your own instance:

1. Create a [Discord application](https://discord.com/developers/applications)
2. On the **Bot** page, generate a token and save it for later
3. Enable **Message Content Intent**
4. Run the application with your bot token as the `DISCORD_TOKEN` environment variable
5. Invite your bot using the invite link printed in the startup logs
6. Sync the slash commands

### Syncing Commands

The command prefix is the bot's mention by default. For example, if your bot's name is `K9's Little Helper`, the prefix is `@K9's Little Helper`.  
Run `@K9's Little Helper sync` to sync the commands, then restart or reload your Discord client (`Ctrl + R` / `Cmd + R`) to see the changes.

### Database Migrations

Changes to the database schema can be found in the upstream [`/migrations`](https://github.com/tree/main/migrations) folder.  
Migrations are applied automatically on startup for both SQLite and PostgreSQL, so no manual steps are needed.

If an upgrade ever goes wrong, pin your Docker image to the previous release tag (e.g., `ghcr.io/seriaati/embed-fixer:1.9.9`), then use `/export` and `/import` to move your settings to a fresh instance.

### Docker

With SQLite:

```sh
docker run -v /my/mnt/logs:/app/logs -v /my/mnt/data:/data -e DISCORD_TOKEN=YOUR_DISCORD_BOT_TOKEN ghcr.io/seriaati/embed-fixer:latest
```

With PostgreSQL:

```sh
docker run -v /my/mnt/logs:/app/logs -v /my/mnt/data:/data -e DISCORD_TOKEN=YOUR_DISCORD_BOT_TOKEN -e DB_URI=postgres://USERNAME:PASSWORD@DBHOST:PORT/DBNAME ghcr.io/seriaati/embed-fixer:latest-asyncpg
```

#### Volumes

- `/app/logs`: The logfiles produced by the program
- `/data`: The default location for the `embed_fixer.db` SQLite database file

#### Environment Variables

- `DISCORD_TOKEN`: Your Discord bot token
- `DB_URI`: Defaults to `sqlite:///data/embed_fixer.db`, available to customize the database location
- `ENV`: Defaults to `prod`, can be set to `dev` for development mode
- `REDIS_URL`: If set, uses Redis for caching instead of SQLite
- `PIXIV_SESSION_ID`: If set, the bot will use it to access Pixiv's API, which is required for fixing R18 Pixiv links

### Local (Without Docker)

1. Install [uv](https://docs.astral.sh/uv/getting-started/installation/)
2. Clone the [upstream repository](https://github.com)
3. Create a `.env` file:

```env
DISCORD_TOKEN=YOUR_DISCORD_BOT_TOKEN
ENV=prod
```

4. Run the bot:

```sh
uv run run.py
```
