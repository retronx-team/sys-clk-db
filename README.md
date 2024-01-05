# sys-clk-db

Thanks to everyone who contributed to this collection!

**Notes:**  
This format is temporary as we set up a convenient directory structure to be
able to directly import community curated profiles!

## Examples

```ini
; Example ; 1: BOTW
; Overclock CPU when docked
; Overclock MEM to docked clocks when handheld
[01007EF00011E000]
docked_cpu=1224
handheld_mem=1600
```

```ini
; Example ; 2: Picross
; Underclock to save battery
[0100BA0003EEA000]
handheld_cpu=816
handheld_gpu=153.6
handheld_mem=800
```

## Community presets

Those presets comes from our community in the RetroNX Discord
in the channel `#oc-perf-submissions`

```ini
; 'n Verlore Verstand
; Overclock to improve preformance
[010098800C4B000]
handheld_gpu=460
handheld-mem=1600
handheld_charging_gpu=768
handheld_charging_official_gpu=921
docked_gpu=921
```

```ini
; 13 Sentinels: Aegis Rim
; Overclock GPU in handheld to get locked 60 FPS 99.9% of time
[01003FC01670C000]
handheld_gpu=460
```

```ini
; AI: The Somnium Files
; Overclock to improve framerate
[010089B00D09C000]
handheld_cpu=1224
handheld_gpu=460
handheld_mem=1600
handheld_charging_cpu=1785
handheld_charging_gpu=768
handheld_charging_official_gpu=921
docked_cpu=1785
docked_gpu=921
```

```ini
; A Short Hike
; Underclock to reduce power draw and heat
[01004890117B2000]
handheld_gpu=153
docked_gpu=230
```

```ini
; AI: The Somnium Files
; Overclock to improve framerate
[010089B00D09C000]
handheld_cpu=1224
handheld_gpu=460
handheld_mem=1600
handheld_charging_cpu=1785
handheld_charging_gpu=768
handheld_charging_official_gpu=921
docked_cpu=1785
docked_gpu=921
```

```ini
; AI the Somnium Files: Nirvana Initiative
; Overclock to improve preformance
[0100713016CCC000]
handheld_cpu=1224
handheld_gpu=460
handheld_mem=1600
handheld_charging_cpu=1683
handheld_charging_gpu=768
handheld_charging_official_gpu=921
docked_cpu=1683
docked_gpu=921
```

```ini
; Animal Crossing: New Horizons
; Underclock to save battery, boost mode will be
; disabled so loading times will increase, especially when starting the game
[01006F8002326000]
handheld_cpu=612
handheld_gpu=307
```

```ini
; ARMS
; Underclock to save battery
[01009B500007C000]
handheld_cpu=918
handheld_gpu=230    
handheld_mem=1065
```

```ini
; Assassin's Creed III: Remastered
; Overclock to get the best performance while docked. 
[01007F600B134000]
docked_cpu=1683
docked_gpu=921
docked_mem=1600
```

```ini
; Astral Chain
; Overclock to improve performance
[01007300020FA000]
handheld_cpu=1224
handheld_mem=1600
handheld_charging_gpu=614
docked_cpu=1428
docked_gpu=921
```

```ini
; Atari Flashback Classics
; Massive underclock with no hit to performance
[0100CF3007578000]
handheld_cpu=612
handheld_gpu=76
handheld_mem=665
```

```ini
; Axiom Verge
; Underclock to save battery
[0100052004384000]
handheld_cpu=612
handheld_gpu=153
handheld_mem=665
```

```ini
; Azure Striker Gunvolt: Striker Pack
; Underclock to reduce heat/save battery
[0100192003FA4000]
handheld_cpu=612
handheld_gpu=153
handheld_mem=665
handheld_charging_mem=800
docked_cpu=612
docked_gpu=153
docked_mem=1065
```

```ini
; Baba is You
; Underclock for a massive battery saving
[01002CD00A51C000]
handheld_cpu=612
handheld_gpu=76
handheld_mem=665
```

```ini
; Badland: Game of the Year Edition
; Underclock to save battery/ reduce heat
[0100D730151C8000]
handheld_cpu=612
handheld_gpu=153
handheld_mem=665
docked_cpu=612
docked_gpu=307
docked_mem=800
```

```ini
; Bayonetta 2
; Overclock to improve framerates
[01007960049A0000]
handheld_gpu=460
handheld_mem=1600
handheld_charging_cpu=1122
handheld_charging_gpu=768
handheld_charging_offical_gpu=921
docked_cpu=1122
docked_gpu=921
```

```ini
; Bendy and the Ink Machine
; Underclock to save battery
; Overclock to improve preformance
[0100D4C00C6C0000]
handheld_cpu=816
handheld_mem=1600
handheld_charging_gpu=460
docked_gpu=921
```

```ini
; Blaster Master Zero 2
; Underclock to save battery
[01005AA00D676000]
handheld_cpu=612
handheld_gpu=230
handheld_mem=665
```

```ini
; Blazing Chrome
; Underclock to save battery with bare minimum settings
[0100C2700C252000]
handheld_cpu=612
handheld_gpu=76 
```

```ini
; Bloodstained: Curse of the Moon
; Underclocked to save battery
[01004B800AF5A000]
handheld_cpu=612
handheld_gpu=153
handheld_mem=665
```

```ini
; Bloodstained: Ritual of the Night
; Provides the game to run generally smoother in handheld mode
[0100BF500207C000]
docked_cpu=1683
docked_gpu=844
handheld_charging_cpu=1224
handheld_cpu=1224
handheld_gpu=460
handheld_mem=1600
```

```ini
; Bloodstained: Ritual of the Night CHT
; Provides the game to run generally smoother in handheld mode
[010025A00DF2A000]
docked_cpu=1683
docked_gpu=921
handheld_charging_cpu=1224
handheld_charging_gpu=768
handheld_charging_mem=1600
handheld_cpu=1224
handheld_gpu=460
handheld_mem=1600
```

```ini
; Blossom Tales: The Sleeping King
; Underclock to save battery
[0100C1000706C000]
handheld_cpu=612
handheld_gpu=153
handheld_mem=665
```

```ini
; Broforce
; Underclock to save battery, level selection screen and main menu has slight slowdowns. 
[010060A00B53C000]
handheld_cpu=714
handheld_gpu=76
handheld_mem=1065
```

```ini
; Bug Fables The Everlasting Sapling
; Underclock to save battery
[010051A00E99E000]
handheld_cpu=612
handheld_gpu=230
```

