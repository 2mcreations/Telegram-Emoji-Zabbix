# Zabbix 7 LTS Telegram Media Type Template

This template provides a custom media type configuration for Zabbix 7 LTS to send notifications via Telegram.

## Features

- Utilizes Telegram's MarkdownV2 for message formatting
- Supports the following text styles:
  - \_\_Underscore__
  - \*\*\*Bold***
  - \~~Strikethrough~~
  - \`Code` (for inline code or copy text)
  - \```Code blocks``` (for multi-line code or text blocks)
  - \[link](https://github.com/2mcreations/Telegram-Emoji-Zabbix)
- Includes hyperlinks to directly access issues in Zabbix
- Uses emojis to visually represent alert severity

## Usage

1. Import the template into your Zabbix 7 LTS instance
2. Configure your Telegram bot token
3. Set up the media type in Zabbix
4. Set the global variable `{$ZABBIX.URL}` to your Zabbix instance URL
5. Customize message content as needed

## Severity Emojis

The template uses the following emojis based on alert severity:

- Info: 👀
- Warning: ⚠️
- Average: 😲
- High: 😨
- Disaster: 🔥
- OK (Resolved): ✅
