# Smart Connect

<h3 align="center">Give context to ChatGPT without giving your files to the cloud<br><small>Smart Connect creates a connection that you control between your local computer and ChatGPT</small></h3>
<p align="center">
  <a href="https://smartconnections.app/story/smart-connect-getting-started/" target="_external">
    <img src="https://smartconnections.app/assets/Setup-Custom-GPT-Actions-Smart-Connect-new-custom-gpt-2025-09-03.png" alt="Smart Connect app" width="300"/>
  </a>
</p>

Designed for Obsidian users, developers, and anyone who wants ChatGPT to work with local notes, files, and tools without uploading everything to a cloud.

**Who is this for**  
You want ChatGPT to actually use your files and tools. You value privacy and control. You prefer a simple setup that shows what is happening.

## Install

| [Windows](https://github.com/brianpetro/smart-connect/releases/latest/download/Smart-Connect-Setup-win.exe) | [Mac](https://github.com/brianpetro/smart-connect/releases/latest/download/Smart-Connect-Setup-mac.dmg) | [Linux (.deb)](https://github.com/brianpetro/smart-connect/releases/latest/download/Smart-Connect-Setup-linux-amd64.deb) | [Linux (.AppImage)](https://github.com/brianpetro/smart-connect/releases/latest/download/Smart-Connect-Setup-linux-x86_64.AppImage) |
|---|---|---|---|

<details open>
  <summary><strong>TLDR</strong> simple 3 step plan</summary>
  <ul>
    <li>Install Smart Connect using the links above.</li>
    <li>Start a Smart Environment and sign in when prompted to enable Official GPTs.</li>
    <li>Chat in your Official or Custom GPT and call Smart Actions on your machine.</li>
  </ul>
</details>

## Getting started

Create and start an environment, sign in to enable Official service, auto setup a Custom GPT or copy the local API key for manual setup, and import MCP servers to bring external tools into GPTs.  
[Open the full slideshow ->](https://smartconnections.app/story/smart-connect-getting-started/)

[![Manager Environments annotated](https://smartconnections.app/assets/annotated/SC%20App%20-%20Manager%20win%20Environments%20tab%20annotated-2025-09-08.png)](https://smartconnections.app/story/smart-connect-getting-started/)
[![Connection settings annotated](https://smartconnections.app/assets/annotated/SC%20App%20-%20Manager%20win%20Connection%20settings%20tab%20annotated-2025-09-08.png)](https://smartconnections.app/story/smart-connect-getting-started/)
[![Environment settings annotated](https://smartconnections.app/assets/annotated/SC%20App%20-%20Env%20win%20settings%20tab%20annotated-2025-09-08.png)](https://smartconnections.app/story/smart-connect-getting-started/)

## How it works

Smart Connect runs on your computer. It opens a private, inspectable path that GPTs can use to call Smart Actions. You approve the actions and you can read the logs.

- Local first by default  
- No bulk upload of your vault or files  
- Approve once then chat normally  
- Readable logs for every call

## Do more on day one

- Use an Official GPT to work with notes and files without building a Custom GPT  
- Build a Custom GPT from selected actions when you want extra control  
- Import MCP servers so tools they expose become Smart Actions callable in ChatGPT  
- Keep Obsidian integration first class with a single toggle in settings

## MCP server integration

Bring your MCP tools into GPTs in minutes. Any tool an MCP server exposes can be called as a Smart Action in normal chats.

- Open the MCP servers tab in your environment  
- Pick a transport  
- Enter the start command or URL  
- Toggle the server on to import tools

[Watch the pre-release preview](https://www.loom.com/share/99b8454bcd5e4be4932115fcb903a5ef) from a recent [Community Lean Coffee](https://luma.com/calendar/cal-ZJtdnzAdURyouM7) meeting.

<blockquote>
  <strong>Note</strong> Smart Connect uses GPTs to call imported MCP tools. That means any tool an MCP server exposes works in chat. The search and fetch constraint applies to native ChatGPT connectors, not to Smart Connect.
</blockquote>

**What this unlocks**  
Universal chat flows that call tools like browser automation, file utilities, or app connectors, all from GPTs. There is no search or fetch gate inside Smart Connect. You choose which tools are on.

![MCP server tabs annotated](https://smartconnections.app/assets/annotated/SC%20App%20-%20Env%20win%20MCP%20server%20tabs%20annotated-2025-09-07.png)

## Official service

Use the Official service for a no code path that works with your vault and Smart Actions.

- Sign in with your email and connection key in <kbd>Manager</kbd> -> <kbd>Connection</kbd>  
- Official GPT calls route through the secure service  
- No need to copy a local API key for Official GPTs

**Do I have to pay?**  
No. You can use Smart Connect without the Official service by hosting your own connection server and creating your own Custom GPTs. The Official service exists to make setup easier and to support the project.

![Official service sign in and local key](https://smartconnections.app/assets/annotated/SC%20App%20-%20Manager%20win%20Connection%20settings%20tab%20annotated-2025-09-08.png)

## Custom GPTs

When you want a custom system prompt or your own action set.

- Start a Smart Environment, open the **Custom GPT** tab, then use **Auto setup** or copy the URL and **Local API key** for manual setup  
- In the GPT builder, **Add Actions** and **Import from URL**, then set **Bearer API Key** to your Local API key  
- Paste the GPT URL back into Smart Connect so calls map to the correct action group  
[Read the Custom GPT setup guide ->](https://smartconnections.app/setup-custom-gpt-actions/)

![Custom GPT auto setup](https://smartconnections.app/assets/annotated/SC%20App%20-%20Env%20win%20Custom%20GPT%20tabs%20annotated-2025-09-08.png)

## Smart Environment

**When** AI tools pull you into cloud silos and hidden data flows.  
**How** a local Smart Environment defines where AI can act, with settings you can read. Pick a folder, toggle Obsidian vault on if applicable, start the environment.  
**Result** Local embeddings by default so ChatGPT can use semantic search without sending all of your files to the cloud.

![Smart Environment settings](https://smartconnections.app/assets/annotated/SC%20App%20-%20Env%20win%20settings%20tab%20annotated-2025-09-08.png)

## Core actions

**When** you need useful actions and cannot install MCP servers right now.  
**How** Smart Connect ships with core actions designed to enable essential interactions between ChatGPT and your local Smart Environment.  
**Result** Create notes and use embedding retrieval right away. Your GPT can create, read, and update notes and call imported tools.

Examples:

- Notes: create note at path, lookup notes about concept, list notes in folder

![Actions tab annotated](https://smartconnections.app/assets/annotated/SC%20App%20-%20Env%20win%20actions%20tab%20annotated-2025-09-08.png)

## Easy setup with Official service

**When** setup friction kills momentum.  
**How** Official service provides an easy connection plus access to the Official GPTs so you can get started in minutes.  
**Result** Sign in once in **Smart Connect -> Connection**, open an Official GPT, and start calling actions.

![Connection settings annotated](https://smartconnections.app/assets/annotated/SC%20App%20-%20Manager%20win%20Connection%20settings%20tab%20annotated-2025-09-08.png)

## Obsidian integration

**When** ChatGPT cannot see your live notes.  
**How** toggle the Obsidian vault switch in Smart Environment settings.  
**Result** use the Notes GPTs to retrieve notes. Includes deep integration like rendering dataviews.  
- _Note: bases rendering coming soon._

## FAQs

**Do I have to pay for the Official service to use Smart Connect?**  
No. You can self-host a connection server that links your local Smart Connect with ChatGPT. Only the Official GPTs require the Official service.

**Is Smart Connect MCP integration limited to search and fetch tools?**  
No. Unlike the native connector, Smart Connect runs tools through GPT actions. Any tool an imported MCP server exposes can be used this way.

**Does this require a ChatGPT Plus subscription?**  
Custom GPT creation requires Plus. Official GPTs can be used with a free plan but usage and results may be limited.

**Can I create my own Smart Actions?**  
Yes. You can add modules written or compiled to JavaScript.

## Troubleshooting

**Where to look first**  
- Click **Logs** in the Manager window for request and response details.  
- Use the **console** tab to capture errors and share the screenshots in a [new issue](https://github.com/brianpetro/smart-connect/issues).

## Learn more

- [Full getting started slideshow](https://smartconnections.app/story/smart-connect-getting-started/)  
- [Smart Connect Official Service](https://smartconnections.app/smart-connect/)