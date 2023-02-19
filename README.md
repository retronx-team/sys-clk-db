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
; 13 Sentinels: Aegis Rim
; Overclock GPU in handheld to get locked 60 FPS 99.9% of time
[01003FC01670C000]
handheld_gpu=460
```

```ini
; A Short Hike
; underclock to reduce power draw and heat
[01004890117B2000]
handheld_gpu=153
docked_gpu=230

; AI: The Somnium Files
; overclock to improve framerate
[010089B00D09C000]
handheld_cpu=1224
handheld_gpu=460
handheld_mem=2131
handheld_charging_cpu=1785
handheld_charging_gpu=768
handheld_charging_official_gpu=921
docked_cpu=1785
docked_gpu=921

; AI: The Somnium Files - Nirvana Initiative
; overclock to improve performance
[0100713016CCC000]
handheld_cpu=1224
handheld_gpu=460
handheld_mem=2131
handheld_charging_cpu=1683
handheld_charging_gpu=768
handheld_charging_official_gpu=921
docked_cpu=1683
docked_gpu=921

; Animal Crossing: New Horizons
; underclock to save battery, boost mode will be
; disabled so loading times will increase, especially when starting the game
[01006F8002326000]
handheld_cpu=612
handheld_gpu=307

; ARMS
; underclock to save battery
[01009B500007C000]
handheld_cpu=918
handheld_gpu=230    
handheld_mem=1065

; Assassin creed 3 remastered 
; overclock to get the best performance while docked. 
[01007F600B134000]
docked_cpu=1683
docked_gpu=921
docked_mem=2131

; Astral Chain
; overclock to improve performance
[01007300020FA000]
handheld_cpu=1224
handheld_mem=2131
handheld_charging_gpu=614
docked_cpu=1428
docked_gpu=921

; Atari Flashback Classics
; massive underclock with no hit to performance
[0100CF3007578000]
handheld_cpu=612
handheld_gpu=76
handheld_mem=665

; Axiom Verge
; underclock to save battery
[0100052004384000]
handheld_cpu=612
handheld_gpu=153
handheld_mem=665

; Azure Striker Gunvolt: Striker Pack
; underclock to reduce heat/save battery
[0100192003FA4000]
handheld_cpu=612
handheld_gpu=153
handheld_mem=665
handheld_charging_mem=800
docked_cpu=612
docked_gpu=153
docked_mem=1065

; Baba is You
; underclock for a massive battery saving
[01002CD00A51C000]
handheld_cpu=612
handheld_gpu=76
handheld_mem=665

; Badland: Game of the Year Edition
; underclock to save battery/ reduce heat
[0100D730151C8000]
handheld_cpu=612
handheld_gpu=153
handheld_mem=665
docked_cpu=612
docked_gpu=307
docked_mem=800

; Bayonetta 2 
; overclock to improve framerates
[01007960049A0000]
handheld_gpu=460
handheld_mem=2131
handheld_charging_cpu=1122
handheld_charging_gpu=768
handheld_charging_official_gpu=921
docked_cpu=1122
docked_gpu=921

; Bendy and the Ink Machine
; underclock to save battery
; overclock to improve performance
[0100D4C00C6C0000]
handheld_cpu=816
handheld_mem=2131
handheld_charging_gpu=460
docked_gpu=921

; Blaster Master Zero 2
; underclock to save battery
[01005AA00D676000]
handheld_cpu=612
handheld_gpu=230
handheld_mem=665

; Blazing Chrome
; underclock to save battery with bare minimum settings
[0100C2700C252000]
handheld_cpu=612
handheld_gpu=76 

; Bloodstained: Curse of the Moon
; underclock to save battery
[01004B800AF5A000]
handheld_cpu=612
handheld_gpu=153
handheld_mem=665

; Bloodstained: Ritual of the Night
; provides the game to run generally smoother in handheld mode
[0100BF500207C000]
docked_cpu=1683
docked_gpu=844
handheld_charging_cpu=1224
handheld_cpu=1224
handheld_gpu=460
handheld_mem=2131

; Blossom Tales: The Sleeping King
; underclock to save battery
[0100C1000706C000]
handheld_cpu=612
handheld_gpu=153
handheld_mem=665

; Bug Fables The Everlasting Sapling
; underclock to save battery
[010051A00E99E000]
handheld_cpu=612
handheld_gpu=230

; Cadence of Hyrule: Crypt of the NecroDancer featuring The Legend of Zelda
; underclock to save battery
[01000B900D8B0000]
handheld_cpu=918
handheld_gpu=153
handheld_mem=1065

; Captain Toad Treasure Tracker 
; underclock to lower heat/ save battery
; overclock to improve resolution 
[01009BF0072D4000]
handheld_cpu=612
handheld_mem=2131
handheld_charging_gpu=537
docked_cpu=612
docked_gpu=921

; CARRION
; underclock to save battery - stable 60fps
[0100B1600E9AE000]
handheld_cpu=612
handheld_gpu=153

; Castle Crashers Unlimited
; underclock to save battery @60fps
[010001300D14A000]
handheld_cpu=612
handheld_gpu=230
handheld_mem=665

