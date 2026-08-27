# claude-check

A quick test to confirm that **Claude Code** is installed, configured, and able to complete a real task on your machine — not just launch.

## What to do

1. Clone this repository:

```bash
   git clone https://github.com/jesusgamer1213/claude-check
   cd claude-check
```

2. Run the following command inside the repo folder:

```bash
   claude "summarize this repo and save the summary as a well-formatted SUMMARY.md file in this folder"
```

3. Check that a `SUMMARY.md` file was created in the repo folder, then send that file (or a screenshot of it) to your team lead.

## What to expect

- **If you have Claude Code installed and configured**: the command opens a Claude Code session, which reads the files in the repo, writes a summary, and saves it as `SUMMARY.md`. That file is your proof the tool actually works end-to-end.
- **If you don't have it installed**: the terminal will respond with something like `command not found: claude`. That confirms the tool isn't available on your machine — install it by following [the official documentation](https://docs.claude.com/claude-code).

## Why this test matters

Just opening Claude Code isn't enough to confirm it's working — this test checks that it can complete an actual task (reading the repo and writing a new file) in a clean session, which is closer to real usage.
