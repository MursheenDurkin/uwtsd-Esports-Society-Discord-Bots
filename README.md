<p align="center">
  <h1 align="center">Atlas</h1>
  <p align="center">Esports Management Bot for the UWTSD Esports Society</p>
</p>

<p align="center">
  <img src="https://img.shields.io/badge/discord.py-2.x-5865F2?logo=discord&logoColor=white" alt="discord.py">
  <img src="https://img.shields.io/badge/status-live-green" alt="Status">
</p>

---

## What is Atlas?

Atlas is the dedicated esports operations bot for the **UWTSD Esports Society** Discord server. It handles everything competitive — player registration, rank tracking, team management, tournaments, events, and more.

Atlas works alongside **Spot** (the society's general server management bot). Spot handles moderation, verification, and community features. Atlas handles the competitive side.

## Full Documentation

For detailed guides on every feature, visit the **[Atlas Wiki](https://github.com/MursheenDurkin/atlas-docs/wiki)**.

### Quick Links

| Page | Description |
|------|-------------|
| [Getting Started](https://github.com/MursheenDurkin/atlas-docs/wiki/Getting-Started) | How to register and set up your profile |
| [Rank Tracking](https://github.com/MursheenDurkin/atlas-docs/wiki/Rank-Tracking) | Automatic and manual rank tracking |
| [Teams & Rosters](https://github.com/MursheenDurkin/atlas-docs/wiki/Teams-&-Rosters) | Team structure, roster management, captain commands |
| [Tournaments](https://github.com/MursheenDurkin/atlas-docs/wiki/Tournaments) | Joining and following tournaments |
| [Events & Practice](https://github.com/MursheenDurkin/atlas-docs/wiki/Events-&-Practice) | Events, practice sessions, RSVP, attendance |
| [VOD Review](https://github.com/MursheenDurkin/atlas-docs/wiki/VOD-Review) | Submitting gameplay for coaching feedback |
| [Stats Dashboard](https://github.com/MursheenDurkin/atlas-docs/wiki/Stats-Dashboard) | Player, team, and server statistics |
| [Committee Guide](https://github.com/MursheenDurkin/atlas-docs/wiki/Committee-Guide) | Admin commands and management tools |
| [Captain's Guide](https://github.com/MursheenDurkin/atlas-docs/wiki/Captains-Guide) | Everything a team captain needs to know |

## Supported Games

### Automatic Rank Tracking
| Game | Player Identifier |
|------|-------------------|
| VALORANT | Riot ID (`Name#TAG`) |
| League of Legends | Riot ID (`Name#TAG`) |
| Counter-Strike 2 | Steam ID or vanity URL |
| Apex Legends | Origin / EA username |

### Manual Submission (all games)
| Game | Queue Types |
|------|-------------|
| Overwatch 2 | Tank, Damage, Support, Open Queue |
| Fortnite | Build, Zero Build |
| Rocket League | 1v1, 2v2, 3v3 |
| Rainbow Six Siege | Ranked, Unranked |

## Command Overview

### Everyone
| Command | Description |
|---------|-------------|
| `/register` | Register as a competitive player |
| `/myprofile` | View your player profile |
| `/ranktrack add` | Register for automatic rank tracking |
| `/rank` | Check your current rank |
| `/rankhistory` | View rank change timeline |
| `/ranklb` | Server leaderboard |
| `/ranksubmit` | Submit rank manually with screenshot |
| `/submissionstatus` | Check submission status |
| `/teams` | View all teams |
| `/myteams` | View your team memberships |
| `/roster view` | View your team's roster |
| `/tournament list` | View open tournaments |
| `/tournament join` | Register for a tournament |
| `/tournament info` | Tournament details |
| `/tournament standings` | W/L standings |
| `/tournament matches` | View matches |
| `/event list` | Upcoming events |
| `/practice list` | Upcoming practices |
| `/myschedule` | Your personal schedule |
| `/vod submit` | Submit gameplay for review |
| `/vod myvods` | Your VOD submissions |
| `/vod feedback` | View VOD feedback |
| `/dashboard player` | Player stats |
| `/dashboard team` | Team stats |
| `/dashboard server` | Server overview |

### Captain Commands
| Command | Description |
|---------|-------------|
| `/roster add` | Add a player to your team |
| `/roster remove` | Remove a player |
| `/roster promote` | Sub → Starter |
| `/roster demote` | Starter → Sub |
| `/roster transfer` | Move player to another team |
| `/roster announce` | Post team announcement |
| `/roster availability` | Weekly availability check |
| `/roster scrim` | Schedule a scrim |
| `/tournament addplayer` | Add player to tournament team |
| `/practice create` | Create practice session |
| `/practice schedule` | Set up recurring practice |
| `/practice attendance` | Mark attendance |

### Committee Commands
| Command | Description |
|---------|-------------|
| `/player view` | View full player profile + notes |
| `/player search` | Search players by name/username |
| `/player note` | Add committee note to profile |
| `/player status` | Change player status |
| `/player history` | View profile timeline |
| `/applications` | Pending applications |
| `/team create` | Create a new team |
| `/team delete` | Delete a team |
| `/team setcaptain` | Change team captain |
| `/team list` | List all teams |
| `/tournament create` | Create tournament |
| `/tournament close` | Close registration |
| `/tournament start` | Start tournament |
| `/tournament end` | End tournament |
| `/tournament delete` | Delete tournament |
| `/tournament addmatch` | Create a match |
| `/tournament result` | Record match result |
| `/tournament announce` | Announce to all participants |
| `/event create` | Create an event |
| `/event cancel` | Cancel an event |
| `/practice stats` | View attendance stats |
| `/vod assign` | Assign reviewer to VOD |
| `/rankadmin forcecheck` | Force rank check |
| `/rankadmin setchannel` | Set rank updates channel |
| `/rankadmin removeplayer` | Remove rank tracking |
| `/rankadmin clearhistory` | Clear rank history |
| `/rankadmin stats` | Tracking statistics |
| `/guide registration` | Post registration guide |
| `/guide ranks` | Post rank tracking guide |
| `/guide teams` | Post teams guide |
| `/guide tournaments` | Post tournaments guide |
| `/guide events` | Post events guide |
| `/guide vod` | Post VOD guide |
| `/guide all` | Post all guides |

---

## Ownership & Continuity Policy

Atlas was designed, built, and is maintained solely by **Durkin** — President of UWTSD Esports Society at the time of the bot's creation.

The bot is made available to the society at the discretion of its creator. The following terms apply regardless of any future leadership changes within the society:

- **Ownership** of the bot, its codebase, and all infrastructure remains with Durkin at all times. This does not transfer as part of any society handover.
- When a new President takes over, the incoming leadership is welcome to continue using Atlas in the server. It will be suggested that the bot remains in place as-is — it will simply continue to run as it always has.
- However, the bot will remain under Durkin's control regardless of who holds the President role. Access credentials, hosting, and the codebase are not part of the society's assets.
- If incoming leadership is not comfortable with these terms, that is entirely their prerogative — they are free to seek alternative solutions. The bot will not be handed over, forked, or transferred under any circumstances.
- **Atlas is not included in the society handover. Full stop.**

> *"I built it, I own it. You're welcome to use it — but it stays mine."*
> — **Durkin**, Founding President & Developer

---

<p align="center">
  Built for the UWTSD Esports Society
</p>
