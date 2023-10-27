# Prosole Slack Bot

## Introduction

Prosole Slack bot is designed to work seamlessly with the Alerts Utility in Prosole, allowing you to send logs and alerts to your Slack channels effortlessly. This bot provides a set of commands to help you get started with alerting in Slack.

## Bot Installation

To install the Slack bot for Prosole, you have two options:

### Option 1: Manual Installation

1. Go to the [Slack App Directory](https://slack.com/apps).
2. In the search bar, look for "Prosole."
3. Click on the app, which will take you to the Prosole Slack bot's dedicated page.
4. Hit the "Add to Workspace" button.
5. To enable the bot to function in your workspace, grant the app the necessary permissions and complete the authorization process.

Once the bot is authorized, you will receive a confirmation message, and it will be added to your workspace.

### Option 2: Quick Installation

Alternatively, you can quickly add the bot to your Slack workspace by clicking the "Add to Slack" button:

[![Add to Slack](https://platform.slack-edge.com/img/add_to_slack.png)](https://slack.com/oauth/v2/authorize?client_id=5993514621264.5983162910881&scope=app_mentions:read,channels:history,channels:join,channels:read,chat:write,chat:write.public,commands,groups:history,groups:read,mpim:read,users:read&user_scope=channels:history,channels:read,groups:history,groups:read)

This will take you directly to the authorization process, making it even more convenient to get started.

Once the bot is authorized, you will receive a confirmation message, and it will be added to your workspace.

Following installation, you can use the provided commands in any channel within your workspace to obtain a URL or token for sending logs to that specific channel. This simplifies the process of logging and alerting directly within Slack!

## Bot Commands

Our Slack bot supports the following commands:

- `/url`: Returns a webhook URL that you can use to send a POST request manually and log data to your channel.
- `/token`: Returns a token you can use with the Alerts Utility in Prosole to send logs to your channel.
- `/help`: Returns a list of available commands and brief descriptions.

Use these commands to configure and utilize the bot's features for logging and alerting in your Slack channel.

With the Slack bot for Prosole, you can enhance your team's collaboration and stay informed about important events in your Node.js applications. Enjoy simplified logging and alerting directly within Slack!

For more information and advanced usage of the Alerts Utility, refer to the Prosole documentation.
