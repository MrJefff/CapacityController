This is a basic plugin that allows you to change the capacity of all storage containers and attachment containers on weapons

## Notes 
At this point in time you can only decrease the size of containers as the visible slots for each item is handled client side. However, there is a method i am slowly working on to make it so you can increase the number of visible slots for certain containers.

## Configuration
```json
{
  "Settings": {
    "Attachments": {
      "crossbow": 2,
      "lmg.m249": 3,
      "pistol.m92": 3,
      "pistol.python": 3,
      "pistol.revolver": 1,
      "pistol.semiauto": 3,
      "rifle.ak": 3,
      "rifle.bolt": 3,
      "rifle.lr300": 3,
      "rifle.semiauto": 3,
      "shotgun.double": 2,
      "shotgun.pump": 2,
      "shotgun.waterpipe": 2,
      "smg.2": 3,
      "smg.mp5": 3,
      "smg.thompson": 2
    },
    "Deployables": {
      "autoturret_deployed": 12,
      "box.wooden.large": 30,
      "campfire": 5,
      "fridge.deployed": 30,
      "furnace": 6,
      "furnace.large": 18,
      "locker.deployed": 38,
      "refinery_small_deployed": 6,
      "small_stash_deployed": 6,
      "stocking_small_deployed": 6,
      "stokcking_large_deployed": 6,
      "survivalfishtrap.deployed": 6,
      "vendingmachine.deployed": 30,
      "woodbox_deployed": 12
    }
  }
}
```
