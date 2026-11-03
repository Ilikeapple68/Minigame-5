# MG5
## Devlog

1. It is more advantageous to use Navmesh when a character movement is simple. For example in Arknights, the enemy only have to move towards the blue door, which cause player to lose health, in that case it will be easier to use Navmesh because scripting it will require too much calculations. It would be better to script the movement when movement is a important part of the game. For example, like Valorant, CSGO, or Overwatch. All these first person games requires precise movement, and that is when scripting character's movement comes important.

2. After I fix the loop, I identified that the loop goes through each element in the birds array. For each of them, the code uses a if statement to check if the distance of the current position is less than the interact distance using Vector3.Distance() method. If the code works, all birds should run away from the player.

## Open-Source Assets
- [Quirky animal 3D models](https://assetstore.unity.com/packages/3d/characters/animals/quirky-series-free-animals-pack-178235)
- [Mountain fantasy environment models](https://www.fab.com/listings/60487a72-3f20-4bb2-aa78-247ed1582656)
