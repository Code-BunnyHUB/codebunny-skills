# Privacy policy: CodeBunny skills

The skills in this repository (including **ScrapeLock**) are instructions that Claude reads. They contain no code that runs on their own, no analytics and no tracking.

- The skills collect, store and send **no data** to CodeBunny or anyone else.
- When you use the ScrapeLock skill, Claude runs WP-CLI commands on the WordPress site you give it access to, on your own machine or server. What those commands read or change stays there.
- Some of those commands show ScrapeLock's own logs, which hold visitors' **IP addresses**, User-Agents, addresses requested and, for failed sign-ins, the **usernames tried**. Claude reads them in your conversation to answer you (for example "what has been blocked?"). The skill does not copy, store or send them anywhere.
- The ScrapeLock WordPress plugin itself keeps its logs in your own database and sends no visitor data anywhere by default. The public IP lists it downloads (Google, Bing, Cloudflare and others) are listed under "External services" in its [readme](https://wordpress.org/plugins/scrapelock/).
- Your conversations with Claude are covered by Anthropic's privacy policy, not by this one.

Questions: open an issue at https://github.com/Code-BunnyHUB/codebunny-skills/issues or use the plugin's [support forum](https://wordpress.org/support/plugin/scrapelock/).
