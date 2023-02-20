# CarDelivery FiveM Script on server with QbCore Framework.

Start a mission for a car delivery, steal the car, drive it to the destination, profit.
*Note: This branch won't be updated unless requested so specifically for this branch.
All created issues default to the new branch.

## Features

- Payout based on vehicle condition (Engine, Body, Level)
- Very configurable
- Cooldown between each taken job
- Vehicles spawn either parked or driving around (Soon)
- Very basic rank system, nothing changes yet
- Possible cop car chase when the car is stolen
- Rank system with better cars spawning the more xp you get
- Chat commands for checking current level by /deliveryxp
- Admin rank editing options with /cardeliveryxp (option) (number)
- Level up and level down notifications

## Requirements

- [QbCore framework](https://github.com/qbcore-framework)

## Setup

1. Download or clone this repository inside your resources folder
2. Remove the "-main" part from folder name
3. Add a line to your server.cfg file -> **ensure hiype-cardelivery**
4. Add a line inside [qb] -> qb-core -> server -> player.lua

```lua
   PlayerData.metadata['cardeliveryxp'] = PlayerData.metadata['cardeliveryxp'] or 0
```

&nbsp;&nbsp;&nbsp;&nbsp;&nbsp;&nbsp;An example image can be found at the bottom of this section.

5. If your server is running, remember to either restart your server or do **/refresh** and also **/start hiype-cardelivery**

![Enter this line](https://i.imgur.com/hae5hLd.png)

## Instructions

To start the job, go to the location seen on the map below.

![Map](https://i.imgur.com/4xeQvGS.png)

Once there, go next to the NPC and press E key on your keyboard to start the job. An objective will automatically show up.

![Job start location](https://i.imgur.com/b4coTdR.png)

Follow the objective, use any lockpick to open the car and hotwire if necessary.
Drive to the destination. Beware, if the car is destroyed, job will **fail**!
Once you arrive at the destination, stop the car inside the objective blip on mini map. Job will finish and you will get paid depending on distance driven and condition of the car.

## Support

If you wish to support me in any way, or need help? Write me on Discord-> [Dicord] --> MoDas#6969 <--
