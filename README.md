# Rotation Count

As start to move and rotate an object see  ["britzl/defold-orthographic"](https://github.com/britzl/defold-orthographic).

Use Mouse to rotate Game Object around it's axis. Use Left mouse button to start rotation count.

In `/main/player.script` there are:
- `process_rotation` - old function to count rotations, has bug when start to use WASD to move object and Mouse to rotate simultaneously.
- `process_rotation2` - new function.

---
