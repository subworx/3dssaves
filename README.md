# 3DS Saves
My saved games for 3DS - unlocks, finished games, 100%.

For use with e.g. [JKSM](https://github.com/J-D-K/JKSM/releases):
- Download folder for the game you want (if region doesn't match, try anyway. Most should still work)
- Place folder into `sdcard:/JKSV/Saves/<Game Name>`
- If the table lists ExtData for a game, repeat with `sdcard:/JKSV/ExtData/<Game Name>`
 - Start JKSM and restore the save and, if applicable, ExtData.

Structure:
```
- Saves
  |- <TitleID>
  |  \- <Game Name as listed in JKSM>
  |     \- <Named directory containing save data>
```


# Saves

Game Name | TitleID | Region | ExtData | Status
----------|---------|--------|---------|-------
[Ace Attorney Trilogy](../main/Saves/0004000000138F00/Ace%20Attorney%20Trilogy/) (Phoenix Wright)|0004000000138F00|USA|No|100%
[Azure Striker Gunvolt](../main/Saves/000400000014C800/AZURE%20STRIKER%20GUNVOLT/)|000400000014C800|USA|No|Game beaten
[Azure Striker Gunvolt 2](../main/Saves/0004000000196A00/AZURE%20STRIKER%20GUNVOLT%202/)|0004000000196A00|USA|No|Game beaten
[Bravely Default](../main/Saves/00040000000FC500/BRAVELY%20DEFAULT/)|00040000000FC500|USA|No|0% with DLC costumes unlocked
[Legend of Zelda: A Link Between Worlds](../main/Saves/00040000000EC300/The%20Legend%20of%20Zelda/)|00040000000EC300|USA|No|Game beaten, [Note 1](#note1)
[Mario & Luigi: Bowser's Inside Story + Bowser Jr.�s Journey](../main/Saves/00040000001D1400/Mario%20&%20Luigi%20%20Bowser's%20Inside�/)|00040000001D1400|USA|No|Game Beaten, [Note 2](#note2)
[Mario & Luigi: Paper Jam](../main/Saves/0004000000132700/Mario%20&%20Luigi%20%20Paper�/)|0004000000132700|USA|No|Game beaten, [Note 2](#note2)
[Mario & Luigi: Superstar Saga + Bowser's Minions](../main/Saves/00040000001B8F00/Mario%20&%20Luigi%20%20Superstar�/)|00040000001B8F00|USA|No|Game beaten, [Note 2](#note2)
[Metroid: Saums Returns](../main/Saves/00040000001BB200/Metroid%20%20Samus%20Returns/)|00040000001BB200|USA|No|Game beaten, Fusion Mode unlocked. NO 100%
[Mighty Gunvolt](../main/Saves/000400000014CD00/MIGHTY%20GUNVOLT/)|000400000014CD00|USA|No|Game beaten
[Picross e](../main/Saves/00040000000A9200/Picross%20e/)|00040000000A9200|EUR|No|100%
[Picross e2](../main/Saves/00040000000CBC00/Picross%20e2/)|00040000000CBC00|EUR|No|100%
[Picross e3](../main/Saves/0004000000102900/Picross%20e3/)|0004000000102900|EUR|No|100%
[Picross e4](../main/Saves/0004000000128400/Picross%20e4/)|0004000000128400|EUR|No|100% including bonus levels
[Picross e5](../main/Saves/000400000014D200/Picross%20e5/)|000400000014D200|EUR|No|100% including bonus levels
[Prof. Layton vs Phoenix Wright](../main/Saves/0004000000100700/Prof%20%20Layton%20vs%20Phoenix%20Wrigh/)|0004000000100700|USA|[Yes](../main/ExtData/0004000000100700/Prof%20%20Layton%20vs%20Phoenix%20Wrigh/)|100% including bonus puzzles

 
## Notes
 <a name="note1"></a>Note 1: Folder name collision: JKSM stores "The Legend of Zelda<b>&trade;</b>" (Zelda I) as "The Legend of Zelda" to lose the symbol. "The Legend of Zelda: A Link Between Worlds" is saved as "The Legend of Zelda" as well. Be wary which TitleID you restore.
 
<a name="note2"></a>Note 2: Folders ending with `�` do NOT end with three dots, but actually with the character `�`. Use this when naming the folders or JKSM will NOT find the backup.