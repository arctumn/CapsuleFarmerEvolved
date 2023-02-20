![# Capsule Farmer Evolved](https://raw.githubusercontent.com/LeagueOfPoro/CapsuleFarmerEvolved/master/.github/banner.png)
<!-- Font for banner above by Riot Games BeaufortForLoL https://brand.riotgames.com/en-us/league-of-legends/typography/ -->
<p align="center">
<a href="https://github.com/LeagueOfPoro/CapsuleFarmerEvolved/blob/master/LICENSE"><img alt="License" src="https://img.shields.io/badge/license-CC%20BY--NC--SA%204.0-orange"></a>
<a href="https://www.python.org/downloads/release/python-3100/"><img alt="Python3" src="https://img.shields.io/badge/built%20for-Python%E2%89%A53.10-red.svg?style=flat"></a>
<a href="https://github.com/LeagueOfPoro/CapsuleFarmerEvolved/pulls"><img alt="PRsWelcome" src="https://img.shields.io/badge/PRs-welcome-brightgreen.svg?style=flat"></a>
<a href="https://github.com/LeagueOfPoro/CapsuleFarmerEvolved/stargazers"><img alt="GitHub Repo stars" src="https://img.shields.io/github/stars/LeagueOfPoro/CapsuleFarmerEvolved"></a>
<a href="https://github.com/LeagueOfPoro/CapsuleFarmerEvolved/issues?q=is%3Aissue+is%3Aclosed"><img alt="GitHub closed issues" src="https://img.shields.io/github/issues-closed/LeagueOfPoro/CapsuleFarmerEvolved"></a>
<a href="https://github.com/LeagueOfPoro/CapsuleFarmerEvolved"><img alt="GitHub last commit" src="https://img.shields.io/github/last-commit/LeagueOfPoro/CapsuleFarmerEvolved"></a>
</p>

Are you tired of watching professional League of Legends games? Do you watch only for the drops? This is a revolution in the farming of League of Legends Esports capsules!

This is a successor to the old [EsportsCapsuleFarmer](https://github.com/LeagueOfPoro/EsportsCapsuleFarmer) which relied on a web browser to watch videos. *Capsule Farmer Evolved* simulates traffic to lolesports.com servers and tricks it into thinking the account is watching a stream. This approach drastically lowers the hardware requirements.

[More information about Drops From Riot Games.](https://lolesports.com/article/drops-information-for-lol-esports-season-2023/blt15759d60486d16cc)


# README CONTENTS 
1. [Features](#features) 
2. [Community](#community)
3. [Notes](#notes)
4. [Configuration](https://github.com/LeagueOfPoro/CapsuleFarmerEvolved/wiki/Configuration)
5. [Installation](https://github.com/LeagueOfPoro/CapsuleFarmerEvolved/wiki)
    - [Windows](https://github.com/LeagueOfPoro/CapsuleFarmerEvolved/wiki/Advanced-Installation-for-Windows)
    - [Linux](https://github.com/LeagueOfPoro/CapsuleFarmerEvolved/wiki/Advanced-Installation-for-Linux)
    - [Docker](https://github.com/LeagueOfPoro/CapsuleFarmerEvolved/wiki/Advanced-Installation-for-Docker)
    - [MacOS](https://github.com/LeagueOfPoro/CapsuleFarmerEvolved/wiki/Advanced-Installation-for-MacOS)
    - [Android](https://github.com/LeagueOfPoro/CapsuleFarmerEvolved/wiki/Advanced-Installation-for-Android)
    - [Google TV](https://github.com/LeagueOfPoro/CapsuleFarmerEvolved/wiki/Advanced-Installation-for-Google-TV)
6. [Disclaimer⚠️](#disclaimer)

## Features
- Watch all live matches on lolesports.com
- Show how many drops each account received during the program run
- Very lightweight - no external browser needed
- Simple GUI
- 2FA (experimental) - programs prompts for the code on startup
- Docker supported
- ARM supported (Raspberry Pi)
- [Discord Webhook support](https://github.com/LeagueOfPoro/CapsuleFarmerEvolved/wiki/Configuration#configuration-options)

## Community
If you have any type of issue, need help, or just want to hangout. Come to [League of Poro's Discord server](https://discord.gg/ebm5MJNvHU).

## Support my work
[Subscribe to my channel on YouTube](https://www.youtube.com/channel/UCwgpdTScSd788qILhLnyyyw?sub_confirmation=1) or even

<a href='https://www.youtube.com/channel/UCwgpdTScSd788qILhLnyyyw/join' target='_blank'><img height='35' style='border:0px;height:46px;' src='https://share.leagueofporo.com/yt_member.png' border='0' alt='Become a channel member on YouTube' />

## Notes
- I recommend disabling 2FA on accounts using the bot. It will be way more stable, and it won't ask you for a code in the middle of a random night.
- Not every account receives every drop. That is normal, and it would happen even if you watched it on the web.
![image](https://user-images.githubusercontent.com/95635582/215994461-4f613b76-0e96-4b1a-b138-f1caa748df65.png)
- Regularly check if the "Heartbeat" happened within the last few minutes. If not, restart the program.

## Disclaimer 
CapsuleFarmerEvolved is not endorsed by Riot Games and does not reflect the views or opinions of Riot Games or anyone officially involved in producing or managing Riot Games properties. Riot Games and all associated properties are trademarks or registered trademarks of Riot Games, Inc

This project comes with no guarantee or warranty. You are responsible for whatever happens from using this project. No bans have been reported from using this project but it is not a guarantee. This is a personal project and is in no way affiliated with Riot Games.
<!-- Properly citing disclaimer from Riot Games Developer Portal https://developer.riotgames.com/docs/lol -->

<!-- !!!! Do not delete this pull request template! !!!! -->
<!-- Pull requests that do not follow this template are likely to be ignored and closed. -->

<!-- Add the issues this PR fixes here. If no issues are related to this PR, then this line can be removed. -->
<!-- Add further issues with a full "Fixes #[issue_no]" line to ensure GitHub closes each one when the PR is merged. -->

## How to enable the Poro-server
![image](https://user-images.githubusercontent.com/10279395/220099601-0bbd4e1a-7955-4fed-a876-e6b274b04086.png)
### .env version
1. create an .env file inside src
![image](https://user-images.githubusercontent.com/10279395/220187569-ac6dea37-6872-4186-9186-4d1cc2714572.png)
2. add the settings you want to adjust (by default you don't need any except WEBSERVER) to run it
![image](https://user-images.githubusercontent.com/10279395/220187788-8bcddc3f-e24d-4db5-b90f-d1bf6f604d55.png)
3. run the program you'll see this:
![image](https://user-images.githubusercontent.com/10279395/220190566-67af98af-1fd7-4ea9-a6c8-a1370113ad64.png)
### docker version
1. adjust or create dockerfile environments:
![image](https://user-images.githubusercontent.com/10279395/220190397-ed487ed9-680d-4a5d-9e63-05a435cf68c9.png)

2. build the image ```docker build -t capsulefarmerevolved .```
3. running the image ```docker run -it --restart unless-stopped -d -p 5000:8543 -v ./config/config.yaml:/config/config.yaml  capsulefarmerevolved```
![image](https://user-images.githubusercontent.com/10279395/220190640-1ef3da7c-d913-4b20-9283-d98714aa5875.png)
