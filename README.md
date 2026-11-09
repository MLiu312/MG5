# MG5
## Devlog
After you fix the for loop in BirdManager.cs, explain what is going on inside the loop. Specifically, what is the call to Vector3.Distance being used for? Based on this if statement, which birds in the _birds array will run away from the player?

1. NavMesh is more advantageous for point and click games. For example, League of Legends simply has the player character move towards the player's mouse click at times, so NavMesh would be better for that. Meanwhile, scripting player movement is better for games that require a greater degree of movement control, like Minecraft. Poor movement can lead to utter disaster, so scripted player movement is better.

2. The call to Vector3.Distance calculates the distance between the current player position and the position of whichever bird is currently selected by the for loop. If this distance is less than the minimum interaction distance, the birds will begin running away from the player, so any bird in the _birds array that is closer to the player than the set _interactDistance will run away.

## Open-Source Assets
- [Quirky animal 3D models](https://assetstore.unity.com/packages/3d/characters/animals/quirky-series-free-animals-pack-178235)
- [Mountain fantasy environment models](https://www.fab.com/listings/60487a72-3f20-4bb2-aa78-247ed1582656)
