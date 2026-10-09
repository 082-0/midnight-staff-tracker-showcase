# 09

![JavaScript](https://img.shields.io/badge/JavaScript-F7DF1E?logo=javascript&logoColor=black) ![HTML](https://img.shields.io/badge/HTML-E34F26?logo=html5&logoColor=white) ![CSS](https://img.shields.io/badge/CSS-663399?logo=css&logoColor=white)

A Discord staff bot and private control room, built for **[Midnight Community](https://discord.gg/midnightt)**.

**Created by 082_0** · [GitHub](https://github.com/082-0) · Discord: `082_0`

## Control room

![Staff control room](dashboard.png)

Track the team, award points, review saved activity and configure each server from one dashboard.

## Features

- Ten-place Discord leaderboard with staff profiles and a personal rank button.
- Automatic message and voice tracking, including members who appear offline. Voice time accumulates across sessions, with a configurable minimum of 2–5 human participants.
- Point awards and deductions with optional reasons, no default weekly cap, and point receipts.
- Staff lookup with roles, account age, voice channel and saved activity.
- Private verification rooms for the joining member and the configured staff team. Staff complete verification through Vynel; completion logs feed the existing points tracker.
- Weekly comparison, meeting summaries and CSV exports.
- Separate settings and data for each server.
- Slash commands and configurable server text prefixes.
- Configurable leaderboard updates, every two minutes by default.
- Optional 30-day remembered sign-in with secure session cookies.

## Bot health

The control room now includes a dedicated **Bot health** page for each server:

- Connection status based on the latest received bot update.
- Last successful sync, displayed in the server dashboard timezone.
- Full count of pending website changes.
- Recent saved and failed changes, with their results.
- A manual refresh button and automatic status updates.

A delayed sync is shown separately from a confirmed connection; it does not automatically mean the Discord bot stopped tracking.

## Manage points

![Manage points](manage-points.png)

Add or remove points from the dashboard or use `/points add` and `/points remove` in Discord.

## Verification rooms

![Verification rooms](verification-rooms.png)

Configure a lobby channel and staff role by ID. Members receive a private room when they join the lobby. Empty managed rooms are cleaned up automatically.

## About this repository

This is a **showcase**, containing documentation and screenshots only. The bot source, credentials and production records are private. Screenshots use demonstration data.

[Join Midnight Community](https://discord.gg/midnightt)
