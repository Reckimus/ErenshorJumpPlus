# ErenshorJumpPlus
Tweaked player jump height and SimPlayer immersion

Jump Plus – a tiny QoL mod for Erenshor

Feature	What it does	Default value
Higher player jump	Multiplies the impulse applied when you hit Jump, so ledges and low fences are easier to clear.	 × 1.6 (≈ 60 % higher)
Livelier SimPlayers	Every NPC “SimPlayer” has a 15 % chance, every 2 s, to do a small running hop (1 m high, 0.6 s airtime). Hops are staggered per‑NPC, so they never look synchronised.	15 % / 1 m / 0.6 s

Install BepInEx 5 (x64) (If you havent already)

Download the latest “BepInEx_x64_5.xx.xx.zip” from the official GitHub releases.

Extract the contents into your Erenshor game folder (you should end up with Erenshor/BepInEx/, winhttp.dll, etc.).



Put Erenshor_JumpPlus.dll in Erenshor/BepInEx/plugins/.

Start the game once; BepInEx will create a config file and print a console window.

That’s it—player jumps are instantly taller and NPCs will start hopping after ~10 s of running.

Now your game world will feel slightly more lively like its filled with actual players. (This mod may or may not be updated in future and or renamed when more features are added to it)

values to change in the config file for your preference
Setting	Section	Effect
JumpMultiplier	[General]	Change from 1.6 to any value (1.0 = vanilla).
HopChance	[SimPlayers]	0 – 1.0. Example 0.25 = 25 % chance every 2 s.
HopHeight	[SimPlayers]	Pure metres. 0.4–1.0 looks natural.
HopTime	[SimPlayers]	Total time (up + down) in seconds.
