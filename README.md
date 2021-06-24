# 3DS Saves
My saved games for 3DS - unlocks, finished games, 100%.

Usable with [JKSM](https://github.com/J-D-K/JKSM/releases) and [Checkpoint](https://github.com/FlagBrew/Checkpoint/releases)

## Structure:
```
- Saves
  |- <TitleID>
  |  \- <Game Name as listed in JKSM>
  |     \- <Named directory containing save data>
```

## Usage
<details>
  <summary>JKSM</summary>
  
  - Backup the game in question once to make things easier
  - Download the save game directory (e.g. `complete`) for the game you want (if region doesn't match, try anyway. Most should still work)
  - Copy the downloaded directory into `sdcard:/JKSV/Saves/<Game Name>/`, so it looks like e.g. `sdcard:/JKSV/Saves/SUPER MARIO 3D LAND/complete/` - [Note 1](#note1)
  - If the table lists ExtData for the game, repeat the steps with `sdcard:/JKSV/ExtData/`
  - Start JKSM and restore the save and, if applicable, ExtData
</details>

<details>
  <summary>Checkpoint</summary>
  
  - Start Checkpoint once to initialize all directories
  - Download the save game directory (e.g. `complete`) for the game you want (if region doesn't match, try anyway. Most should still work)
  - Find the Checkpoint save game directory: open `sdcard:/3ds/Checkpoint/saves/`, look for `0x<digits 10-14 of Title ID> <Game Name>`, e.g. `0x0053F Super Mario 3D Land`
  - Copy the downloaded directory into `sdcard:/3ds/Checkpoint/saves/<Game directory>/`, so it looks like e.g. `sdcard:/3ds/Checkpoint/saves/0x0053F SUPER MARIO 3D LAND/complete/` 
  - If the table lists ExtData for the game, download and copy to `sdcard:/3ds/Checkpoint/extdata/<Game directory>/`
  - Start Checkpoint and restore the save and, if applicable, ExtData
</details>

# Saves

Game Name | TitleID | Region | ExtData | Status
----------|---------|--------|---------|-------
[Ace Attorney Trilogy](../main/Saves/0004000000138F00/Ace%20Attorney%20Trilogy/) (Phoenix Wright)|0004000000138F00|USA|No|100%
[Azure Striker Gunvolt](../main/Saves/000400000014C800/AZURE%20STRIKER%20GUNVOLT/)|000400000014C800|USA|No|Game beaten
[Azure Striker Gunvolt 2](../main/Saves/0004000000196A00/AZURE%20STRIKER%20GUNVOLT%202/)|0004000000196A00|USA|No|Game beaten
[Bravely Default](../main/Saves/00040000000FC500/BRAVELY%20DEFAULT/)|00040000000FC500|USA|No|0% with DLC costumes unlocked
[Legend of Zelda: A Link Between Worlds](../main/Saves/00040000000EC300/The%20Legend%20of%20Zelda/)|00040000000EC300|USA|No|Game beaten, [Note 1](#note1)
[Mario & Luigi: Bowser's Inside Story + Bowser Jr.’s Journey](../main/Saves/00040000001D1400/Mario%20&%20Luigi%20%20Bowser's%20Inside…/)|00040000001D1400|USA|No|Game Beaten
[Mario & Luigi: Paper Jam](../main/Saves/0004000000132700/Mario%20&%20Luigi%20%20Paper…/)|0004000000132700|USA|No|Game beaten
[Mario & Luigi: Superstar Saga + Bowser's Minions](../main/Saves/00040000001B8F00/Mario%20&%20Luigi%20%20Superstar…/)|00040000001B8F00|USA|No|Game beaten
[Metroid: Saums Returns](../main/Saves/00040000001BB200/Metroid%20%20Samus%20Returns/)|00040000001BB200|USA|No|Game beaten, Fusion Mode unlocked
[Mighty Gunvolt](../main/Saves/000400000014CD00/MIGHTY%20GUNVOLT/)|000400000014CD00|USA|No|Game beaten
[Picross e](../main/Saves/00040000000A9200/Picross%20e/)|00040000000A9200|EUR|No|100%
[Picross e2](../main/Saves/00040000000CBC00/Picross%20e2/)|00040000000CBC00|EUR|No|100%
[Picross e3](../main/Saves/0004000000102900/Picross%20e3/)|0004000000102900|EUR|No|100%
[Picross e4](../main/Saves/0004000000128400/Picross%20e4/)|0004000000128400|EUR|No|100% including bonus puzzles
[Picross e5](../main/Saves/000400000014D200/Picross%20e5/)|000400000014D200|EUR|No|100% including bonus puzzles
[Prof. Layton vs Phoenix Wright](../main/Saves/0004000000100700/Prof%20%20Layton%20vs%20Phoenix%20Wrigh/)|0004000000100700|USA|[Yes](../main/ExtData/0004000000100700/Prof%20%20Layton%20vs%20Phoenix%20Wrigh/)|100% including bonus puzzles

 
## Notes
<a name="note1"></a>Note 1: Directory name collision: JKSM stores "The Legend of Zelda<b>&trade;</b>" (Zelda I) as "The Legend of Zelda". "The Legend of Zelda: A Link Between Worlds" is saved as "The Legend of Zelda" as well. Be wary which save you restore to which game. Checkpoint is not affected due to different directory naming.
