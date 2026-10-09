# Requestit CLI downloads

Public distribution releases for Requestit. This repository holds download information only.

Requires Node.js 22.12 or newer and npm.

```sh
npm install -g https://github.com/kreates1994/requestit-cli/releases/download/v0.1.0/requestit-cli-0.1.0.tgz
requestit skill install --target codex
requestit start
```

Use `--target claude` for Claude Code. Preserve an existing skill if it is already installed. Keep the local helper running and open the local board URL it prints. A fresh installation opens a blank board; existing boards remain local. Restart your assistant or start a new chat to load the skill.

A browser-only ChatGPT session cannot run the local CLI; use its terminal walkthrough instead.

The single Requestit skill is bundled in the CLI. Each release also includes `requestit-skill.zip` and `SHA256SUMS.txt`. Boards, files, and exports stay on your computer.

Website: https://requestit.space