```ini
; Cadence of Hyrule: Crypt of the NecroDancer featuring The Legend of Zelda
; Underclock to save battery
[01000B900D8B0000]
handheld_cpu=918
handheld_gpu=153
handheld_mem=1065
```

```ini
; Captain Toad: Treasure Tracker
; Underclock to lower heat/ save battery
; Overclock to improve resolution 
[01009BF0072D4000]
handheld_cpu=612
handheld_mem=1600
handheld_charging_gpu=537
docked_cpu=612
docked_gpu=921
; Alternate settings
; Underclock to save battery
;handheld_cpu=612
;handheld_gpu=307
;handheld_mem=665
```

```ini
; Captain Toad: Treasure Tracker
; Underclock to save battery
[01009BF0072D4000]
handheld_cpu=612
handheld_gpu=307
handheld_mem=665
```

```ini
; CARRION
; Underclock to save battery - stable 60fps
[0100B1600E9AE000]
handheld_cpu=612
handheld_gpu=153
```

```ini
; Castle Crashers Unlimited
; Underclock to save battery @60fps
[010001300D14A000]
handheld_cpu=612
handheld_gpu=230
handheld_mem=665
```

```ini
; Catherine: Full Body (US)
; Underclock to save battery in handheld
; Underclock to reduce power consumption Docked/Official charger
; Small resolution penalty in handheld (you can go lower if you don't mind sawtooth)
; No resolution penalty docked
[0100BF00112C0000]
docked_cpu=1020
docked_gpu=460
docked_mem=1331
handheld_charging_cpu=918
handheld_charging_gpu=307
handheld_charging_mem=1065
handheld_charging_usb_cpu=918
handheld_charging_usb_gpu=307
handheld_charging_usb_mem=1065
handheld_charging_official_cpu=1020
handheld_charging_official_gpu=460
handheld_charging_official_mem=1331
handheld_cpu=918
handheld_gpu=307
handheld_mem=1065
```

```ini
; Cave Story+
; Underclock to save battery
[0100B7D0022EE000]
handheld_cpu=612
handheld_gpu=153
handheld_mem=665
```

```ini
; Celeste
; Increases battery life by underclocking, only lags in overworld menu, gameplay is unaffected, load times *may* be slightly slower.
; Not tested with Chapter 9 "Farewell"
[01002B30028F6000]
handheld_cpu=665
handheld_gpu=153
handheld_mem=800
```

```ini
; Child of Light
; Overclock to improve preformance
; Underclock to save battery
[01007D000AD8A000]
handheld_cpu=714
handheld_gpu=384
handheld_mem=1600
handheld_charging_cpu=1224
handheld_charging_gpu=537
docked_cpu=1224
docked_gpu=921
```

```ini
; Crimsonland
; Underclock to save battery
[01005640080B0000]
handheld_cpu=612
handheld_gpu=76
```

```ini
; DANDY DUNGEON - LEGEND OF BRAVE YAMADA -
; Underclock to save battery
[0100DFB00D808000]
handheld_cpu=816
handheld_gpu=230
handheld_mem=800
```

```ini
; Darksiders II Deathinitive Edition
; Improve resolutions and performance for handheld mode
[010071800BA98000]
handheld_gpu=460
```

```ini
; Destroy All Humans! (US)
; Underclock CPU to reduce battery/energy consumption in handheld/dock/charger (you can go as low as 612MHz won't drop a frame except in saucer, it will drop between 2 to 4 frames when it gets full of NPCs, but I mean a ridiculously full, that's why 714MHz)
; Overclock GPU to increase resolution (Wont be noticeable past 691MHz)
; Overclock MEM to reduce object/texture pop-in
[01009E701356A000]
docked_cpu=816
docked_gpu=691
docked_mem=1600
handheld_charging_cpu=714
handheld_charging_gpu=691
handheld_charging_mem=1600
handheld_charging_usb_cpu=714
handheld_charging_usb_gpu=691
handheld_charging_usb_mem=1600
handheld_charging_official_cpu=816
handheld_charging_official_gpu=691
handheld_charging_official_mem=1600
handheld_cpu=714
handheld_gpu=460
handheld_mem=1600
```

```ini
; Devil May Cry
; Underclock to save battery while maintaining 60fps
[0100E8000D5B8000]
handheld_cpu=816
handheld_gpu=230
handheld_mem=800
```

```ini
; Donkey Kong Country Tropical Freeze
; Underclock GPU when docked to decrease heat
[0100C1F0051B6000]
docked_gpu=614
```

```ini
; DOOM
; Better Framerate (Adjust dock gpu between 768-921 based on your comfort level)
; via gbatemp thread
[0100416004C00000]
handheld_gpu=460
handheld_mem=1600
handheld_charging_official_gpu=768
docked_cpu=1224
docked_gpu=844
```

```ini
; Doom 1993
; Underclock to save battery with bare minimum settings
[010018900DD00000]
handheld_cpu=612
handheld_gpu=76
```

```ini
; Doom 64
; Underclock to save battery with bare minimum settings
[01005D700E742000]
handheld_cpu=612
handheld_gpu=76
```

```ini
; Doom II Classic
; Underclock to save battery with bare minimum settings
[0100D4F00DD02000]
handheld_cpu=612
handheld_gpu=76
```

```ini
; Dragon Ball Xenoverse 2 (US)
; Underclock CPU to reduce battery/energy consumption in handheld/dock/charging (you can go as los as 714MHz, I didn't experience any frame drops but to be sure I left it at 816MHz)
; Underclocked GPU on docked/charging to reduce energy consumption (small resolution penalty docked that's why 537MHz, no penalty charging)
; Overclocked MEM to reduce object/texture pop-in
[010078D000F88000]
docked_cpu=816
docked_gpu=537
docked_mem=1600
handheld_charging_cpu=816
handheld_charging_gpu=460
handheld_charging_mem=1600
handheld_charging_usb_cpu=816
handheld_charging_usb_gpu=460
handheld_charging_usb_mem=1600
handheld_charging_official_cpu=816
handheld_charging_official_gpu=460
handheld_charging_official_mem=1600
handheld_cpu=816
handheld_gpu=460
handheld_mem=1600
```