; Catherine: Full Body (US)
; underclock to save battery in handheld
; underclock to reduce power consumption docked/official charger
; small resolution penalty in handheld (you can go lower if you don't mind sawtooth)
; no resolution penalty docked
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

; Cave Story+
; underclock to save battery
[0100B7D0022EE000]
handheld_cpu=612
handheld_gpu=153
handheld_mem=665

; Child of light
; overclock to improve performance
; underclock to save battery
[01007D000AD8A000]
handheld_cpu=714
handheld_gpu=384
handheld_mem=2131
handheld_charging_cpu=1224
handheld_charging_gpu=537
docked_cpu=1224
docked_gpu=921

; Crimsonland
; underclock to save battery
[01005640080B0000]
handheld_cpu=612
handheld_gpu=76

; DANDY DUNGEON - LEGEND OF BRAVE YAMADA -
; underclock to save battery
[0100DFB00D808000]
handheld_cpu=816
handheld_gpu=230
handheld_mem=800

; Darksiders II Deathinitive Edition
; improve resolutions and performance for handheld mode
[010071800BA98000]
handheld_gpu=460

; Destroy All Humans! (US)
; underclock CPU to reduce battery/energy consumption in handheld/dock/charger (you can go as low as 612MHz won't drop a frame except in saucer, it will drop between 2 to 4 frames when it gets full of NPCs, but I mean a ridiculously full, that's why 714MHz)
; overclock GPU to increase resolution (Wont be noticeable past 691MHz)
; overclock MEM to reduce object/texture pop-in
[01009E701356A000]
docked_cpu=816
docked_gpu=691
docked_mem=2131
handheld_charging_cpu=714
handheld_charging_gpu=691
handheld_charging_mem=2131
handheld_charging_usb_cpu=714
handheld_charging_usb_gpu=691
handheld_charging_usb_mem=2131
handheld_charging_official_cpu=816
handheld_charging_official_gpu=691
handheld_charging_official_mem=2131
handheld_cpu=714
handheld_gpu=460
handheld_mem=2131

; Devil May Cry
; underclock to save battery while maintaining 60fps
[0100E8000D5B8000]
handheld_cpu=816
handheld_gpu=230
handheld_mem=800

; Donkey Kong Country Tropical Freeze
; underclock GPU when docked to decrease heat
[0100C1F0051B6000]
docked_gpu=614

; DOOM
; Better Framerate (Adjust dock gpu between 768-921 based on your comfort level)
; via GBAtemp thread
[0100416004C00000]
handheld_gpu=460
handheld_mem=2131
handheld_charging_official_gpu=768
docked_cpu=1224
docked_gpu=844

; Doom 1993
; underclock to save battery with bare minimum settings
[010018900DD00000]
handheld_cpu=612
handheld_gpu=76

; Doom 64
; underclock to save battery with bare minimum settings
[01005D700E742000]
handheld_cpu=612
handheld_gpu=76

; Doom II Classic
; underclock to save battery with bare minimum settings
[0100D4F00DD02000]
handheld_cpu=612
handheld_gpu=76

; Dragon Ball Xenoverse 2 (US)
; underclock CPU to reduce battery/energy consumption in handheld/dock/charging (you can go as los as 714MHz, I didn't experience any frame drops but to be sure I left it at 816MHz)
; underclocked GPU on docked/charging to reduce energy consumption (small resolution penalty docked that's why 537MHz, no penalty charging)
; overclocked MEM to reduce object/texture pop-in
[010078D000F88000]
docked_cpu=816
docked_gpu=537
docked_mem=2131
handheld_charging_cpu=816
handheld_charging_gpu=460
handheld_charging_mem=2131
handheld_charging_usb_cpu=816
handheld_charging_usb_gpu=460
handheld_charging_usb_mem=2131
handheld_charging_official_cpu=816
handheld_charging_official_gpu=460
handheld_charging_official_mem=2131
handheld_cpu=816
handheld_gpu=460
handheld_mem=2131

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
handheld_mem=2131

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
handheld_mem=2131

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

; Dragon Quest XI S: Echoes of an Elusive Age - Definitive Edition
; Improves stutter when moving the camera at high speed and improves framerate of far NPC animation (15 -> 30)
[01006C300E9F0000]
docked_cpu=1581

; Drowning 
; overclock to improve framerates
[010052000A574000]
handheld_cpu=1224
handheld_gpu=460
handheld_mem=2131
handheld_charging_cpu=1428
handheld_charging_gpu=768
handheld_charging_official_gpu=921
docked_cpu=1428
docked_gpu=921

; Duke Nukem 3D 20th Anniversary World Tour
; underclock to save battery
[01007EF00CB88000]
handheld_cpu=612
handheld_gpu=230

; Dusk
; underclock to save battery
[01007740160D4000]
handheld_cpu=612
handheld_gpu=153

; Fast RMX
; Improve resolutions for handheld mode
[01009510001CA000]
handheld_gpu=460
handheld_charging_gpu=768
handheld_charging_mem=2131

; FIFA 19
; underclock to reduce power draw/heat
; underclock to save battery
; overclock to slightly improve performance
[0100FFA0093E8000]
handheld_cpu=918
handheld_gpu=307
handheld_mem=1065
handheld_charging_mem=2131
docked_cpu=918
docked_gpu=537

; Five Nights at Freddy's 1
; underclock to save battery
; underclock to lower power draw
; the game will drop frames when switching cameras rapidly, but it happens even on stock
[0100B6200D8D2000]
handheld_cpu=612
handheld_gpu=76
handheld_mem=665
docked_cpu=612
docked_gpu=76
docked_mem=800

; Five Nights at Freddy's 2
; underclock to save battery
; underclock to reduce heat
; the game may drop frames on title screen and on switching cameras quickly
[01004EB00E43A000]
handheld_cpu=612
handheld_gpu=76
handheld_mem=665
docked_cpu=612
docked_gpu=76
docked_mem=800

; Five Nights at Freddy's 3
; underclock to save battery
; underclock to reduce heat
; the game drops frames on camera switching, and there is a slight delay when switching cameras
[010056100E43C000]
handheld_cpu=612
handheld_gpu=76
handheld_mem=665
docked_cpu=612
docked_gpu=76
docked_mem=800

; Five Nights at Freddy's 4
; underclock to save battery
; underclock to reduce heat
; when switching areas the game will drop to 15 frames, then recover
[010083800E43E000]
handheld_cpu=612
handheld_gpu=76
handheld_mem=665
docked_cpu=612
docked_gpu=76
docked_mem=800

; Five Nights at Freddy's Sister Location
; underclock to save battery
; underclock to reduce heat
; when entering a new area, stuttering occurs briefly
[01003B200E440000]
handheld_cpu=612
handheld_gpu=153
handheld_mem=800
docked_cpu=612
docked_gpu=230
docked_mem=1065

; Fire Emblem Three Houses
; provides a smoother framerate whilst undocked and better framerate docked
[010055D009F78000]
docked_cpu=1224
docked_gpu=844
handheld_charging_cpu=1224
handheld_charging_gpu=768
handheld_cpu=1020
handheld_gpu=460
handheld_mem=2131

; Fire Emblem Warriors
; Provides a smoother framerate whilst undocked
[0100F15003E64000]
handheld_cpu=1224
handheld_gpu=460
handheld_mem=2131

; Fire Emblem Warriors: Three Hopes
; overclock to reach higher framerates
[010071F0143EA000]
handheld_cpu=1224
handheld_gpu=460
handheld_mem=2131
handheld_charging_cpu=1785
handheld_charging_gpu=768
handheld_charging_official_gpu=921
docked_cpu=1785
docked_gpu=921

; Florence
; underclock to reduce heat/ save battery 
; Note: Stuttering will occur, so ram OC is enabled to mitigate this
[010040700E8FC000]
handheld_cpu=612
handheld_gpu=153
handheld_mem=2131
docked_cpu=714
docked_gpu=307

; Fortnite
; This enables the game to run generally smoother in handheld mode. 
[010025400AECE000]
handheld_cpu=1224
handheld_gpu=460
handheld_mem=2131

; Furi
; sustain the framerate, more noticeable after the 3rd fight
[01009D3008D20000]
handheld_cpu=1224
handheld_mem=2131

; Grand Theft Auto: San Andreas - The Definitive Edition (US)
; overclock for smoother gameplay
; it will decrease your handheld playtime by 30 to 45 min.
[010065A014024000]
docked_cpu=1581
docked_gpu=768
docked_mem=2131
handheld_charging_cpu=1224
handheld_charging_gpu=460
handheld_charging_mem=2131
handheld_charging_usb_cpu=1224
handheld_charging_usb_gpu=460
handheld_charging_usb_mem=2131
handheld_charging_official_cpu=1581
handheld_charging_official_gpu=768
handheld_charging_official_mem=2131
handheld_cpu=1224
handheld_gpu=460
handheld_mem=2131

; Grandia II
; Massively improved handheld framerate
[0100E0600BBC8002]
handheld_gpu=460

; Gris
; underclock to save battery and reduce heat in docked
; overclock to reduce load times
[0100E1700C31C000]
handheld_cpu=816
handheld_gpu=230
handheld_mem=1065
handheld_charging_cpu=1224
docked_cpu=1224
docked_gpu=460

; Gear Club Unlimited
; eliminates some stutter during races in handheld mode.
[010065E003FD8000]
handheld_gpu=460
handheld_mem=2131

; Gear Club Unlimited 2
; mitigates freezes that occur while racing in handheld mode..
[010072900AFF0000]
handheld_gpu=460
handheld_mem=2131

; Graveyard Keeper
; underclock to save battery (slightly increases loading times)
[0100B6800B5C8000]
handheld_cpu=816
handheld_gpu=230
handheld_mem=800

; Grip
; this enables the game to actually run at 30FPS
[0100459009A2A000]
handheld_cpu=1224
handheld_gpu=460
handheld_mem=2131

; A Hat in Time
; boosts clock for noticeably faster loading screens and better framerate in handheld
; the unfinished Nyakuza included with Seal the Deal's romfs now runs at 30fps
[010056E00853A000]
docked_cpu=1785
docked_gpu=844
handheld_charging_cpu=1785
handheld_charging_gpu=844
handheld_mem=2131

; Hatsune Miku: Project DIVA Mega Mix
; overclock for better load times.
[01001CC00FA1A000]
docked_cpu=1785
handheld_cpu=1785
handheld_mem=2131

; Hyrule Warriors: Age of Calamity
; overclock to improve frame rate and resolution
; docked mode does not maintain stable framerates even with 1785
[01002B00111A2000]
handheld_cpu=1326
handheld_gpu=460
handheld_mem=2131
handheld_charging_cpu=1785
handheld_charging_gpu=614
docked_cpu=1785
docked_gpu=921

; ICEY
; overclock to improve framerate and frame pacing 
[0100BE9007E7E000]
handheld_cpu=1224
handheld_mem=2131
handheld_charging_cpu=1326
handheld_charging_gpu=384
docked_cpu=1326
docked_gpu=844

; Katana Zero
; underclock to save battery
[010029600D56A000]
handheld_cpu=612
handheld_gpu=153

; Kirby Star Allies
; underclock to save battery
[01007E3006DDA000]
handheld_cpu=918
handheld_mem=1065

; LA Noire
; smooths up things such as general camera movement while in vehicles.
[0100830004FB6000]
handheld_mem=2131

; Layers of Fear: Legacy
; more stable 60 FPS across whole game
[0100BF5006A7C000]
handheld_cpu=1224
handheld_gpu=460
handheld_mem=2131

; Legend of Zelda: Link's Awakening
; improved framerate in handheld, resolves most framerate issues in handheld_charging
[01006BB00C6F0000]
handheld_charging_gpu=768
handheld_gpu=460
handheld_mem=2131

; LEGO City Undercover
; smoother framerate in handheld.
[01003A30012C0000]
handheld_gpu=460
handheld_mem=2131

; Lines Infinite
; save them batteries
[0100A9000F17E000]
handheld_cpu=612
handheld_gpu=76
handheld_mem=665

; Luigi's Mansion 3 [700p]
; NOTE: This will lower the res to 700p, but is
; not noticeable in handheld due to TAA
; underclock to save battery
; adjust if needed, still @30fps
[0100DCA0064A6000]
handheld_cpu=714
handheld_gpu=307
handheld_mem=2131

; LUMINES REMASTERED
; underclock to save battery
[0100A4200A284000]
handheld_cpu=918
handheld_gpu=230

; Mario + Rabbids Kingdom Battle
; underclock to improve battery
; overclock to improve performance
; Note: Charger OC is for cutscenes and can be disabled for base game.
; Note: This kneecaps the load times in this game
[010067300059A000]
handheld_cpu=612
handheld_mem=2131
handheld_charging_cpu=1226
handheld_charging_gpu=537
docked_cpu=1226
docked_gpu=921

; Mario Kart 8 Deluxe Booster pass course wave 1
; underclock to save battery
[0100152000022000]
handheld_cpu=918
handheld_gpu=307
handheld_mem=1065

; Marsupilami - Hoobadventure
; overclock CPU and GPU for 60 FPS gameplay in handheld mode. Stages 1-1, 2-4, 2-5 require more power
[010074F014628000]
handheld_cpu=1581
handheld_gpu=460
handheld_mem=2131
handheld_charging_cpu=1581
handheld_charging_gpu=614
handheld_charging_mem=2131

; Marvel Ultimate Alliance 3
; Better framerate in handheld mode
[010060700AC50000]
handheld_charging_cpu=1224
handheld_charging_gpu=768
handheld_charging_mem=2131
handheld_cpu=1020
handheld_gpu=460
handheld_mem=2131

; Max: The Curse of Brotherhood
; underclock to save battery/reduce head
; overclock to improve performance
[01001C9007614000]
handheld_cpu=714
handheld_gpu=384
handheld_mem=2131
handheld_charging_cpu=816
handheld_charging_gpu=537
docked_cpu=816
docked_gpu=537

; Mega Man 11
; underclock to save battery
[0100B0C0086B0000]
handheld_cpu=612
handheld_gpu=230
handheld_mem=665

; Mega Man X Legacy Collection
; underclock to save on battery
[01005C60086BE000]
handheld_cpu=816
handheld_gpu=230
handheld_mem=665

; Mega Man X Legacy Collection 2
; underclock CPU, mem to save on battery
[01005250086C4000]
handheld_cpu=714
handheld_gpu=153
handheld_mem=665

; Metroid Dread
; underclock to save battery/ lower heat 
; overclock to improve performance 
[010093801237C000]
handheld_cpu=714
handheld_mem=2131
docked_cpu=918
docked_gpu=844

; Mighty Gunvolt Burst
; underclock to save battery with bare minimum settings
[01000E2003FA0000]
handheld_cpu=612
handheld_gpu=76
handheld_mem=665

; Minecraft
; Better Framerate
[0100D71004694000]
handheld_cpu=1224
handheld_mem=2131
 
; Minecraft story mode
; overclock to improve load times
; overclock to hit 60fps more
; underclock to save battery
; 
[010059C002AC2000]
handheld_cpu=816
handheld_gpu=460
handheld_mem=2131
handheld_charging_cpu=1428
handheld_charging_gpu=768
handheld_charging_official_gpu=921
docked_cpu=1428
docked_gpu=921

; Minecraft story mode, season 2
; overclock to maintain 60fps
[01003EF007ABA000]
handheld_gpu=460
handheld_mem=2131
handheld_charging_cpu=1428
handheld_charging_gpu=768
docked_cpu=1428
docked_gpu=921

; MISTOVER
; underclock to improve battery/ reduce heat
; overclock to improve performance
[010034E00EFD0000]
handheld_cpu=714
handheld_mem=2131
handheld_charging_gpu=460
docked_cpu=816
docked_gpu=921

; Modern Combat Blackout
; Absolutely needed to avoid frame drops in handheld mode
[0100D8700B712000]
handheld_gpu=460
handheld_mem=2131

; Mutant Mudds Collection
; underclock to save battery with bare minimum settings
[01004BE004A86000]
handheld_cpu=612
handheld_gpu=76
handheld_mem=665

; My Big Sister
; underclock to save battery/ reduce power draw
[0100A0F00D82A000]
handheld_cpu=612
handheld_gpu=76
handheld_mem=665
docked_cpu=612
docked_gpu=76
docked_mem=800

; N++
; underclock to save battery
[01000D5005974000]
handheld_cpu=612
handheld_gpu=153
handheld_mem=665

; Necrobarista
; overclock to hit 60fps more
[0100E64015370000]
handheld_cpu=1224
handheld_gpu=460
handheld_mem=2131
handheld_charging_cpu=1428
handheld_charging_gpu=768
handheld_charging_official_gpu=921
docked_cpu=1428
docked_gpu=921

; Need for Speed Hot Pursuit Remastered
; overclock to improve performance 
[010029B0118E8000]
handheld_cpu=1224
handheld_mem=2131
handheld_charging_cpu=1581
handheld_charging_gpu=614
docked_cpu=1683
docked_gpu=921

; NEO The World Ends With You DEMO
; overclock to improve framerates
[01001AB0141A8000]
handheld_cpu=1224
handheld_gpu=460
handheld_mem=2131
handheld_charging_cpu=1785
handheld_charging_gpu=768
handheld_charging_official_gpu=921
docked_cpu=1785
docked_gpu=921
``
; NEO: The World Ends With You 
; overclock to improve framerates
[010043B013C5C000]
handheld_cpu=1224
handheld_gpu=460
handheld_mem=2131
handheld_charging_cpu=1785
handheld_charging_gpu=768
handheld_charging_official_gpu=844
docked_cpu=1785
docked_gpu=921

; New Super Mario Bros. U Deluxe
; underclock to save battery
[0100EA80032EA000]
handheld_cpu=816
handheld_gpu=230
handheld_mem=800
docked_gpu=537

; NES - Nintendo Switch Online
; underclock to save battery
[0100D870045B6000]
handheld_cpu=612
handheld_mem=665
handheld_gpu=76

; NieR:Automata The End of YoRHa Edition
; overclock to improve framerates
; higher COU OC may be required for certain fights
[0100B8E016F76000]
handheld_cpu=1122
handheld_gpu=460
handheld_mem=2131
handheld_charging_cpu=1428
handheld_charging_gpu=614
docked_cpu=1428
docked_gpu=921

; ONINAKI
; overclock to improve performance
[01001AF00CE54000]
handheld_cpu=1122
handheld_mem=2131
handheld_charging_cpu=1326
handheld_charging_gpu=537
docked_cpu=1326
docked_gpu=921

; Ori and the Blind Forest
; overclock to improve performance and resolution
[010061D00DB74000]
handheld_cpu=1124
handheld_mem=2131
handheld_charging_cpu=1224
handheld_charging_gpu=614
docked_cpu=1224
docked_gpu=921

; Ori and the Will of the Wisps 
; overclock to improve resolution
[01008DD013200000]
handheld_cpu=1124
handheld_mem=2131
handheld_charging_cpu=1326
handheld_charging_gpu=768
handheld_charging_official_gpu=844
docked_cpu=1326
docked_gpu=921

; Override: Mech City Brawl
; Improve resolutions for handheld mode
[0100F2600EA72000]
handheld_gpu=460
handheld_charging_gpu=768
handheld_charging_mem=2131

; Persona 4 Arena Utimax
; underclock to reduce power draw/ save battery
[010075A016A3A000]
handheld_cpu=612
handheld_gpu=307
docked_cpu=612
docked_gpu=307

; Persona 5 Strikers
; overclock to improve performance and help dynamic resolution
[0100801011C3E000]
handheld_cpu=1326
handheld_gpu=460
handheld_mem=2131
handheld_charging_cpu=1785
handheld_charging_gpu=614
docked_cpu=1785
docked_gpu=844

; Picross
; underclock to save battery
[0100BA0003EEA000]
handheld_cpu=816
handheld_gpu=153
handheld_mem=800

; Picross S4
; underclock to save battery with bare minimum settings
[0100C250115DC000]
handheld_cpu=612
handheld_gpu=76

; Pillars of Eternity
; Resolves some issues with framepacing
[0100D6200E130000]
handheld_cpu=1581
docked_cpu=1581

; Pokemon Legends: Arceus
; underclock to save battery
; overclock to improve resolution
[01001F5010DFA000]
handheld_cpu=714
handheld_gpu=384
handheld_mem=2131
handheld_charging_gpu=537
docked_cpu=816
docked_gpu=844

; Pokemon Lets go Eevee
; Helps reduce UI slowdowns as well as varidian forest.
[0100187003A36000]
handheld_gpu=460
handheld_mem=2131

; Pokemon Lets go Pikachu
; Helps reduce UI slowdowns as well as varidian forest.
[010003f003a34000]
handheld_gpu=460
handheld_mem=2131

; Pokemon Mystery Dungeon: Rescue Team DX (USA)
; underclock to save battery @30fps
[01003D200BAA2000]
handheld_cpu=816
handheld_mem=1065

; Pokemon Quest
; Since there are no real gameplay elements,
; and that there is very little slowdown in the worlds to worry about
; this game runs absolutely fine at these settings.
[01005D100807A000]
handheld_cpu=612
handheld_gpu=76
handheld_mem=665

; Project Warlock
; underclock to save battery
[0100BDB01150E000]
handheld_cpu=612
handheld_gpu=153

; PUYO PUYO™ TETRIS® 2
; underclock to save battery (Cpu can go a bit lower but loading times will increase)
[010038E011940000]
handheld_cpu=816
handheld_gpu=230
handheld_mem=800

; Qlaunch
; If you want to save battery in handheld mode 
; while not in a game and not compromise on usability.
[0100EF0015A9A000]
handheld_cpu=1581
handheld_gpu=153
handheld_mem=2131
docked_cpu=1581
docked_gpu=153

; Resident Evil 4
; More constant 60FPS
[010099A00BC1E000]
handheld_cpu=1224
handheld_gpu=460
handheld_mem=2131 

; Resident Evil 5 Demo 
; overclock to improve performance
[010081D00E6BA000]
handheld_cpu=1224
handheld_gpu=460
handheld_mem=2131
handheld_charging_cpu=1785
handheld_charging_gpu=768
docked_cpu=1785
docked_gpu=921

; Resident Evil 6 Demo 
; overclock to improve performance
[01008ED00E6C0000]
handheld_cpu=1224
handheld_gpu=460
handheld_mem=2131
handheld_charging_cpu=1785
handheld_charging_gpu=768
handheld_charging_official_gpu=921
docked_cpu=1785
docked_gpu=921

; Resident Evil Revelations 2
; Reduce FPS drops in some areas for handheld
[010095300212A000]
handheld_gpu=460

; RiME
; Better Framerate. Still some slowdowns
[0100A62002042000]
handheld_gpu=460
handheld_mem=2131

; Rolling Sky 2 
; underclock to save battery/ reduce heat
; overclock to improve performance
[01007C900FD96000]
handheld_gpu=153
handheld_mem=2131
handheld_charging_gpu=537
docked_gpu=537

; Saints Row: The Third - The Full Package
; Improves framerate and/or resolution,
; More headroom when charging.
; Should make open world antics more stable.
[0100DE600BEEE000]
handheld_cpu=1122
handheld_mem=2131
handheld_charging_gpu=460

; Shantae
; underclock to reduce heat and increase battery life
; Gpu can be pushed lower, but the menus will noticeably lag
[0100430013120000]
handheld_cpu=612
handheld_gpu=230
handheld_mem=2131
docked_cpu=612
docked_gpu=307

; Shantae: Risky's Revenge - Directors Cut
; underclock to reduce heat and increase battery life
[0100ADA012370000]
handheld_cpu=612
handheld_gpu=153
handheld_mem=2131
docked_cpu=612
docked_gpu=230

; Shin Megami Tensei 3 Nocturne
; overclock to improve performance
[01003B0012DC2000]
handheld_cpu=1224
handheld_gpu=460
handheld_mem=2131
handheld_charging_cpu=1326
handheld_charging_gpu=691
docked_cpu=1326
docked_gpu=921

; SHIN MEGAMI TENSEI V
; overclock to improve performance 
[010063B012DC6000]
handheld_gpu=460
handheld_mem=2131
handheld_charging_gpu=768
handheld_charging_official_gpu=921
docked_gpu=921

; Shovel Knight
; underclock to save battery with bare minimum settings
[010057D0021E8000]
handheld_cpu=612
handheld_gpu=76
handheld_mem=665

; Sky: Children of the Light 
; overclock to improve performance
[0100C52011460000]
handheld_cpu=1224
handheld_gpu=460
handheld_mem=2131
handheld_charging_cpu=1785
handheld_charging_gpu=768
docked_cpu=1785
docked_gpu=844

; Slender - The Arrival
; overclock to increase frame rate
[0100FDC00D0C0000]
handheld_gpu=460
handheld_mem=2131
handheld_charging_gpu=768
handheld_charging_official_gpu=921
docked_gpu=921

; Smashy Road: Wanted 2
; underclock to save battery/reduce heat
; overclock to improve performance
[010012D016176000]
handheld_cpu=1122
handheld_gpu=230
handheld_mem=2131
docked_cpu=1224
docked_gpu=384

; Snake Pass
; Improve FPS while charging
; Improve battery life in handheld
[0100C0F0020E8000]
handheld_cpu=918
handheld_mem=2131
handheld_charging_cpu=1224
handheld_charging_mem=2131
handheld_charging_gpu=460

; Sonic Colors Ultimate
; overclock to improve performance 
[010040E0116B8000]
handheld_gpu=460
handheld_mem=2131
handheld_charging_cpu=1581
handheld_charging_gpu=768
docked_cpu=1581
docked_gpu=921

; Sonic Forces
; underclock to save battery
; overclock to improve performance/ load times
; Adjust cpu if needed
[01001270012B6000]
handheld_cpu=816
handheld_mem=2131
handheld_charging_cpu=1224
handheld_charging_gpu=537
docked_cpu=1224
docked_gpu=921

; Sonic Frontiers 
; overclock to improve performance
[01004AD014BF0000]
handheld_cpu=1224
handheld_gpu=460
handheld_mem=2131
handheld_charging_cpu=1428
handheld_charging_gpu=768
handheld_charging_official_gpu=921
docked_cpu=1428
docked_gpu=921

; Sonic Mania
; underclock to save battery with bare minimum settings
[01009AA000FAA000]
handheld_cpu=612
handheld_gpu=76
handheld_mem=665

; Splatoon 2
; underclock to save battery
; overclock to improve resolution
[01003BC0000A0000]
handheld_cpu=816
handheld_mem=2131
handheld_charging_gpu=614
docked_gpu=921

; Splatoon 3 
; overclock to increase resolution
; Note: not tested online, and anything higher than 614MHz GPU isn't needed unless you are planning on playing story mode
[0100C2500FC20000]
handheld_mem=2131
handheld_charging_gpu=768
docked_gpu=921

; Splatoon 3: Splatfest World Premiere
; overclock to improve resolution
[0100BA0018500000]
handheld_mem=2131
handheld_charging_gpu=537
docked_gpu=921

; Starlink: Battle for Atlas
; Improve resolutions and performance for handheld mode
[01002CC003FE6000]
handheld_charging_gpu=768
handheld_mem=2131
handheld_gpu=460

; Streets of Rage 4
; underclock to save battery with bare minimum settings
[0100EC9010258000]
handheld_cpu=612
handheld_gpu=76

; SubaraCity
; underclock to save battery
[0100CD6004130000]
handheld_cpu=612
handheld_gpu=76

; Super Kirby Clash
; underclock to save battery
[01003FB00C5A8000]
handheld_cpu=918
handheld_mem=1065

; Super Mario 3d All Stars
; The game switches title ids when launching any of the games, as such, the game select will be the only thing affected
; overclock to improve loading times
; underclock to save some battery
[010049900F546000]
handheld_cpu=714
handheld_gpu=153
handheld_mem=1065
handheld_charging_cpu=1785
docked_cpu=1785
docked_gpu=460

; Super Mario 3d World + Bowsers Fury
; underclock to save battery
; overclock to improve performance
; OC for bowsers fury, can be disabled for main game
[010028600EBDA000]
handheld_cpu=918
handheld_mem=2131
handheld_charging_cpu=1224
handheld_charging_gpu=614
docked_cpu=1224
docked_gpu=921

; Super Mario 64 (3d All Stars)
; underclock to reduce heat/ save battery 
; Note: this will cause the game to load for much longer at the initial loading screen 
[010049900F546001]
handheld_cpu=612
handheld_gpu=153
handheld_mem=800
docked_cpu=612
docked_gpu=230
docked_mem=1065

; Super Mario Galaxy (3d all stars)
; underclock to save battery
[010049900F546003]
handheld_cpu=714
handheld_gpu=307
handheld_mem=1065
docked_cpu=918
docked_gpu=614

; Super Mario Maker 2
; underclock to save battery (slightly increases loading times)
[01009B90006DC000]
handheld_cpu=816
handheld_gpu=230    
handheld_mem=1065

; Super Mario Odyssey
; underclock to save battery
; The game has periodic drops to 57fps with this, but it's barely noticeable
; overclock to improve performance
[0100000000010000]
handheld_cpu=918
handheld_gpu=384
handheld_mem=2131
handheld_charging_cpu=1224
handheld_charging_gpu=460
handheld_charging_mem=2131
docked_cpu=1224
docked_gpu=844

; Super Mario Sunshine (3d All Stars)
; overclock to improve performance 
; underclock to save some battery
; underclock to lower docked power draw
[010049900F546002]
handheld_cpu=1326
handheld_gpu=230
handheld_mem=2131
handheld_charging_cpu=1683
handheld_charging_gpu=460
docked_cpu=1683
docked_gpu=614

; Super Meat Boy
; underclock to save battery
[01004F8006A78000]
handheld_cpu=612
handheld_gpu=230
handheld_mem=800

; Super Nintendo - Nintendo Switch Online
; underclock to save battery with bare minimum settings
[01008D300C50C000]
handheld_cpu=612
handheld_gpu=76

; Super Smash Bros. Ultimate
; underclock to save battery
[01006A800016E000]
handheld_cpu=816
handheld_mem=1065

; SWORD ART ONLINE: Hollow Realization Deluxe Edition
; overclock GPU, Mem for smoother framerate in handheld mode
[0100EC400D54E000]
handheld_gpu=460
handheld_mem=2131

; Taiko no Tatsujin Drum 'n' Fun!
; underclock to save battery
[01002C000B552000]
handheld_cpu=612
handheld_gpu=153
handheld_mem=800

; Tales of Vesperia
; Better performance in cities and map
[01002C0008E52000]
handheld_gpu=460
handheld_mem=2131

; Team Sonic Racing 
; underclock to save battery/ lower heat 
; overclock to improve performance 
[010092B0091D0000]
handheld_cpu=612
handheld_mem=2131
docked_cpu=918
docked_gpu=921

; The Alto Collection
; underclock to save battery/ reduce heat
[01006B100E44C000]
handheld_cpu=714
handheld_gpu=76
handheld_mem=800
docked_cpu=714
docked_gpu=153
docked_mem=1065

; The Binding of Isaac: Afterbirth+
; underclock to save battery
[010021C000B6A000]
handheld_cpu=612
handheld_gpu=230
handheld_mem=665

; The Grisaia Trilogy
; underclock to save battery
[01003B300E4AA000]
handheld_cpu=612
handheld_gpu=76

; The Legend of Zelda - Breath of the Wild
; overclock CPU when docked
; overclock MEM to docked clocks when handheld
[01007EF00011E000]
docked_cpu=1224
handheld_mem=2131

; The Legend Of Zelda: Skyward Sword HD
; underclock to save battery/ reduce heat
; The game may drop to 30 frames in certain instances 
[01002DA013484000]
handheld_cpu=714
docked_cpu=816
docked_gpu=691

; The Touryst
; underclock to save some battery
; overclock to improve resolution 
[0100C3300D8C4000]
handheld_cpu=816
handheld_gpu=460
handheld_mem=2131
handheld_charging_gpu=537
docked_gpu=921

; The Walking Dead
; overclock to improve performance
[010029200B6AA000]
handheld_gpu=460
handheld_mem=2131
handheld_charging_cpu=1428
handheld_charging_gpu=768
handheld_charging_official_gpu=921
docked_cpu=1428
docked_gpu=921

; The Wonderful 101: Remastered
; overclock to improve performance
[0100B1300FF08000]
handheld_cpu=1224
handheld_gpu=460
handheld_mem=2131
handheld_charging_cpu=1785
handheld_charging_gpu=768
handheld_charging_official_gpu=921
docked_cpu=1785
docked_gpu=921

; The World Ends With You, Final Remix
; underclock to save battery
[0100C1500B82E000]
handheld_cpu=714
handheld_gpu=230
handheld_mem=1065

; Tokyo Dark -Remembrance-
; overclock to improve performance
[01003E500F962000]
handheld_cpu=1326
handheld_gpu=384
handheld_mem=2131
handheld_charging_cpu=1683
handheld_charging_gpu=537
docked_cpu=1683

; Touhou Luna Nights
; underclock to reduce power draw and heat
; Note: Yes this game can run perfectly fine under those gpu clockspeeds, it seems to tax cpu alot though
[0100D850131B0000]
handheld_cpu=612
handheld_gpu=76
docked_gpu=76
handheld_mem=665

; Travis Strikes Again
; Tweak as you see fit, 
; this here is to save some battery VIA the gpu at lowest official clock vs 384
; via GBAtemp thread
[010011600c946000]
handheld_charging_cpu=1122
handheld_cpu=1122
handheld_gpu=307

; Trials Rising
; OC perform, smoother frames.
[01003E800A102000]
docked_cpu=1224
docked_gpu=844
docked_mem=2131
handheld_cpu=1020
handheld_gpu=460

; Trine 4 The Nightmare Prince
; overclock GPU for higher resolution
[010055E00CA68000]
handheld_gpu=460
handheld_mem=2131
handheld_charging_gpu=614
handheld_charging_mem=2131

; Turok
; underclock to save battery on bare minimum settings
[010085500D5F6000]
handheld_cpu=612
handheld_gpu=76
handheld_mem=665

; Turok 2: Seeds of Evil
; underclock to save battery
[0100CDC00D8D6000]
handheld_cpu=612
handheld_gpu=153

; Ultimate Custom Night
; overclock to improve framerate
; underclock to reduce heat
[010033500E444000]
handheld_cpu=1224
handheld_gpu=460
handheld_mem=2131
handheld_charging_cpu=1428
docked_cpu=1428
docked_gpu=537

; Undertale
; Increases battery life
[010080B00AD66000]
handheld_gpu=230
handheld_mem=1065

; Urban Trial Playground
; slight upclock for CPU and GPU, 
; will help with slowdown and keeps dynamic resolution high, 
; especially when charging
[01001B10068EC000]
docked_cpu=1122
handheld_cpu=1122
handheld_gpu=614
handheld_mem=2131

; VA-11 HALL-A
; underclock to save battery and to serve more drinks
[010086500D3C8000]
handheld_cpu=816
handheld_gpu=230
handheld_mem=800 

; VVVVVV
; underclock to save battery with  bare minimum settings
[0100B1E0022F8000]
handheld_cpu=612
handheld_gpu=76
handheld_mem=665

; Warface
; overclocks GPU, Mem for better performance.
; By default, Warface uses the lower performance
; GPU default setting.
[0100D1E00E972000]
handheld_gpu=384
handheld_mem=2131

; West of Loathing
; Downclock all the things. It's a 2D game.
[010031B00A4E8000]
handheld_cpu=918
handheld_mem=800
handheld_gpu=153.6

; What Remains of Edith Finch
; Higher resolution in handheld mode
[010038900DFE0000]
handheld_cpu=1224
handheld_gpu=460
handheld_mem=2131

; The Witcher 3 - Complete Edition (US)
; overclock RAM for smoother framerate in handheld mode
; Improve resolutions and performance in handheld_charging
; Limit GPU clock to save battery in handheld. Slight decrease to FPS
; EU version: [01003D100E9C6000]
[0100BFE00E9CA000]
handheld_mem=2131
handheld_gpu=384
handheld_charging_gpu=768

; Wolfenstein II: The New Colossus
; Provides higher resolution with more stable framerate in undocked mode
[01009040091E0000]
handheld_cpu=1224
handheld_gpu=460
handheld_mem=2131

; Wonder Boy Asha in Monster World
; overclock CPU and GPU and MEM to hit 60 FPS most of the time when handheld
[0100EB2012E36000]
handheld_cpu=1326
handheld_gpu=460
handheld_mem=2131
handheld_charging_cpu=1581
handheld_charging_gpu=768
handheld_charging_mem=2131

; Xenoblade Chronicles Definitive Edition
; Improves performance and resolution in docked and handheld
; NOTE: CPUOCis for Future Connected, and can be disabled for the regular base game.
[0100FF500E34A000]
docked_gpu=921
docked_cpu=1581
handheld_gpu=460
handheld_cpu=1224
handheld_mem=2131

; Xenoblade Chronicles 2
; Improves performance and resolution in handheld
[0100E95004038000]
handheld_gpu=460
handheld_mem=2131

; Xenoblade Chronicles 2 Torna
; Improves performance and resolution in handheld
[0100C9F009F7A000]
handheld_gpu=460
handheld_mem=2131

; Xenoblade Chronicles 3
; overclock to improve performance
; Note: CPUOCis only active to reduce framedrops in heavy fights
[010074F013262000]
handheld_cpu=1224
handheld_gpu=460
handheld_mem=2131
handheld_charging_gpu=768
handheld_charging_official_gpu=921
docked_cpu=1326
docked_gpu=921

; Youtube
; saves battery life
[01003A400C3DA000]
handheld_gpu=153
handheld_mem=665

; Ys 8: Lacrimosa of DANA
; overclock to improve resolution
[01007F200B0C0000]
handheld_cpu=816
handheld_gpu=460
handheld_mem=2131
handheld_charging_gpu=537
handheld_charging_cpu=1122
docked_cpu=1122
docked_gpu=921

; Yu-Gi-Oh!  Legacy of The Duelist: Link Evolution
; underclock to save battery
; 55-60 FPS in story duels
[010022400BE5A000]
handheld_cpu=612
handheld_gpu=76

; 'n Verlore Verstand
; overclock to improve performance
[010098800C4B0000]
handheld_gpu=460
handheld_mem=2131
handheld_charging_gpu=768
handheld_charging_official_gpu=921
docked_gpu=921
