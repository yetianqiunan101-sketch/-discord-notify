# -discord-notify
​A lightweight, zero-dependency Python CLI and library for sending Discord Webhook notifications

Simple Discord Webhook notifier for shell scripts, cron jobs, and Python apps with zero dependencies


 # Discord Notify CLI & Python Wrapper

A lightweight, zero-dependency Python script and CLI tool to send log outputs or system alerts directly to Discord via Webhooks.

## Features

- **Zero External Dependencies**: Uses only standard Python modules (`urllib`).
- **CLI & Python Module**: Use it directly in your terminal/bash scripts or import it as a library.
- **Pipe Support**: Easily piping long execution logs directly into Discord.

## Quick Start (CLI)

1. Set your Webhook URL:
   ```bash
   export DISCORD_WEBHOOK_URL="[https://discord.com/api/webhooks/](https://discord.com/api/webhooks/)..."
