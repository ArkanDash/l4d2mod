# My own L4D2 addons and configuration
Update: 27 March 2025

- Multislot (4+ Player)
  Extend 4 player slots to 8 player slots.
- Auto Bhop
  Automatic Bunny Hop for every survivor.
- Player Panel
  This allow to see survivor/special health in the player panel.
- Character Manager
  Fix duplicate survivor spawn.

# Launch Option
```
-high -nojoy -heapsize 750000 -num_edicts 4096 -insecure
```

- high
  Sets the game’s process priority to “high” in Windows. This can sometimes improve performance by giving the game more CPU time compared to lower-priority processes.

- nojoy
  Disables joystick support. If you don’t use a joystick or gamepad, turning off this feature can slightly reduce unnecessary input processing overhead.

- heapsize 750000
  Specifies the size of the memory heap for the game, in kilobytes. In this example, it allocates roughly 750,000 KB (about 750 MB) for the heap, which can influence how memory is managed, potentially improving performance or stability. This also fixed the audio cropped issue.

- num_edicts 4096
  Increases the maximum number of edicts (entities) the game engine can handle. This is useful if you’re running a mod or map that creates a lot of entities, ensuring that the game doesn’t run out of slots for them.

- insecure
  Launches the game in “insecure” mode, meaning it disables certain security features (like Valve Anti-Cheat, VAC). This is important to mod the game especially for addons.

# Credits
- [L4D1_2-Plugins](https://github.com/fbef0102/L4D1_2-Plugins)
- [l4dtoolz](https://github.com/accelerator74/l4dtoolz)
- [Player Panel](https://forums.alliedmods.net/showthread.php?t=341187)
- [Auto BunnyHop](https://forums.alliedmods.net/showthread.php?p=2481018)
- [Character Manager](https://forums.alliedmods.net/showthread.php?t=309601)