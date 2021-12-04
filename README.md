# kurat_antipowergaming
Anti-Powergaming Script for FiveM 🐌

Here I present my anti-powergaming script, publish it for you to use on your server! enjoy and hope you like it!

![LJ HUD](https://user-images.githubusercontent.com/91661118/143670558-cbd7b923-1fbe-4ac1-86f5-72c518937b85.png)

# 🎅🎄🎁 lj-hud used with QBCore Framework 🍪🦌🤶
Join my Discord laboratory for updates, support, and special early testing!
<br>
https://discord.gg/loljoshie (without-vanity url: https://discord.gg/HH6uTcBfew)

Improved off of the newest QBCore hud. Written in Vue.js
<br>
Runs at ~ 0.04 to 0.09 ms if you have more optimization suggestions feel free to reach out

# Dependencies
* [qbcore framework](https://github.com/qbcore-framework)
* [pma-voice](https://github.com/AvarianKnight/pma-voice)
* [qb-radio](https://github.com/qbcore-framework/qb-radio)
* [lj-fuel](https://github.com/qbcore-framework/qb-radio)

# Video Guide Installation
* [**[QBCore] lj-hud - Video Installation Guide**](https://youtu.be/_StJooDVGC8)

# Installation
* **IMPORTANT: If you're using [lj-fuel](https://github.com/loljoshie/lj-fuel) you NEED to change lj-fuel exports**

## qb-smallresources
* find **"qb-smallresources/client/seatbelt.lua"**
* find **"seatbelt:client:UseHarness" event** then add snippet below under **"harnessData = ItemData"**
```lua 
TriggerEvent('hud:client:UpdateHarness', harnessHp)
```

# My Compass
* Compass was made standalone to reduce (ms) on hud https://github.com/loljoshie/lj-compass

![lj-compass](https://user-images.githubusercontent.com/91661118/138012961-163ec6b3-7885-4df6-84a5-efd84aeac696.png)

# Key Features
* Toggle engine on and off
* Harness mode (harness radial shows when you have the harness item and checks for uses left which updates on the radial)
* Armed mode (weapons specifically whitelisted to not show armed mode)
* Switch between square and circle map with in-game /circle or square
* Cinematic mode (fully hides hud)
* Nitro when actived icon turns light red
* When dead heath radial turns red
* Dev mode radial when permission to do so (if you want dev mode working must follow instructions below)
* Headset icon appears when connected to radio channel
* Voice proximity and radio proximity highlighted
* Radial icons realign
* Seat belt equipped icon indicator
* Oxygen and Stamina radial indicator
* Engine health orange and red icon indicator
* Fuel low alert
* Fuel gauge color changes
* Parachute equipped radial indicator
* Cruise control radial dependent on vehicle speed
#

# Previews
### config / dynamic settings
![config](https://user-images.githubusercontent.com/91661118/143668588-9f99203e-d292-4aff-b6f7-5a742c0f7350.PNG)
### dead health
![dead](https://user-images.githubusercontent.com/91661118/143668617-3f41913f-506e-4c40-bc97-99c0e02eaec6.png)
### engine health
![engine](https://user-images.githubusercontent.com/91661118/143668642-22269059-8220-4b78-8f24-3c3661b7e82f.png)
### altitude
![altitude](https://user-images.githubusercontent.com/91661118/143668687-89ae10b6-9acc-4d68-845d-97db67d3d6de.png)
### parachute
![parachute](https://user-images.githubusercontent.com/91661118/143668699-a9d50ee4-1168-401b-bf92-8ba80a696e6e.png)
### armed
![armed](https://user-images.githubusercontent.com/91661118/143668646-baac9848-56e5-436b-922a-b35e50ed335f.png)
### cinematic
![cinematic](https://user-images.githubusercontent.com/91661118/143668651-74e90ac0-11ad-447a-b27c-1542dd10edfd.png)
### cruise
![cruise](https://user-images.githubusercontent.com/91661118/143668654-1b843009-c791-4482-807d-352b75707d42.png)
### harness
![harness](https://user-images.githubusercontent.com/91661118/143668664-bd03289a-286f-4165-9447-25b16b5b0c8e.png)
### cash
![cash](https://user-images.githubusercontent.com/91661118/143668667-a8e2e856-94be-45c4-9751-39e71315b303.png)
### bank
![bank](https://user-images.githubusercontent.com/91661118/143668668-fed140e6-9043-4daa-8aba-36feac3f9b78.png)
### nitro
![nitro](https://user-images.githubusercontent.com/91661118/143668672-8a164eb0-aca5-4e00-a99f-56c64e4d5069.png)
### stamina
![stamina](https://user-images.githubusercontent.com/91661118/143668678-3327c0bf-7e3b-4fe5-b6e5-da6e4054a47a.png)
### oxygen
![oxygen](https://user-images.githubusercontent.com/91661118/143668693-d623822b-fc78-499a-baa3-a86e29504044.png)
### radio
![radio](https://user-images.githubusercontent.com/91661118/143668707-eb4bb5e7-5900-4dd8-b500-5fc745a7c146.png)
### all radials
![all radials](https://user-images.githubusercontent.com/91661118/143668930-e9475c53-284c-4054-ad9c-88aa98f76768.png)

# Change Logs

### 1.1
* Revised radials added more spacing
* Separated icons from radials
* CSS changes on money and colors
* CSS changes on stress and parachute
* Added dynamic armor
* Fixed map not displaying while idle in vehicle
* Added border option found in config.lua
* Added more optimization

### 1.0
* Initial release

# Credit
* GhzGarage for original qb-hud [original version](https://github.com/qbcore-framework/qb-hud)

# Issues and Suggestions
Please use the GitHub issues system to report issues or make suggestions, when making suggestion, please keep [Suggestion] in the title to make it clear that it is a suggestion.