```ini
; Dragon Dogma Dark Arisen
; Better framerate
[010032C00AC58800]
docked_cpu=1224
docked_gpu=844
handheld_charging_cpu=1122
handheld_charging_gpu=768
handheld_charging_official_cpu=1122
handheld_charging_official_gpu=768
handheld_cpu=1020
handheld_gpu=460
handheld_mem=1600
```

```ini
; Dragon Dogma Dark Arisen (JPN)
; Better framerate
docked_cpu=1224
docked_gpu=844
handheld_charging_cpu=1122
handheld_charging_gpu=768
handheld_charging_official_cpu=1122
handheld_charging_official_gpu=768
handheld_cpu=1020
handheld_gpu=460
handheld_mem=1600
```

```ini
; Dragon Quest Builders 2
; Fixed docked & handheld FPS stutter
[010042000A986000]
docked_cpu=1224
docked_gpu=768
handheld_gpu=460
handheld_charging_gpu=537
; Alternate settings
; Save a bit of battery, retaining performance
;handheld_cpu=816
;handheld_gpu=307
;handheld_mem=1065
```

```ini
; Dragon Quest XI S: Echoes of an Elusive Age - Definitive Edition
; Improves stutter when moving the camera at high speed and improves framerate of far NPC animation (15 -> 30)
[01006C300E9F0000]
docked_cpu=1581
```

```ini
; Duke Nukem 3D 20th Anniversary World Tour
; Underclock to save battery
[01007EF00CB88000]
handheld_cpu=612
handheld_gpu=230
```

```ini
; Dusk
; Underclock to save battery
[01007740160D4000]
handheld_cpu=612
handheld_gpu=153
```

```ini
; Fast RMX
; Improve resolutions for handheld mode
[01009510001CA000]
handheld_gpu=460
handheld_charging_gpu=768
handheld_charging_mem=1600
```

```ini
; FIFA 19
; Underclock to reduce power draw/heat
; Underclock to save battery
; Overclock to slightly improve performance
[0100FFA0093E8000]
handheld_cpu=918
handheld_gpu=307
handheld_mem=1065
handheld_charging_mem=1600
docked_cpu=918
docked_gpu=537
```

```ini
; Fire Emblem Three Houses
; Provides a smoother framerate whilst undocked and better framerate docked
[010055D009F78000]
docked_cpu=1224
docked_gpu=844
handheld_charging_cpu=1224
handheld_charging_gpu=768
handheld_cpu=1020
handheld_gpu=460
handheld_mem=1600
```

```ini
; Fire Emblem Warriors
; Provides a smoother framerate whilst undocked
[0100F15003E64000]
handheld_cpu=1224
handheld_gpu=460
handheld_mem=1600
```

```ini
; Fire Emblem Warriors: Three Hopes
; Overclock to reach higher framerates
[010071F0143EA000]
handheld_cpu=1224
handheld_gpu=460
handheld_mem=1600
handheld_charging_cpu=1785
handheld_charging_gpu=768
handheld_charging_official_gpu=921
docked_cpu=1785
docked_gpu=921
```

```ini
; Five Nights at Freddy's 1
; Underclock to save battery
; Underclock to lower power draw
; The game will drop frames when switching cameras rapidly, but it happens even on stock
[0100B6200D8D2000]
handheld_cpu=612
handheld_gpu=76
handheld_mem=665
docked_cpu=612
docked_gpu=76
docked_mem=800
```

```ini
; Five Nights at Freddy's 2
; Underclock to save battery
; Underclock to reduce heat
; The game may drop frames on title screen and on switching cameras quickly
[01004EB00E43A000]
handheld_cpu=612
handheld_gpu=76
handheld_mem=665
docked_cpu=612
docked_gpu=76
docked_mem=800
```

```ini
; Five Nights at Freddy's 3
; Underclock to save battery
; Underclock to reduce heat
; The game drops frames on camera switching, and there is a slight delay when switching cameras
[010056100E43C000]
handheld_cpu=612
handheld_gpu=76
handheld_mem=665
docked_cpu=612
docked_gpu=76
docked_mem=800
```

```ini
; Five Nights at Freddy's 4
; Underclock to save battery
; Underclock to reduce heat
; When switching areas the game will drop to 15 frames, then recover
[010083800E43E000]
handheld_cpu=612
handheld_gpu=76
handheld_mem=665
docked_cpu=612
docked_gpu=76
docked_mem=800
```

```ini
; Five Nights at Freddy's Sister Location
; Underclock to save battery
; Underclock to reduce heat
; When entering a new area, suttering occurs briefly
[01003B200E4400000]
handheld_cpu=612
handeheld_gpu=153
handheld_mem=800
docked_cpu=612
docked_gpu=230
docked_mem=1065
```

```ini
; Florence
; Underclock to reduce heat/ save battery 
; Note: Suttering will occur, so RAM OC is enabled to mitigate this
[010040700E8FC000]
handheld_cpu=612
handheld_gpu=153
handheld_mem=1600
docked_cpu=714
docked_gpu=307
```

```ini
; Fortnite
; This enables the game to run generally smoother in handheld mode. 
[010025400AECE000]
handheld_cpu=1224
handheld_gpu=460
handheld_mem=1600
```

```ini
; Furi
; Sustain the framerate, more noticeable after the 3rd fight
[01009D3008D20000]
handheld_cpu=1224
handheld_mem=1600
```

```ini
; Grandia II
; Massively improved handheld framerate
[0100E0600BBC8002]
handheld_gpu=460
```

```ini
; Gear Club Unlimited
; Eliminates some stutter during races in handheld mode.
[010065E003FD8000]
handheld_gpu=460
handheld_mem=1600
```

```ini
; Gear Club Unlimited 2
; Mitigates freezes that occur while racing in handheld mode..
[010072900AFF0000]
handheld_gpu=460
handheld_mem=1600
```

```ini
; Grand Theft Auto: San Andreas - The Definitive Edition (US)
; Overclock for smoother gameplay
; It will decrease your handheld playtime by 30 to 45 min.
[010065A014024000]
docked_cpu=1581
docked_gpu=768
docked_mem=1600
handheld_charging_cpu=1224
handheld_charging_gpu=460
handheld_charging_mem=1600
handheld_charging_usb_cpu=1224
handheld_charging_usb_gpu=460
handheld_charging_usb_mem=1600
handheld_charging_official_cpu=1581
handheld_charging_official_gpu=768
handheld_charging_official_mem=1600
handheld_cpu=1224
handheld_gpu=460
handheld_mem=1600
```

