# CodeBunny skills

Agent skills by [CodeBunny](https://profiles.wordpress.org/codebunnyhube/) for Claude and other AI agents that read `SKILL.md`.

## ScrapeLock

Protect a WordPress site from AI training crawlers (GPTBot, ClaudeBot, CCBot, Bytespider), content scrapers and fake Googlebot with the free [ScrapeLock](https://wordpress.org/plugins/scrapelock/) plugin. Claude installs it with WP-CLI, sets it up for your site, checks that AI bots and fake Googlebots are refused while real visitors are not, reads the log and helps during a scraping attack. It asks before anything that blocks more or changes server files.

Install in Claude Code:

```
/plugin install scrapelock --marketplace Code-BunnyHUB/codebunny-skills
```

On older Claude Code versions:

```
/plugin marketplace add Code-BunnyHUB/codebunny-skills
/plugin install scrapelock@codebunny
```

Or copy [`scrapelock/skills/scrapelock`](scrapelock/skills/scrapelock) to `~/.claude/skills/`. Then ask, for example: "Block AI training bots on my WordPress site but keep AI search". Claude needs WP-CLI access to the site (local, over SSH or in a container).

The plugin's source code: [Code-BunnyHUB/ScrapeLock-WP](https://github.com/Code-BunnyHUB/ScrapeLock-WP).

## License

GPL-2.0-or-later, as ScrapeLock.
