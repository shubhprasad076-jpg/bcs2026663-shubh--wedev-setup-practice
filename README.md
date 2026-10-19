# Web Development Day 01 Setup Practice

**Student:** `SHUBH PRASAD 
**Roll number:** bcs2026663`  
**GitHub repository:** [`<rollno>-<firstname>-webdev-day01-setup-practice`](<paste-your-GitHub-repository-link-here>)

This repository contains my setup work and practice tasks for Web Development Day 01.

## Setup checklist and evidence

- [ ] **Explain how a web page loads:** Write one paragraph describing what happens after entering a URL and before the page appears. Mention the browser, DNS lookup, server request/response, and rendering the returned files.
- [ ] **Verify the development tools:** Install VS Code, Node.js, and the Live Server extension. Add a screenshot proving the tools are installed. Save it in this repository, for example as `screenshots/tool-installation.png`, and link it here: [Tool installation screenshot](screenshots/tool-installation.png).
- [ ] **Make at least three meaningful commits:** Use clear messages that describe different pieces of work. Check the history with `git log --oneline`.
- [ ] **Share the pushed repository link:** Paste the public GitHub repository URL above and confirm the project files are visible on GitHub.
- [ ] **Complete terminal navigation practice:** Save the completed practice sheet in this repository, for example as `terminal-practice.md`.
- [ ] **Inspect website network requests:** Use Chrome DevTools on a live website. Open DevTools → **Network**, reload the page, and record the website inspected, a few request URLs or resource types, and what you noticed. Save notes in `network-inspection.md`.
- [ ] **Install and verify every required tool:** Record tool names and versions or verification steps below. Create the first project workspace.
- [ ] **Create the project folder structure using only the terminal:** Record the commands used, or include them in `terminal-practice.md`.
- [ ] **Initialize Git in the semester practice folder and make the first commit:** Confirm the initial commit appears in `git log --oneline`.
- [ ] **Create a GitHub repository and push the local project:** Confirm the local `origin` remote points to the intended repository and the latest commit is visible on GitHub.

## Web page loading explanation

When I type a website address into the browser, DNS helps it find the server that hosts the site. The browser requests the page, and the server sends back files such as HTML, CSS, JavaScript, and images. The browser reads these files, requests any additional resources it needs, and renders the webpage on the screen.
## Setup screenshots

### VS Code with the project open

VS Code project screenshot
<img width="1917" height="1078" alt="image" src="https://github.com/user-attachments/assets/e67dcf83-60ce-44d1-97c5-cc5bed43d763" />

### Node.js version

![Node.js version screenshot](screenshots/node-version.png)
<img width="1917" height="1078" alt="image" src="https://github.com/user-attachments/assets/e7d349a9-242a-48d8-ba28-c5f32ac399d9" />

### Page running with Live Server

![Live Server screenshot](screenshots/live-server-page.png)
<img width="1917" height="882" alt="image" src="https://github.com/user-attachments/assets/0d3f667b-69f8-465a-9780-903151c26cdf" />

## Tools installed and verified

| Tool | Version or verification | Evidence / notes |
| --- | --- | --- |
| Visual Studio Code | `<version>` | `<how verified>` |
| Node.js | `<version from node --version>` | `<verification notes>` |
| Live Server | `<installed in VS Code>` | `<how verified by launching the local page>` |
| Git | `<version from git --version>` | `<verification notes>` |
| Google Chrome | `<version>` | `<DevTools Network panel used>` |

## Project folder structure

```text
<project-folder>/
├── README.md
├── index.html
├── css/
│   └── style.css
├── js/
│   └── script.js
├── screenshots/
│   ├── vscode-project.png
│   ├── node-version.png
│   └── live-server-page.png
├── terminal-practice.md
└── network-inspection.md
```

Adjust this tree to match the folders and files actually created for the project.

## Terminal commands used

Record the terminal commands used to create the workspace and folders. Example:

```cmd
mkdir webdev-day01-setup-practice
cd webdev-day01-setup-practice
mkdir css js screenshots
```

## Terminal navigation practice

`<Add the completed terminal-navigation practice sheet here, or link to terminal-practice.md.>`

## Chrome DevTools network inspection

- **Website inspected:** `<website name and URL>`
- **Steps:** Opened the site in Chrome, opened DevTools with F12, selected **Network**, and reloaded the page.
- **Requests or resource types observed:** `<examples: document, stylesheet, JavaScript, image, font>`
- **Observation:** `<briefly describe what the Network panel showed>`
- **Full notes:** [Network inspection notes](network-inspection.md)

## Git commit evidence

Add at least three meaningful commits. Example progression:

1. `Create initial project structure`
2. `Add page content and styles`
3. `Document setup and inspection tasks`

See the repository history with:

```cmd
git log --oneline
```

## GitHub repository proof

- **Repository URL:** `<paste the complete GitHub URL>`
- **Pushed successfully:** `<yes/no>`
- **Latest commit visible on GitHub:** `<yes/no>`

## Submission checklist

- [ ] This README includes the web page loading paragraph.
- [ ] Tool installation screenshot is committed and linked above.
- [ ] At least three meaningful commits are visible in the Git history.
- [ ] GitHub repository link is filled in and opens the repository.
- [ ] Terminal navigation practice sheet is completed and included.
- [ ] Chrome DevTools network inspection notes are completed and included.
- [ ] Required tools are installed and verified; the first workspace exists.
- [ ] Project folders were created using terminal commands.
- [ ] Semester practice folder is a Git repository and has an initial commit.
- [ ] Local project was pushed to the GitHub repository.
