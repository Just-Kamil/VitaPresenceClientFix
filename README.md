# VitaPresence
Change your Discord rich presence to your currently playing PS Vita game!

Inspired by [SwitchPresence](https://github.com/Sun-Research-University/SwitchPresence-Rewritten)
<br>

![vitapresence](https://user-images.githubusercontent.com/12598379/78289782-fc45eb80-7522-11ea-8d5c-1deb49b1cb9c.png)

Works with PSVita & Adrenaline (including custom bubbles) games/apps

## Fix
- There was a "bug" where you would be stopped by the character limit for the Client ID this fork fixes that
- also updated .NET 

## Disclaimer
The client app (on Windows PC) must be running in the background, and the PC must be on the same network as your Vita.

It would be nice to have rich presence working with only the Vita itself, but this isn't currently possible due to Discord's RPC API restrictions.

## Setup
- Install the .skprx plugin within the `*KERNEL` section of your taiHEN config.txt
- Create an application at the [Discord Developer Portal](https://discordapp.com/developers/applications/), call your application `PS Vita` or whatever you would like and then enter your client ID and Vita's IP or MAC address into the VitaPresence client!
<br>

## Credits
- [Sun-Research-University](https://github.com/Sun-Research-University) for the idea & desktop app codebase

