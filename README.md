Server Restart Plugin

Overview

The Server Restart plugin adds a simple command, /server-restart, to Minecraft servers. When executed, it starts a 60-second countdown, notifying players that the server will restart in 60 seconds. After the countdown, the server automatically restarts, making it easier for administrators to handle scheduled or manual restarts without extra tools or complex setups.

Features

Simple Command: The plugin introduces the /server-restart command that initiates a server restart.
60-Second Countdown: Once the command is entered, a countdown is triggered, notifying players about the upcoming restart every 10 seconds.
Automatic Restart: After the countdown ends, the server restarts automatically.
Customizable Messages: You can modify the warning message to suit your server's needs.
No External Dependencies: The plugin is lightweight, easy to install, and doesn’t rely on any external tools.
Installation

Download the .jar file from the GitHub Releases section.
Place it in the plugins folder of your server.
Restart or reload the server to activate the plugin.
Usage

To initiate a server restart, type the following command in chat:

/server-restart
A 60-second countdown will begin, and players will see the message: "This server will restart in X seconds." After the countdown, the server restarts automatically.

Configuration

You can customize the countdown message, permission node, and countdown interval via the config.yml file. Default settings include a 60-second countdown and notifications every 10 seconds.

Permissions

server-restart.use: This permission allows users to run the /server-restart command.
This plugin is a simple yet effective way to manage server restarts with minimal downtime.
