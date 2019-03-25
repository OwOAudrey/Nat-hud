uwui-Custom Fork by Audrey
==========

A TF2 Hud forked from [Pigby/uwui](https://github.com/Pigby/uwui)
Then forked from [SohamG/uwui-v2](https://github.com/SohamG/uwui-v2)

Credits to Pigby and SohamG Respectively for making and editing the hud.

install the fonts in /resource/fonts for it to work properly
==========

Soham's Modifications
========
- Added Party chat and the button to open it (Missing from upstream)
- Fixed a bug where the label of the progress bar in the map loading screen would not be visible

My Modifications
========
- Made Scoreboard in 12v12 format for 16:10 apect ratio displays
- Removed sniper scope entirely
![Screenshot](https://user-images.githubusercontent.com/34928493/54888124-4acc9e80-4e68-11e9-8835-fc6d8f648292.png "Screenshot")

Non Hud side of things
========
The following is required in an autoexec config.
>alias remove_scope "sv_cheats 1; testhudanim scoperemoval" ; remove_scope

License
========
Gnu GPL v3
