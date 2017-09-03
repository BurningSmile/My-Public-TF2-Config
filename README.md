# My-Public-TF2-Config
This is a public version of my custom and CFG folders.

This config is designed for My Linux install but should work on Windows
and OSX just fine.

This is designed to be ran on systems with a quadcore or better CPU.
Running this on a dual core WILL cause problems. Edit cfg/gfx.cfg with
Comanglia's dual core config.

Included are the following

#CFG

# Autoexec
- Execution of graphics and binds configs
- Quick aliases to change server levels as long as Rcon has already been entered
- Easy setup for server connect aliases
- Valve Demo record settings set to record to a demos directory
- Valve demo support set to record mp_tournament matches, This has the problem of also recording public games, I have a workaround for it in binds.cfg
- Various competitive settings and hud tweaks
- Various audio tweaks
- Removal of mouse acceleration

# Binds
- Unbind all keys
- Rebind defaults
- Null cancel movement script
- Loadout changer via f7 -f10 (Useful for quick forward/backward spawning)
- Binding of DEL/END/PGDWN to Scout Soldier Demo
- Fix for demo support recording public games. You press this at the start of official matches to make a mark called "Competitive game start" You will need to press this to avoid having the demo deleted after the game is over. This also starts a fresh demo recording at the start of the game so that the pregame is not recorded.
- Kill bind
- Hud and sound reload bind
- Viewmodel toggle bind
- Scoreboard with net_graph 1

# GFX
- Comanglia's graphics config with the following tweaks
    - Facial features turned on
    - High quality network settings turned on
    - Fps cap of 289. (I ran into problems on jump maps of hitting over 1000 when in offline mode, this solves it. Adjust accordantly for your refresh rate. The formula is 2X your monitors refresh rate plus 1. If you do not know your refresh rate then it is likely 60)
- This is the QUAD core or better config. This will cause problems on dual or single core CPU'S

# GFX_Pub
- Basic config with parts of Comanglia's config put in. This is to allow the game to run on high settings with certain things disabled.
- Sprays disabled
- Shadows disabled
- Ragdolls disabled
- Gibs disabled
- Weather disabled
- Quad core threading

# MatchmakingTF2Config
- Config that is designed to be exec'd while in a matchmaking game
- Designed for users with bad fps in MM
- Creator can be found here- https://www.reddit.com/r/tf2/comments/4k551m/tf2_matchmaking_config/

# Pub
- Turns off text chat and voice chat
- Turns on hud 3d player class model

# Rollout
- Script for practicing rollouts, dependency for Sollyrollout_fakelag and Sollyrollout_nofakelag
- Intended for offline jump maps or when on a server with sv_cheats 1 on for practicing jumps on comp maps
- Binds a key for noclip to repeat a jump multiple times without walking back
- Binds e to impulse101
- Configures offline servers properly for jumping

# Sollyrollout_fakelag and Sollyrollout_nofakelag
- Execs soldier and rollout scripts
- Binds mouse 1 to fire and impulse101
- Fakelag puts 25 fake lag while nofakelag adds no fakelag

# Viewmodelson
- Turns on viewmodels
- Puts 90 viewmodel fov on
- Rebinds 1/2/3 and mwheel up and down to defaults
- Changes crosshair to cross(7)

# Crosshair switcher folder
- Browsel crosshair switcher customized to my tastes, look through the files to see the changes

# Class configs
- Changes interp for hitscan to 0.033
- Changes interp for projectile to 0.0152
- Execs binds

#Custom


# m0rehud black
- http://www.teamfortress.tv/33738/ive-updated-some-huds
Changes include
- Small Hud damage indicators
- Removal of the killstreak counter
- Green damage numbers
- Minimal killfead

# No bullet hole dust
- Removes the dust that comes of walls
- See demo here https://www.youtube.com/watch?v=-GHvMCpRS68&feature=gp-n-y&google_comment_id=z131tl24kxnxetw4r04cdxbp1nqzuj5ojhg

# No Sound scapes
- Removes background noise in maps

# explosions_original
- Changes explosions to blue sparks
- http://www.teamfortress.tv/25647/no-explosion-smoke-script

# Installation
```
- Move your current cfg and custom directorys to the desktop
- Remove all TF2 launch options and place -default -autoconfig into launch options
- Start TF, once it starts close it
- Put my cfg and custom folders into your TF directory
- Edit launch options and use the launch options from the launch option file included
- Start TF and enjoy
```