```ini
; Graveyard Keeper
; Underclock to save battery (slightly increases loading times)
[0100B6800B5C8000]
handheld_cpu=816
handheld_gpu=230
handheld_mem=800
```

```ini
; Grip
; This enables the game to actually run at 30FPS
[0100459009A2A000]
handheld_cpu=1224
handheld_gpu=460
handheld_mem=1600
```

```ini
; A Hat in Time (US)
; Boosts clock for noticeably faster loading screens and better framerate in handheld
; The unfinished Nyakuza included with Seal the Deal's romfs now runs at 30fps
[010056E00853A000]
docked_cpu=1785
docked_gpu=844
handheld_charging_cpu=1785
handheld_charging_gpu=844
handheld_mem=1600
```

```ini
; Hatsune Miku: Project DIVA Mega Mix
; Overclock for better load times.
[01001CC00FA1A000]
docked_cpu=1785
handheld_cpu=1785
handheld_mem=1600
```

```ini
; Hyrule Warriors: Age of Calamity
; Overclock to improve frame rate and resolution
; Docked mode does not maintain stable framerates even with 1785
[01002B00111A2000]
handheld_cpu=1326
handheld_gpu=460
handheld_mem=1600
handheld_charging_cpu=1785
handheld_charging_gpu=614
docked_cpu=1785
docked_gpu=921
```

```ini
; ICEY
; Overclock to improve framerate and frame pacing 
[0100BE9007E7E000]
handheld_cpu=1224
handheld_mem=1600
handheld_charging_cpu=1326
handheld_charging_gpu=384
docked_cpu=1326
docked_gpu=844
```

```ini
; Katana Zero
; Underclock to save battery
[010029600D56A000]
handheld_cpu=612
handheld_gpu=153
```

```ini
; Kirby Star Allies
; Underclock to save battery
[01007E3006DDA000]
handheld_cpu=918
handheld_mem=1065
```

```ini
; LA Noire
; Smooths up things such as general camera movement while in vehicles
[0100830004FB6000]
handheld_mem=1600
```

```ini
; Layers of Fear: Legacy
; More stable 60 FPS across whole game
[0100BF5006A7C000]
handheld_cpu=1224
handheld_gpu=460
handheld_mem=1600
```

```ini
; Legend of Zelda: Link's Awakening
; Improved framerate in handheld, resolves most framerate issues in handheld_charging
[01006BB00C6F0000]
handheld_charging_gpu=768
handheld_gpu=460
handheld_mem=1600
```

```ini
; LEGO City Undercover
; Smoother framerate in handheld.
[01003A30012C0000]
handheld_gpu=460
handheld_mem=1600
```

```ini
; Lines Infinite
; Save them batteries
[0100A9000F17E000]
handheld_cpu=612
handheld_gpu=76
handheld_mem=665
```

```ini
; Luigi's Mansion 3 [700p]
; NOTE: This will lower the res to 700p, but is
; not noticeable in handheld due to TAA
; Underclock to save battery
; Adjust if needed, still @30fps
[0100DCA0064A6000]
handheld_cpu=714
handheld_gpu=307
handheld_mem=1600
```

```ini
; LUMINES REMASTERED
; Underclock to save battery
[0100A4200A284000]
handheld_cpu=918
handheld_gpu=230
```

```ini
; Mario + Rabbids Kingdom Battle
; Underclock to improve battery
; Overclock to improve preformance
; Note: Charger OC is for cutscenes, and can be disabled for base game.
; Note: This kneecaps the load times in this game
[010067300059A000]
handheld_cpu=612
handheld_mem=1600
handheld_charging_cpu=1226
handheld_charging_gpu=537
docked_cpu=1226
docked_gpu=921
```

```ini
; Mario Kart 8 Deluxe
; Underclock to save battery
[0100152000022000]
handheld_cpu=918
handheld_gpu=230
handheld_mem=1065
; Alternate settings (Booster pass course wave 1)
; Only use this if you wish to play the DLC courses without slowdowns, as the profile above is for DLC-less
;handheld_cpu=918
;handheld_gpu=307
;handheld_mem=1065
```

```ini
; Marsupilami - Hoobadventure
; Overclock CPU and GPU for 60 FPS gameplay in handheld mode. Stages 1-1, 2-4, 2-5 require more power
[010074F014628000]
handheld_cpu=1581
handheld_gpu=460
handheld_mem=1600
handheld_charging_cpu=1581
handheld_charging_gpu=614
handheld_charging_mem=1600
```

```ini
; Marvel Ultimate Alliance 3
; Better framerate in handheld mode
[010060700AC50000]
handheld_charging_cpu=1224
handheld_charging_gpu=768
handheld_charging_mem=1600
handheld_cpu=1020
handheld_gpu=460
handheld_mem=1600
```

```ini
; Max: The Curse of Brotherhood
; Underclock to save battery/reduce head
; Overclock to improve preformance
[01001C9007614000]
handheld_cpu=714
handheld_gpu=384
handheld_mem=1600
handheld_charging_cpu=816
handheld_charging_gpu=537
docked_cpu=816
docked_gpu=537
```

```ini
; Mega Man 11
; Underclock to save battery
[0100B0C0086B0000]
handheld_cpu=612
handheld_gpu=230
handheld_mem=665
```

```ini
; Mega Man Legacy Collection 2
; Underclock to save on battery
[0100842008EC4000]
handheld_cpu=714
handheld_gpu=153
handheld_mem=665
```

```ini
; Mega Man X Legacy Collection
; Underclock to save on battery
[01005C60086BE000]
handheld_cpu=816
handheld_gpu=230
handheld_mem=665
```

```ini
; Mega Man X Legacy Collection 2
; Underclock CPU, Mem to save on battery
[01005250086C4000]
handheld_cpu=714
handheld_mem=1065
```

```ini
; Metroid Dread
; Underclock to save battery/ lower heat 
; Overclock to improve preformance 
[010093801237C000]
handheld_cpu=714
handheld_mem=1600
docked_cpu=918
docked_gpu=844
```

```ini
; Mighty Gunvolt Burst
; Underclock to save battery with bare minimum settings
[01000E2003FA0000]
handheld_cpu=612
handheld_gpu=76
handheld_mem=665
```

```ini
; Minecraft
; Better Framerate
[0100D71004694000]
handheld_cpu=1224
handheld_mem=1600
```

