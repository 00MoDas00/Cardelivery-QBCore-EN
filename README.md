# CarDelivery FiveM Script on QbCore Framework.
**This rewrite release might be less stable, if you want the old version, change the branch**

Start a mission for a car delivery, steal the car, drive it to the destination, profit.

## Features

- Payout based on vehicle condition (Engine, Body, Rank)
- Very configurable
- Cooldown between each taken job
- Possible cop car chase when the car is stolen
- Rank system with better cars spawning the more xp you get
- Chat commands for checking current level
- Admin rank editing options
- Level up and level down notifications
- Vehicles deleted more seemlessly
- **NEW** Now uses qb-target and polyzone

## Requirements

- [QbCore framework](https://github.com/qbcore-framework)
  - Polyzone - If you want a better programmable script, download it here. [Polyzone](https://drive.google.com/file/d/1HERgTQ0oxughilSp0qo7QnTZjuhE5cSt/view?usp=share_link)
  - QB-Target - If you want a better programmable script, download it here. [QB-Target](https://drive.google.com/file/d/1TWXZ_ZVgRTQUMYrfiOYdCR4fiSOj2qK4/view?usp=share_link)

## Setup

1. Download or clone this repository inside your resources folder
2. Remove the "-main" part from folder name
3. Add a line to your server.cfg file -> **ensure hiype-cardelivery**
4. Add a line inside [qb] -> qb-core -> server -> player.lua

```lua
   PlayerData.metadata['cardeliveryxp'] = PlayerData.metadata['cardeliveryxp'] or 0
```

5. If your server is running, remember to either restart your server or do **/refresh** and also **/start hiype-cardelivery**

![Enter this line](https://i.imgur.com/hae5hLd.png)

## Instructions

To start the job, go to the location seen on the map below.

![Map](https://i.imgur.com/4xeQvGS.png)

Once there, go next to the NPC and use third eye (left alt) to start the job. You will receive a message about the vehicle you need to steal.

![Job start location](https://i.imgur.com/b4coTdR.png)

Follow the objective, use any lockpick to open the car and hotwire if necessary.
Drive to the destination. Beware, if the car is destroyed, job will **fail**!
Once you arrive at the destination, stop the car inside the objective blip on mini map. Job will finish and you will get paid depending on distance driven and condition of the car.

## Config and translation info

[Head to the wiki page for detailed explanation on each variable](https://github.com/00MoDas00/Cardelivery-QBCore/wiki)

## Support

If you wish to support me in any way, or need help? Write me on Discord-> [Dicord] --> MoDas#6969 <--
