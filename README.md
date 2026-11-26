# Topics Hub with Timeback Machine™

Your Claude chats and files pile up fast. Topics Hub files them under the subjects you keep coming back to. Timeback Machine™ checks your work every day, files what is new, suggests a hub when a subject keeps coming up, and suggests ways to automate work you keep repeating, with an estimate of the time it would give back. Nothing happens until you approve it.

Free for personal use. Get it at https://doovli.app/topics-hub.html

## What is in this repository

| Path | What it is |
|---|---|
| download/Topics Hub with Timeback Machine.zip | The package people download (always the latest version): Install Guide, Setup Prompt, the page file and the Timeback Machine™ Playbook for other assistants. |
| topics.html | The current Topics Hub. The Update now button installs this file. |
| hub.html | The current topic hub page. Timeback Machine™ uses it to build hubs, and the Update now button installs it on existing hubs. |
| version.json | The current version number and release note. The daily check reads it on Mondays. |
| tasks/daily.txt | The current instructions for the Timeback Machine™ daily check. |
| install.txt | The setup instructions Claude follows when someone clicks Install in Claude on the Doovli page. |
| doovli/topics-hub.html | The Doovli page with the Install in Claude button. |

## License

(c) 2026 Rich Henderson. Shared under CC BY-NC 4.0: free to use and adapt for your own work, with credit. Not for resale or use in a paid product. Provided as is, with no warranty.

## Install as a Claude plugin

In Claude on the web or desktop: Customize, then Plugins, then Add, then Add marketplace, and enter RevCeleris/doovli-plugins. Add Topics Hub, then type "Set up my Topics Hub" in a new chat.

In Claude Code:

    /plugin install topics-hub --marketplace RevCeleris/doovli-plugins
