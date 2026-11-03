# MG5
## Devlog
1. I think its more advantageous to use NavMesh when the character movement input singular, for instance a single press on a keyboard or press of a single button on a controller. This is because once it is pressed the NavMesh will navigate to the destination of the Vector3, while character's movement with physics should be used when there are multiple inputs that each correspond to a certain direction. Baldurs Gate 3 only has one input for movement (mostly) which is defaulted to right click meaning it should use NavMesh, while games like Deadlock use WASD and several other inputs like CTRL or SPACE, so character's movement with physics makes more sense.
2. My for loop starts i = 0, so the index _birds[i] corresponds to element 0 which is the first bird, then i = 1 -> element 1, and lastly i = 2 -> element 2 in the inspector.

## Open-Source Assets
- [Quirky animal 3D models](https://assetstore.unity.com/packages/3d/characters/animals/quirky-series-free-animals-pack-178235)
- [Mountain fantasy environment models](https://www.fab.com/listings/60487a72-3f20-4bb2-aa78-247ed1582656)