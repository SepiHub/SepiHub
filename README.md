# Hi, I'm Seph 👋

I build World of Warcraft addons in Lua for the WoW: Forever client, and websites for the community around the game. I like small tools that are fast and quiet in game: they show players useful numbers and stay out of the way.

<!-- Add a line about what you're looking for, e.g. "Looking for a junior developer role in ..." -->

## Projects

### [GatheringGoldCalculator](https://github.com/SepiHub/GatheringGoldCalculator) · my own addon
Shows how much gold your gathering is worth while you play, for Mining, Herbalism, Skinning and Fishing.
- Floating gold value text for every gather, plus a session box with gold per hour
- Session history and per-resource totals for each character, with sortable columns
- Live prices read from the Auctionator addon's public API, with vendor price as a fallback
- Handles Forever-specific API differences and moves saved data forward safely between versions

### [GuildWrapped](https://github.com/SepiHub/GuildWrapped) · my own website · [live site](https://sepihub.github.io/GuildWrapped/)
A Spotify Wrapped-style yearly recap for the Gay Furries of Azeroth guild. Every guildmate gets a character card, and tapping it plays their year in the guild as a slide-by-slide story.
- Story slides built from in-game data: mobs and quests, dungeons and bosses, loot, professions, deaths, attunements and video clips. Slides with no data are skipped.
- Guildmates only need to paste an export code from the guild addon. The site checks it (CRC32) and decodes it into a character entry, so they don't need a GitHub account.
- Version history for each character, with a "Since last time" slide that compares the new export to the previous one
- Ten card themes, a picture carousel and a full-screen viewer
- Plain HTML, CSS and JavaScript with no framework, hosted on GitHub Pages

### [GFoA Guild Sync](https://github.com/Harl3yVT/gfoa-guildsync) · contributor
The guild addon for Gay Furries of Azeroth: guild crafters in tooltips, alts, levelling buddy, cooldowns and a pre-raid checklist. I work on it with the project's owner, mostly on the guild leaderboards. **7 pull requests merged**, including:
- **Overall leaderboard tab** showing class, level, time played, professions and top hit ([#15](https://github.com/Harl3yVT/gfoa-guildsync/pull/15), [#19](https://github.com/Harl3yVT/gfoa-guildsync/pull/19), [#20](https://github.com/Harl3yVT/gfoa-guildsync/pull/20))
- **World PvP kill board** that leaves out battlegrounds and raid groups ([#13](https://github.com/Harl3yVT/gfoa-guildsync/pull/13)), and a fix for a board stuck at 0 kills ([#22](https://github.com/Harl3yVT/gfoa-guildsync/pull/22))
- Smaller UI improvements: gold, silver and copper colored money text ([#14](https://github.com/Harl3yVT/gfoa-guildsync/pull/14)), and a "Reset XP/hour" option in the minimap menu ([#12](https://github.com/Harl3yVT/gfoa-guildsync/pull/12))

→ [All my commits](https://github.com/Harl3yVT/gfoa-guildsync/commits?author=SepiHub) · [All my pull requests](https://github.com/Harl3yVT/gfoa-guildsync/pulls?q=author%3ASepiHub)

## Tools

Lua · WoW addon API · HTML, CSS & JavaScript · GitHub Pages · Git & GitHub · AI-assisted development (Claude Code)

<!-- Optional: add a way to contact you, e.g. email or LinkedIn -->