```ini
; Minecraft Story Mode
; Overclock to improve load times
; Overclock to hit 60fps more
; Underclock to save battery
[010059C002AC2000]
handheld_cpu=816
handheld_gpu=460
handheld_mem=1600
handheld_charging_cpu=1428
handheld_charging_gpu=768
handheld_charging_official_gpu=921
docked_cpu=1428
docked_gpu=921
```

```ini
; Minecraft Story Mode, season 2
; Overclock to maintain 60fps
[01003EF007ABA000]
handheld_gpu=460
handheld_mem=1600
handheld_charging_cpu=1428
handheld_charging_gpu=768
docked_cpu=1428
docked_gpu=921
```

```ini
; MISTOVER
; Underclock to improve battery/ reduce heat
; Overclock to imrpove preformance
[010034E00EFD0000]
handheld_cpu=714
handheld_mem=1600
handheld_charging_gpu=460
docked_cpu=816
docked_gpu=921
```

```ini
; Modern Combat Blackout
; Absolutely needed to avoid frame drops in handheld mode
[0100D8700B712000]
handheld_gpu=460
handheld_mem=1600
```

```ini
; Mutant Mudds Collection
; Underclock to save battery with bare minimum settings
[01004BE004A86000]
handheld_cpu=612
handheld_gpu=76
handheld_mem=665
```

```ini
; My Big Sister
; Underclock to save battery/ reduce power draw
[0100A0F00D82A000]
handheld_cpu=612
handheld_gpu=76
handheld_mem=665
docked_cpu=612
docked_gpu=76
docked_mem=800
```

```ini
; N++
; Underclock to save battery
[01000D5005974000]
handheld_cpu=612
handheld_gpu=153
handheld_mem=665
```

```ini
; Necrobarista
; Overclock to hit 60fps more
[0100E64015370000]
handheld_cpu=1224
handheld_gpu=460
handheld_mem=1600
handheld_charging_cpu=1428
handheld_charging_gpu=768
handheld_charging_official_gpu=921
docked_cpu=1428
docked_gpu=921
```

```ini
; Need for Speed Hot Pursuit Remastered
; Overclock to improve preformance 
[01029B0118E8000]
handheld_cpu=1224
handheld_mem=1600
handheld_charging_cpu=1581
handheld_charging_gpu=614
docked_cpu=1683
docked_gpu=921
```

```ini
; New Super Mario Bros. U Deluxe
; Underclock to save battery
[0100EA80032EA000]
handheld_cpu=816
handheld_mem=800
; Alternate settings
; Underclock GPU in handheld mode and TV mode to reduce heat
;handheld_gpu=230
;docked_gpu=537
```

```ini
; NEO The World Ends With You DEMO
; Overclock to improve framerates
[01001AB0141A8000]
handheld_cpu=1224
handheld_gpu=460
handheld_mem=1600
handheld_charging_cpu=1785
handheld_charging_gpu=768
handheld_charging_official_gpu=921
docked_cpu=1785
docked_gpu=921
```

```ini
; NEO: The World Ends With You
; Overclock to improve framerates
[010043B013C5C000]
handheld_cpu=1224
handheld_gpu=460
handheld_mem=1600
handheld_charging_cpu=1785
handheld_charging_gpu=768
handheld_charging_official_gpu=844
docked_cpu=1785
docked_gpu=921
```

```ini
; NES - Nintendo Switch Online
; Underclock to save battery
[0100D870045B6000]
handheld_cpu=612
handheld_mem=665
handheld_gpu=76
```

```ini
; NieR: Automata The End of YoRHa Edition
; Overclock to improve framerates
; Higher CPU OC may be required for certain fights
[0100B8E016F76000]
handheld_cpu=1122
handheld_gpu=460
handheld_mem=1600
handheld_charging_cpu=1428
handheld_charging_gpu=614
docked_cpu=1428
docked_gpu=921
```

```ini
; ONINAKI
; Overclock to improve preformance
[01001AF00CE54000]
handheld_cpu=1122
handheld_mem=1600
handheld_charging_cpu=1326
handheld_charging_gpu=537
docked_cpu=1326
docked_gpu=921
```

```ini
; Ori and the Blind Forest
; Overclock to improve preformance and resolution
[010061D00DB74000]
handheld_cpu=1124
handheld_mem=1600
handheld_charging_cpu=1224
handheld_charging_gpu=614
docked_cpu=1224
docked_gpu=921
```

```ini
; Ori and the Will of the Wisps
; Overclock to improve resolution
[01008DD013200000]
handheld_cpu=1124
handheld_mem=1600
handheld_charging_cpu=1326
handheld_charging_gpu=768
handheld_charging_official_gpu=844
docked_cpu=1326
docked_gpu=921
```

```ini
; Override: Mech City Brawl
; Improve resolutions for handheld mode
[0100F2600EA72000]
handheld_gpu=460
handheld_charging_gpu=768
handheld_charging_mem=1600
```

```ini
; Persona 4 Arena Utimax
; Underclock to reduce power draw/ save battery
[010075A016A3A000]
handheld_cpu=612
handheld_gpu=307
docked_cpu=612
docked_gpu=307
```

```ini
; Persona 5 Strikers
; Overclock to improve preformance and help dynamic resolution
[0100801011C3E000]
handheld_cpu=1326
handheld_gpu=460
handheld_mem=1600
handheld_charging_cpu=1785
handheld_charging_gpu=614
docked_cpu=1785
docked_gpu=844
```

```ini
; Picross S4
; Underclock to save battery with bare minimum settings
[0100C250115DC000]
handheld_cpu=612
handheld_gpu=76
```

```ini
; Pillars of Eternity
; Resolves some issues with framepacing
[0100D6200E130000]
handheld_cpu=1581
docked_cpu=1581
```

```ini
; Pokemon Legends: Arceus
; Underclock to save battery
; Overclock to improve resolution
[01001F5010DFA000]
handheld_cpu=714
handheld_gpu=384
handheld_mem=1600
handheld_charging_gpu=537
docked_cpu=816
docked_gpu=844
```

```ini
; Pokemon: Lets go, Eevee!
; Helps reduce UI slowdowns as well as varidian forest.
[0100187003A36000]
handheld_gpu=460
handheld_mem=1600
```

```ini
; Pokemon: Lets go, Pikachu!
; Helps reduce UI slowdowns as well as varidian forest.
[010003f003a34000]
handheld_gpu=460
handheld_mem=1600
```

```ini
; Pokemon Mystery Dungeon: Rescue Team DX (USA)
; Underclock to save battery @30fps
[01003D200BAA2000]
handheld_cpu=816
handheld_mem=1065
```

