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
; Animal Crossing: New Horizons
; underclock to save battery, boost mode will be
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
; Assassin creed 3 remastered 
; Overclock to get the best performance while docked. 
[01007F600B134000]
docked_cpu=1683
docked_gpu=921
docked_mem=1600
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
; Baba is You
; Underclock for a massive battery saving
[01002CD00A51C000]
handheld_cpu=612
handheld_gpu=76
handheld_mem=665
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
; Blossom Tales: The Sleeping King
; Underclock to save battery
[0100C1000706C000]
handheld_cpu=612
handheld_gpu=153
handheld_mem=665
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
; underclock to save battery
[01000B900D8B0000]
handheld_cpu=918
handheld_gpu=153
handheld_mem=1065
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
; Castle Crashers Unlimited
; Underclock to save battery @60fps
[010001300D14A000]
handheld_cpu=612
handheld_gpu=230
handheld_mem=665
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
; Devil May Cry
; Underclock to save battery while maintaining 60fps
[0100E8000D5B8000]
handheld_cpu=816
handheld_gpu=230
handheld_mem=800
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
; Save a bit of battery, retaining performance
[010042000A986000]
handheld_cpu=816
handheld_gpu=307
handheld_mem=1065
; Alternate settings
; Fixed docked & handheld FPS stutter
; docked_cpu=1224
; docked_gpu=768
; handheld_gpu=460
; handheld_charging_gpu=537
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
; Fast RMX
; Improve resolutions for handheld mode
[01009510001CA000]
handheld_gpu=460
handheld_charging_gpu=768
handheld_charging_mem=1600
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
; A Hat in Time
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
; Smooths up things such as general camera movement while in vehicles.
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
; Mario Kart 8 Deluxe
; Underclock to save battery
[0100152000022000]
handheld_cpu=918
handheld_gpu=230
handheld_mem=1065
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
; N++
; Underclock to save battery
[01000D5005974000]
handheld_cpu=612
handheld_gpu=153
handheld_mem=665
```

```ini
; New Super Mario Bros. U Deluxe
; Underclock to save battery
[0100EA80032EA000]
handheld_cpu=816
handheld_mem=800
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
; Override: Mech City Brawl
; Improve resolutions for handheld mode
[0100F2600EA72000]
handheld_gpu=460
handheld_charging_gpu=768
handheld_charging_mem=1600
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
; Pokemon Lets go Eevee
; Helps reduce UI slowdowns as well as varidian forest.
[0100187003A36000]
handheld_gpu=460
handheld_mem=1600
```

```ini
; Pokemon Lets go Pikachu
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
; Shovel Knight
; Underclock to save battery with bare minimum settings
[010057D0021E8000]
handheld_cpu=612
handheld_gpu=76
handheld_mem=665
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
; Sonic Mania
; Underclock to save battery with bare minimum settings
[01009AA000FAA000]
handheld_cpu=612
handheld_gpu=76
handheld_mem=665
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
; Super Mario Maker 2
; Underclock to save battery (slightly increases loading times)
[01009B90006DC000]
handheld_cpu=816
handheld_gpu=230    
handheld_mem=1065
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
```

```ini
; SWORD ART ONLINE: Hollow Realization Deluxe Edition
; Overclock GPU, Mem for smoother framerate in handheld mode
[0100EC400D54E000]
handheld_gpu=460
handheld_mem=1600
```

```ini
; Tales of Vesperia
; Better performance in cities and map
[01002C0008E52000]
handheld_gpu=460
handheld_mem=1600
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
; Undertale
; Increases battery life
[010080B00AD66000]
handheld_gpu=230
handheld_mem=1065
```

```ini
; Urban Trial Playground
; slight upclock for CPU and GPU, 
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
; saves battery life
[01003A400C3DA000]
handheld_gpu=153
handheld_mem=665
```
