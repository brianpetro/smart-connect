# Smart Connect

<h3 align="center"> Give context to ChatGPT without giving your files to the cloud<br> <small>Smart Connect creates a connection you control between your local computer and ChatGPT</small> </h3> <p align="center"> <a href="https://smartconnections.app/story/smart-connect-getting-started/" target="_external"> <img src="https://smartconnections.app/assets/Setup-Custom-GPT-Actions-Smart-Connect-new-custom-gpt-2025-09-03.png" alt="Smart Connect app" width="300"/> </a> </p>

Designed for Obsidian users, developers, and anyone who wants ChatGPT to work with local notes, files, and tools without uploading everything to a cloud.

<blockquote> <p>**Who is this for**<br> You want ChatGPT to actually use your files and tools. You value privacy and control. You prefer a simple setup that shows what is happening.</p> </blockquote>

## Install

|[Windows](https://github.com/brianpetro/smart-connect/releases/latest/download/Smart-Connect-Setup-win.exe)|[Mac](https://github.com/brianpetro/smart-connect/releases/latest/download/Smart-Connect-Setup-mac.dmg)|[Linux (.deb)](https://github.com/brianpetro/smart-connect/releases/latest/download/Smart-Connect-Setup-linux-amd64.deb)|[Linux (.AppImage)](https://github.com/brianpetro/smart-connect/releases/latest/download/Smart-Connect-Setup-linux-x86_64.AppImage)|
|---|---|---|---|

<details open> <summary>**TLDR** simple 3 step plan</summary> <ul> <li>Install Smart Connect using the links above.</li> <li>Start a Smart Environment and sign in when prompted to enable Official GPTs.</li> <li>Chat in your Official or Custom GPT and call Smart Actions on your machine.</li> </ul> </details>

## Getting started
[Open the full slideshow →](https://smartconnections.app/story/smart-connect-getting-started/)

<details> <summary>**What you will see**</summary> <p>Create and start an environment, sign in to enable Official service, auto setup a Custom GPT or copy the local API key for manual setup, and import MCP servers to bring external tools into GPTs.</p> </details>

## How it works

<details open> <summary>**Plain language**</summary> <p>Smart Connect runs on your computer. It opens a private, inspectable path that GPTs can use to call Smart Actions. You approve the actions and you can read the logs.</p> </details>

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
Bring your MCP tools into GPTs in minutes. Any tool an MCP server exposes can be called as a Smart Action.
- Open the **MCP servers** tab in your environment
- Pick a transport
- Enter the start command or URL
- Toggle the server on to import tools
    

<p> <a href="https://www.loom.com/share/99b8454bcd5e4be4932115fcb903a5ef" target="_external">Watch the pre-release preview</a> from a recent <a href="https://luma.com/calendar/cal-ZJtdnzAdURyouM7" target="_external">Community Lean Coffee</a> meeting. </p> <p> <img src="https://smartconnections.app/assets/annotated/SC%20App%20-%20Env%20win%20MCP%20server%20tabs%20annotated-2025-09-07.png" alt="Import MCP server tools" width="720"/> </p> <details> <summary>**What this unlocks**</summary> <p>Universal chat flows that call tools like browser automation, file utilities, or app connectors, all from GPTs. There is no search or fetch gate inside Smart Connect. You choose which tools are on.</p> </details>

## Official GPTs
**Smart Connect - Obsidian GPT**  
Use the Official service for a no code path that works with your vault and Smart Actions.
- Sign in with your email and connection key in <kbd>Manager</kbd> → <kbd>Connection</kbd>
- Official GPT calls route through the secure service
- No need to copy a local API key for Official GPTs
    

<details> <summary>**Do I have to pay**</summary> <p>No. You can use Smart Connect without the Official service by hosting your own connection server and creating your own Custom GPTs. The Official service exists to make setup easier and to support the project.</p> </details>

## Custom GPTs
When you want a custom system prompt or your own action set.
- Start a Smart Environment, open the **Custom GPT** tab, then use **Auto setup** or copy the URL and **Local API key** for manual setup
- In the GPT builder, **Add Actions** and **Import from URL**, then set **Bearer API Key** to your Local API key
- Paste the GPT URL back into Smart Connect so calls map to the correct action group
[Read the Custom GPT setup guide →](https://smartconnections.app/setup-custom-gpt-actions/)

<p> <img src="https://smartconnections.app/assets/annotated/SC%20App%20-%20Env%20win%20Custom%20GPT%20tabs%20annotated-2025-09-08.png" alt="Custom GPT auto setup" width="600"/> </p>

## Smart Environment
- AI tools pull you into cloud silos and hidden data flows.
- A local Smart Environment defines where AI can act, with settings you can read.
	- Pick a folder, toggle Obsidian vault on if applicable, start the environment.
- **Local embeddings by default** so ChatGPT can use semantic search without sending all of your files to the cloud.
	- Already using the Obsidian Smart Connections plugin? Smart Connect uses the same embeddings and Smart Environment architecture.
        

<p> <img src="https://smartconnections.app/assets/annotated/SC%20App%20-%20Env%20win%20settings%20tab%20annotated-2025-09-08.png" alt="Smart Environment settings" width="720"/> </p>

## Core actions
- You need useful actions and can't install MCP servers.
- Smart Connect ships with core actions designed to enable essential interactions between ChatGPT and your local Smart Environment.
- Create notes and use embedding retrieval right away.
- Your GPT can create, read, and update notes and call imported tools.
    

Examples:
- Notes: create note at path, lookup notes about concept, list notes in folder
    

## Easy setup with Official Service
- Setup friction kills momentum.
- Official service provides an easy connection plus access to the Official GPTs so you can get started in minutes.
- Sign in with your connection key in **Smart Connect → Connection**.
- Open an Official GPT and start calling actions.
    

<p> <img src="https://smartconnections.app/assets/annotated/SC%20App%20-%20Manager%20win%20Connection%20settings%20tab%20annotated-2025-09-08.png" alt="Official service sign in and local key" width="720"/> </p>

## Obsidian integration
- ChatGPT cannot see your live notes.
- Toggle the Obsidian vault switch in Smart Environment settings.
- Use the Notes GPTs to retrieve notes. Includes deep integration like rendering dataviews.
	- *Bases rendering coming soon!*
        

## FAQs

**Do I have to pay for the Official service to use Smart Connect**  
No. You can self-host a connection server that links your local Smart Connect with ChatGPT. Only the Official GPTs require the Official service.

**Is Smart Connect MCP integration limited to search and fetch tools**  
No. Unlike the native connector, Smart Connect runs tools through GPT actions. Any tool an imported MCP server exposes can be used this way.

**Does this require a ChatGPT Plus subscription**  
Custom GPT creation requires Plus. Official GPTs can be used with a free plan but usage and results may be limited.

**Can I create my own Smart Actions**  
Yes. You can add modules written or compiled to JavaScript.

## Troubleshooting
**Where to look first**
- Click **Logs** in the Manager window for request and response details.
- Use the **console** tab to capture errors and share the screenshots in a [new issue](https://github.com/brianpetro/smart-connect/issues).

## Learn more
- [Full getting started slideshow](https://smartconnections.app/story/smart-connect-getting-started/)
- [Smart Connect Official Service](https://smartconnections.app/smart-connect/)