```ini
; Pokemon Quest
; Since there are no real gameplay elements,
; and that there is very little slowdown in the worlds to worry about
; this game runs absolutely fine at these settings.
[01005D100807A000]
handheld_cpu=612
handheld_gpu=76
handheld_mem=665
```

```ini
; Project Warlock
; Underclock to save battery
[0100BDB01150E000]
handheld_cpu=612
handheld_gpu=153
```

```ini
; PUYO PUYO™ TETRIS® 2
; Underclock to save battery (CPU can go a bit lower but loading times will increase)
[010038E011940000]
handheld_cpu=816
handheld_gpu=230
handheld_mem=800
```

```ini
; Qlaunch
; If you want to save battery in handheld mode 
; while not in a game and not compromise on useablilty.
[0100000000001000]
handheld_cpu=816
handheld_gpu=230
handheld_mem=800
```

```ini
; Resident Evil 4
; More constant 60FPS
[010099A00BC1E000]
handheld_cpu=1224
handheld_gpu=460
handheld_mem=1600 
```

```ini
; Resident Evil 5 Demo
; Overclock to improve performance
[010081D00E6BA000]
handheld_cpu=1224
handheld_gpu=460
handheld_mem=1600
handheld_charging_cpu=1785
handheld_charging_gpu=768
docked_cpu=1785
docked_gpu=921
```

```ini
; Resident Evil 6 Demo
; Overclock to improve performance
[01008ED00E6C0000]
handheld_cpu=1224
handheld_gpu=460
handheld_mem=1600
handheld_charging_cpu=1785
handheld_charging_gpu=768
handheld_charging_offical_gpu=921
docked_cpu=1785
docked_gpu=921
```

```ini
; Resident Evil Revelations 2
; Reduce FPS drops in some areas for handheld
[010095300212A000]
handheld_gpu=460
```

```ini
; RiME
; Better Framerate. Still some slowdowns
[0100A62002042000]
handheld_gpu=460
handheld_mem=1600
```

```ini
; Rolling Sky 2
; Underclock to save battery/ reduce heat
; Overclock to improve performance
[01007C900FD96000]
handheld_gpu=153
handheld_mem=1600
handheld_charging_gpu=537
docked_gpu=537
```

```ini
; Saints Row: The Third - The Full Package
; Improves framerate and/or resolution,
; More headroom when charging.
; Should make open world antics more stable.
[0100DE600BEEE000]
handheld_cpu=1122
handheld_mem=1600
handheld_charging_gpu=460
```

```ini
; Shantae
; Underclock to reduce heat and increase battery life
; GPU can be pushed lower, but the menus will noticeably lag
[0100430013120000]
handheld_cpu=612
handheld_gpu=230
handheld_mem=1600
docked_cpu=612
docked_gpu=307
```

```ini
; Shantae: Risky's Revenge - Directors Cut
; Underclock to recude heat and increase battery life
[0100AD012370000]
handheld_cpu=612
handheld_gpu=153
handheld_mem=1600
docked_cpu=612
docked_gpu=230
```

```ini
; Shin Megami Tensei 3 Nocturne
; Overclock to improve performance
[01003B0012DC2000]
handheld_cpu=1224
handheld_gpu=460
handheld_mem=1600
handheld_charging_cpu=1326
handheld_charging_gpu=691
docked_cpu=1326
docked_gpu=921
```

```ini
; SHIN MEGAMI TENSEI V
; Overclock to improve preformance 
[010063B012DC6000]
handheld_gpu=460
handheld_mem=1600
handheld_charging_gpu=768
handheld_charging_official_gpu=921
docked_gpu=921
```

```ini
; Shovel Knight
; Underclock to save battery with bare minimum settings
[010057D0021E8000]
handheld_cpu=612
handheld_gpu=76
handheld_mem=665
```

```ini
; Sky: Children of the Light
; Overclock to improve performance
[0100C52011460000]
handheld_cpu=1224
handheld_gpu=460
handheld_mem=1600
handheld_charging_cpu=1785
handheld_charging_gpu=768
docked_cpu=1785
docked_gpu=844
```

```ini
; Slender - The Arrival
; Overclock to increase frame rate
[0100FDC00D0C0000]
handheld_gpu=460
handheld_mem=1600
handheld_charging_gpu=768
handheld_charging_official_gpu=921
docked_gpu=921
```

```ini
; Smashy Road: Wanted 2
; Underclock to save battery/reduce heat
; Overclock to improve performance
[010012D016176000]
handheld_cpu=1122
handheld_gpu=230
handheld_mem=1600
docked_cpu=1224
docked_gpu=384
```

```ini
; Snake Pass
; Improve FPS while charging
; Improve battery life in handheld
[0100C0F0020E8000]
handheld_cpu=918
handheld_mem=1600
handheld_charging_cpu=1224
handheld_charging_mem=1600
handheld_charging_gpu=460
```

```ini
; Sonic Colors Ultimate
; Overclock to improve preformance 
[010040E0116B8000]
handheld_gpu=460
handheld_mem=1600
handheld_charging_cpu=1581
handheld_charging_gpu=768
docked_cpu=1581
docked_gpu=921
```

```ini
; Sonic Forces
; Underclock to save battery
; Overclock to improve preformance/ load times
; Adjust cpu if needed
[01001270012B6000]
handheld_cpu=816
handheld_mem=1600
handheld_charging_cpu=1224
handheld_charging_gpu=537
docked_cpu=1224
docked_gpu=921
```

```ini
; Sonic Frontiers
; Overclock to improve preformance
[01004AD014BF0000]
handheld_cpu=1224
handheld_gpu=460
handheld_mem=1600
handheld_charging_cpu=1428
handheld_charging_gpu=768
handheld_charging_offical_gpu=921
docked_cpu=1428
docked_gpu=921
```

```ini
; Sonic Mania
; Underclock to save battery with bare minimum settings
[01009AA000FAA000]
handheld_cpu=612
handheld_gpu=76
handheld_mem=665
```

```ini
; Splatoon 2
; Underclock to save battery
; Overclock to improve resolution
[01003BC0000A0000]
handheld_cpu=816
handheld_mem=1600
handheld_charging_gpu=614
docked_gpu=921
```

```ini
; Splatoon 3
; Overclock to increase resolution
; Note: not tested online, and anything higher than 614mhz GPU isn't needed unless you are planning on playing story mode
[0100C2500FC20000]
handheld_mem=1600
handheld_charging_gpu=768
docked_gpu=921
```

