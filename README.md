# Yeeps Map Loader -- BETA!

A Unity Editor tool that fetches real Yeeps room data and loads it into unity, ready to export as an FBX for Blender. (you can update the **`YeepsMapLoaderData`** with fixes if you see any)

## Install

**Requires Unity 6000.1.17f1** (matches the real game's engine version — install this exact version from the AssetRipper export screen, other versions aren't tested).

1. Get an AssetRipper export of Yeeps. Inside it you'll have a folder like `ExportedProject`.
2. Download the **`YeepsMapLoaderSetup`** folder from this repo and put it **next to** `ExportedProject`, not inside it:
   ```
   AssetRipper_export_.../
   ├── ExportedProject/
   └── YeepsMapLoaderSetup/   <- put it here
   ```
3. Double-click **`setup.bat`** inside `YeepsMapLoaderSetup`. Leave the window open until it says **Done**.
4. Open `ExportedProject` in Unity and wait for it to finish importing (this can take a while the first time).
5. In Unity's top menu: **Window > TextMeshPro > Import TMP Essential Resources** > **Import**.
6. In Unity's top menu: **Yeeps > Map Loader**. That's the tool.







Official Room/Map Keys
==========================================================

=== Hub ===

nexus
nexus_worlds
public
ch2_hub


=== Chapter 2 World Zones ===

ch2_beach_0
ch2_beach_1
ch2_city_0
ch2_city_2
ch2_desert_0
ch2_desert_2
ch2_fantasy_0
ch2_fantasy_2
ch2_snow_0
ch2_snow_2
ch2_space_0
ch2_space_2
ch2_suburb_1
ch2_researchFacility_0
ch2_researchFacility_1
ch2_horror_0
ch2_horror_1
ch2_horror_2
ch2_horror_3
ch2_horror_4
ch2_horror_5
ch2_horror_6
ch2_horror_7
ch2_horror_8
ch2_horror_9
ch2_horror_10


=== Chapter 2 Dungeons ===

ch2_dungeon_beach
ch2_dungeon_snow
ch2_dungeon_space
ch2_dungeon_suburb
ch2_dungeon_fantasy0
ch2_dungeon_fantasy1


=== Chapter 2 Legacy/Old Rooms ===

ch2_old_blueHouse
ch2_old_playground
ch2_old_starterHouse


=== Chapter 2 Transitions ===

ch2_transition_beach
ch2_transition_city
ch2_transition_city_space
ch2_transition_desert
ch2_transition_fantasy
ch2_transition_researchFacility
ch2_transition_snow
ch2_transition_suburb_fantasy
ch2_transition_suburb_snow


=== Minigames ===

minigame_battleRoyale
minigame_paintWars
minigame_battleArena
minigame_battlecrafts
minigame_boatBattle
minigame_captureTheFlag
minigame_copsAndRobbers
minigame_fishyHarbor
minigame_fortress
minigame_goblinSiege
minigame_impostor
minigame_infestedCastle
minigame_laserTag
minigame_outlawOasis
minigame_outpost
minigame_redVsBlue
minigame_spikeArena
minigame_spleef
minigame_superhero
minigame_toTheTop
minigame_constructionSite
minigame_hill
minigame_petValley
minigame_playground
minigame_propTown
minigame_sky
minigame_theater
minigame_basement
minigame_blueHouse
minigame_starterHouse
