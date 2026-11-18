# **Privacy Policy**

**Effective Date:** 17th November 2026

## 1. **Introduction**
This Privacy Policy outlines how K9's Little Helper collects, uses, stores, and protects data as a Discord bot. By using K9's Little Helper, you agree to these data practices.

## 2. **Data Collection**
The bot stores the following in its local SQLite database:
- **Guild & User Settings:** Configurations set via `/settings`, `/translang`, and `/user-settings` (such as language, disabled websites, fix modes, channels, and roles) and opt-out preferences (`/ignore-me`).
- **Fixed Message Records:** Metadata for messages sent by the bot (message, guild, and channel IDs, author ID, delivery method, and timestamp) to support features like delete/rotate reactions and webhook mentions.

Message content is processed temporarily to rewrite supported links and is not stored in the database, though URLs may appear briefly in local log files or temporary in-memory request caches.

## 3. **Data Usage & Storage**
Collected data customizes bot features and assists with debugging. It is never sold, used for advertising, or used to train machine learning/AI models. Data is kept in a local SQLite database on a private machine maintained by the developer; the system is password-protected, though the database file itself is unencrypted.

## 4. **Data Sharing**
Data is not shared with third parties except when essential for core functionality:
- **Embed Fix Services & Post APIs:** Links are rewritten to third-party services (e.g., FxEmbed, Phixiv) or queried via APIs (e.g., Pixiv, Bluesky, Kemono) to extract media, check NSFW status, and generate embeds.

## 5. **Data Retention**
- **Settings & Opt-Outs:** Retained indefinitely until deletion is requested.
- **Fixed Message Records:** Automatically deleted after 90 days or immediately upon message deletion.
- **Log Files & Cache:** Logs delete automatically after 2 weeks; request cache entries clear after 10 minutes.

## 6. **Security & User Rights**
The host environment is password-protected. Guild owners and users can request data access, modification, or deletion, or opt out at any time using `/ignore-me` (or by prefixing a link with `$` or `<>`).

## 7. **Contact & Policy Changes**
For inquiries, contact the developer at <k9thegoatt@hotmail.com> or on Discord at `@k9thegoatt`. This policy may change at any time without direct notification to users.