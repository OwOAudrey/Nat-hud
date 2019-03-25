uwui-Custom Fork by Audrey
==========

A TF2 Hud forked from [Pigby/uwui](https://github.com/Pigby/uwui)
Then forked from [SohamG/uwui-v2] (https://github.com/SohamG/uwui-v2)

Credits to Pigby for making the hud
Credits to SohamG for adding some useful feature to the hud

Soham's Modifications
========
- Added Party chat and the button to open it (Missing from upstream)
- Fixed a bug where the label of the progress bar in the map loading screen would not be visible

My Modifications
========
- Made Scoreboard in 12v12 format for 16:10 apect ratio displays
- Removed sniper scope entirely

Non Hud side of things
========
The following is required in an autoexec config.
`alias remove_scope "sv_cheats 1; testhudanim scoperemoval"
remove_scope`

License
========
Gnu GPL v3