```ini
; Splatoon 3: Splatfest World Premiere
; Overclock to improve resolution
[0100BA0018500000]
handheld_mem=1600
handheld_charging_gpu=537
docked_gpu=921
```

```ini
; Starlink: Battle for Atlas
; Improve resolutions and performance for handheld mode
[01002CC003FE6000]
handheld_charging_gpu=768
handheld_mem=1600
handheld_gpu=460
```

```ini
; Streets of Rage 4
; Underclock to save battery with bare minimum settings
[0100EC9010258000]
handheld_cpu=612
handheld_gpu=76
```

```ini
; SubaraCity
; Underclock to save battery
[0100CD6004130000]
handheld_cpu=612
handheld_gpu=76
```

```ini
; Super Kirby Clash
; Underclock to save battery
[01003FB00C5A8000]
handheld_cpu=918
handheld_mem=1065
```

```ini
; Super Mario 3D All Stars
; The game switches Title IDs when launching any of the games, as such, the game select will be the only thing affected
; Overclock to improve loading times
; Underclock to save some battery
[010049900F546000]
handheld_cpu=714
handheld_gpu=153
handheld_mem=1065
handheld_charging_cpu=1785
docked_cpu=1785
docked_gpu=460
```

```ini
; Super Mario 64 (3D All Stars)
; Underclock to reudce heat/ save battery 
; Note: this will cause the game to load for much longer at the initial loading screen 
[010049900F546001]
handheld_cpu=612
handeheld_gpu=153
handheld_mem=800
docked_cpu=612
docked_gpu=230
docked_mem=1065
```

```ini
; Super Mario Galaxy (3D All Stars)
; Underclock to save battery
[010049900F546003]
handheld_cpu=714
handheld_gpu=307
handheld_mem=1065
docked_cpu=918
docked_gpu=614
```

```ini
; Super Mario Sunshine (3D All Stars)
; Overclock to improve preformance 
; Underclock to save some battery
; Underclock to lower docked power draw
[010049900F546002]
handheld_cpu=1326
handheld_gpu=230
handheld_mem=1600
handheld_charging_cpu=1683
handheld_charging_gpu=460
docked_cpu=1683
docked_gpu=614
```

```ini
; Super Mario 3D World + Bowsers Fury
; Underclock to save battery
; Overclock to improve preformance
; OC for Bowsers Fury, can be disabled for main game
[010028600EBDA000]
handheld_cpu=918
handheld_mem=1600
handheld_charging_cpu=1224
handheld_charging_gpu=614
docked_cpu=1224
docked_gpu=921
```

```ini
; Super Mario Maker 2
; Underclock to save battery (slightly increases loading times)
[01009B90006DC000]
handheld_cpu=816
handheld_gpu=230    
handheld_mem=1065
```

```ini
; Super Mario Odyssey
; Underclock to save battery
; The game has periodic drops to 57fps with this, but it's barely noticeable
; Overclock to improve performance
[0100000000010000]
handheld_cpu=918
handheld_gpu=384
handheld_mem=1600
handheld_charging_cpu=1224
handheld_charging_gpu=460
handheld_charging_mem=1600
docked_cpu=1224
docked_gpu=844
```

```ini
; Super Meat Boy
; Underclock to save battery
[01004F8006A78000]
handheld_cpu=612
handheld_gpu=230
handheld_mem=800
```

```ini
; Super Nintendo - Nintendo Switch Online
; Underclock to save battery with bare minimum settings
[01008D300C50C000]
handheld_cpu=612
handheld_gpu=76
```

```ini
; Super Smash Bros. Ultimate
; Underclock to save battery
[01006A800016E000]
handheld_cpu=816
handheld_mem=1065
; Alternate settings
; Fast loading times, great in game battle speeds and nice battery savings
;handheld_cpu=1220
;handheld_gpu=230
;handheld_mem=1600
```

```ini
; SWORD ART ONLINE: Hollow Realization Deluxe Edition
; Overclock GPU, Mem for smoother framerate in handheld mode
[0100EC400D54E000]
handheld_gpu=460
handheld_mem=1600
```

```ini
; Taiko no Tatsujin Drum 'n' Fun!
; Underclock to save battery
[01002C000B552000]
handheld_cpu=612
handheld_gpu=153
handheld_mem=800
```

```ini
; Tales of Vesperia
; Better performance in cities and map
[01002C0008E52000]
handheld_gpu=460
handheld_mem=1600
```

```ini
; Team Sonic Racing
; Underclock to save battery/ lower heat 
; Overclock to improve preformance 
[010092B0091D0000]
handheld_cpu=612
handheld_mem=1600
docked_cpu=918
docked_gpu=921
```

```ini
; The Alto Collection
; Underclock to save battery/ reduce heat
[01006B100E44C000]
handheld_cpu=714
handheld_gpu=76
handheld_mem=800
docked_cpu=714
docked_gpu=153
docked_mem=1065
```

```ini
; The Binding of Isaac: Afterbirth+
; Underclock to save battery
[010021C000B6A000]
handheld_cpu=612
handheld_gpu=230
handheld_mem=665
```

```ini
; The Grisaia Trilogy
; Underclock to save battery
[01003B300E4AA000]
handheld_cpu=612
habdheld_gpu=76
```

```ini
; The Legend Of Zelda: Skyward Sword HD
; Underclock to save battery/ reduce heat
; The game may drop to 30 frames in certain instances 
[01002DA013484000]
handheld_cpu=714
docked_cpu=816
docked_gpu=691
```

```ini
; The Touryst
; Underclock to save some battery
; Overclock to improve resolution 
[0100C3300D8C4000]
handheld_cpu=816
handheld_gpu=460
handheld_mem=1600
handheld_charging_gpu=537
docked_gpu=921
```

```ini
; The Walking Dead
; Overclock to improve performance
[010029200B6AA000]
handheld_gpu=460
handheld_mem=1600
handheld_charging_cpu=1428
handheld_charging_gpu=768
handheld_charging_official_gpu=921
docked_cpu=1428
docked_gpu=921
```

```ini
; The World Ends With You, Final Remix
; Underclock to save battery
[0100C1500B82E000]
handheld_cpu=714
handheld_gpu=230
handheld_mem=1065
```

