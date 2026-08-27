# claude-check

A quick test to confirm that **Claude Code** is installed and working on your machine.

## What to do

1. Clone this repository:

   ```bash
   git clone https://github.com/jesusgamer1213/claude-check
   cd claude-check
   ```

2. Run the following command inside the repo folder:

   ```bash
   claude "summarize this repo"
   ```

3. Send the result (or a screenshot) to your team lead.

## What to expect

- **If you have Claude Code installed and configured**: the command opens a Claude Code session, which reads the files in the repo and gives you a summary in the terminal.
- **If you don't have it installed**: the terminal will respond with something like `command not found: claude`. That confirms the tool isn't available on your machine — install it by following [the official documentation](https://docs.claude.com/claude-code) or ask your IT team for help.

## Why this test

This repo contains no automatic logic or hidden scripts: the `claude "summarize this repo"` command is run by you, on purpose, from your own terminal. It's only meant to verify, simply and transparently, which code-agent tool (Claude Code, or another one) you have available in your work environment.
