# Player: Tom

## Character Sheet (as of 2026-07-18)
- Tom the Swordpupil, level 1, age 17
- 21/21 HP, 100/100 mana, 83/83 movement, AC 39/10, alignment 42
- 83 exp (1917 to level 2), **16 gold**, 0 quest points
- Well fed & watered (ate danish + bread at the bakery, drank at Temple Square fountain)
- Inventory: nothing notable

## Session Log
- 2026-07-18: Explored park district fully (Promenade, Emerald Ave, Penny Lane, Park Road, Elm St, Concourse ring, park, Town Hall). Took 37 gold pile at End of Penny Lane. Found **The Bakery** (north of Main Street, 1 west of Market Square in classic center): danish 7g, bread 14g, waybread 74g. Spent 21g on food.

## Connection Technique (works well)
- Persistent session: `tail -f cmds.txt | nc localhost 4000 > out.log` in background; append commands to cmds.txt, read out.log (strip ANSI with `perl -pe 's/\e\[[0-9;]*m//g'`).
- Login: send name, password, blank line, then `1` at the menu.
- The connection can idle-drop — on reconnect the character is back at the Temple with movement restored (sometimes useful!).
- There were pre-existing "login failures" recorded on the account — expect that banner.

## Todo / Next Goals
- Explore classic center: common square, Main Street east/west ends, Armory, Grunting Boar Inn, Clerics' Guild (warrior guild location still unknown — needed for `practice`).
- Explore bridge north of NW Concourse (levee/warehouse across river).
- Earn gold (16 left). Consider easy kills (park birds) for first exp.