```ini
; Tokyo Dark -Remembrance-
; Overclock to improve performance
[01003E500F962000]
handheld_cpu=1326
handheld_gpu=384
handheld_mem=1600
handheld_charging_cpu=1683
handheld_charging_gpu=537
docked_cpu=1683
```

```ini
; Touhou Luna Nights
; Underclock to save battery.
; In fact, this game is so light, it does not struggle AT ALL with all clocks at minimum, still keeping a stable 60fps.
; Haven't tested with boss battles yet, though.
[0100D850131B0000]
handheld_cpu=612
handheld_gpu=76
handheld_mem=665
; Alternate settings
; Underclock to reduce power draw and heat
; Note: Yes this game can run perfectly fine under those gpu clockspeeds, it seems to tax cpu alot though
;handheld_gpu=76
;docked_gpu=76
```

```ini
; Travis Strikes Again
; Tweak as you see fit, 
; this here is to save some battery VIA the gpu at lowest official clock vs 384
; via gbatemp thread
[010011600c946000]
handheld_charging_cpu=1122
handheld_cpu=1122
handheld_gpu=307
```

```ini
; Trials Rising
; OC perform, smoother frames.
[01003E800A102000]
docked_cpu=1224
docked_gpu=844
docked_mem=1600
handheld_cpu=1020
handheld_gpu=460
```

```ini
; Trine 4 The Nightmare Prince
; Overclock GPU for higher resolution
[010055E00CA68000]
handheld_gpu=460
handheld_mem=1600
handheld_charging_gpu=614
handheld_charging_mem=1600
```

```ini
; Turok
; Underclock to save battery on bare minimum settings
[010085500D5F6000]
handheld_cpu=612
handheld_gpu=76
handheld_mem=665
```

```ini
; Turok 2: Seeds of Evil
; Underclock to save battery
[0100CDC00D8D6000]
handheld_cpu=612
handheld_gpu=153
```

```ini
; Ultimate Custom Night
; Overclock to improve framerate
; Underclock to reduce heat
[010033500E444000]
handheld_cpu=1224
handheld_gpu=460
handheld_mem=1600
handheld_charging_cpu=1428
docked_cpu=1428
docked_gpu=537
```

```ini
; Undertale
; Increases battery life
[010080B00AD66000]
handheld_gpu=230
handheld_mem=1065
```

```ini
; Urban Trial Playground
; Slight upclock for CPU and GPU, 
; will help with slowdown and keeps dynamic resolution high, 
; especially when charging
[01001B10068EC000]
docked_cpu=1122
handheld_cpu=1122
handheld_gpu=614
handheld_mem=1600
```

```ini
; VA-11 HALL-A
; Underclock to save battery and to serve more drinks
[010086500D3C8000]
handheld_cpu=816
handheld_gpu=230
handheld_mem=800 
```

```ini
; VVVVVV
; Underclock to save battery with  bare minimum settings
[0100B1E0022F8000]
handheld_cpu=612
handheld_gpu=76
handheld_mem=665
```

```ini
; Warface
; Overclocks GPU, Mem for better performance.
; By default, Warface uses the lower performance
; GPU default setting.
[0100D1E00E972000]
handheld_gpu=384
handheld_mem=1600
```

```ini
; West of Loathing
; Downclock all the things. It's a 2D game.
[010031B00A4E8000]
handheld_cpu=918
handheld_mem=800
handheld_gpu=153.6
```

```ini
; What Remains of Edith Finch
; Higher resolution in handheld mode
[010038900DFE0000]
handheld_cpu=1224
handheld_gpu=460
handheld_mem=1600
```

```ini
; The Witcher 3 - Complete Edition (US)
; Overclock RAM for smoother framerate in handheld mode
; Improve resolutions and performance in handheld_charging
; Limit GPU clock to save battery in handheld. Slight decrease to FPS
; EU version: [01003D100E9C6000]
[0100BFE00E9CA000]
handheld_mem=1600
handheld_gpu=384
handheld_charging_gpu=768
```

```ini
; Wolfenstein II: The New Colossus
; Provides higher resolution with more stable framerate in undocked mode
[01009040091E0000]
handheld_cpu=1224
handheld_gpu=460
handheld_mem=1600
```

```ini
; Wonder Boy Asha in Monster World
; Overclock CPU and GPU and MEM to hit 60 FPS most of the time when handheld
[0100EB2012E36000]
handheld_cpu=1326
handheld_gpu=460
handheld_mem=1600
handheld_charging_cpu=1581
handheld_charging_gpu=768
handheld_charging_mem=1600
```

```ini
; Xenoblade Chronicles 2
; Improves performance and resolution in handheld
[0100E95004038000]
handheld_gpu=460
handheld_mem=1600
```

```ini
; Xenoblade Chronicles 2 Torna
; Improves performance and resolution in handheld
[0100C9F009F7A000]
handheld_gpu=460
handheld_mem=1600
```

```ini
; Xenoblade Chronicles 3
; Overclock to improve preformance
; Note: CPU OC is only active to reduce framedrops in heavy fights
[010074F013262000]
handheld_cpu=1224
handheld_gpu=460
handheld_mem=1600
handheld_charging_gpu=768
handheld_charging_official_gpu=921
docked_cpu=1326
docked_gpu=921
```

```ini
; Xenoblade Chonicles Definitive Edition
; Improves performance and resolution in docked and handheld
; NOTE: CPU OC is for Future Connected, and can be disabled for the regular base game.
[0100FF500E34A000]
docked_gpu=921
docked_cpu=1581
handheld_gpu=460
handheld_cpu=1224
handheld_mem=1600
```

```ini
; Youtube
; Saves battery life with no performance reductions
; NOTE: if you are not planning on watching 1080p60 videos in handheld, reducing everything to minimum speeds has no downsides
; NOTE 2: 76mhz GPU works fine for video playback, but I chose 153mhz because 76mhz causes significant slowdown in the system UI.
[01003A400C3DA000]
handheld_gpu=153
handheld_mem=665
```

```ini
; Ys 8: Lacrimosa of DANA
; Overclock to improve resolution
[01007F200B0C0000]
handheld_cpu=816
handheld_gpu=460
handheld_mem=1600
handheld_charging_gpu=537
handheld_charging_cpu=1122
docked_cpu=1122
docked_gpu=921
```

```ini
; Yu-Gi-Oh!  Legacy of The Duelist: Link Evolution
; Underclock to save battery
; 55-60 FPS in story duels
[010022400BE5A000]
handheld_cpu=612
handheld_gpu=76
```
