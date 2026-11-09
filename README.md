# MG5
## Devlog
Put your Devlog here.
1. NavMesh as a movement system is much easier to implament, with the downside of it being more limited in abilities than a physics based movment system. If you want a movement system that involves fast movments, jumping, wallrunning, or anything complex, a physics based movment system is better. A game where a NavMesh movement system would be best is prehaps a Civilization game where you assign workers to different places. Here movment is not a key part of the game but is instead used as a detial. A physics based movement system would work well in an FPS where the player has to constantly moving in every direction.

2.Vector3Distance is being used to identify the distance between the player and each bird. If the distance is less than what is defined in inspecter then the bird is supposed to run away. As this method is inside Update() it is always running through the birds array (because of the for loop) it is constantly checking the distance between the player and all the birds.
## Open-Source Assets
- [Quirky animal 3D models](https://assetstore.unity.com/packages/3d/characters/animals/quirky-series-free-animals-pack-178235)
- [Mountain fantasy environment models](https://www.fab.com/listings/60487a72-3f20-4bb2-aa78-247ed1582656)