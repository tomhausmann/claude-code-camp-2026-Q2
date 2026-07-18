# World Map & NPCs

## City Layout (Midgaard — two districts)
The city has two connected districts:
1. **Classic center** (Temple / Market Square) — reached automatically on login/reconnect (Temple of Midgaard is the start room).
2. **Park district** (Promenade / Emerald Ave / Park) — the area northwest, ringed by the Concourse.

## Classic Center
- **The Temple Of Midgaard**: Start/reconnect room. Exits n e s w d. Has ATM. Reading Room west, donation room east, `down` → Temple Square.
- **The Temple Square**: Marble fountain (FREE water — `drink fountain`). Clerics' Guild west, Grunting Boar Inn east, Market Square south.
- **Market Square**: Center of Midgaard. Temple square north, common square south (unexplored), Main Street east/west.
- **Main Street (1 west of Market Square)**: **THE BAKERY is NORTH** of here; Armory is south (unexplored). Cityguards patrol.
- **The Bakery** ⭐: Baker sells (use `list`/`buy`):
  - A danish pastry — 7 gold
  - A bread — 14 gold
  - A waybread — 74 gold
- Unexplored: common square (s of Market), Main Street further e/w, Armory, Inn, Clerics' Guild, Reading Room.

## Park District
- **The Promenade** (3 rooms, river north): west room → Park Road south; middle room → The Park Entrance south (small building west = Cityguard HQ); east room → path south to Emerald/Penny junction, levee visible across river.
- **Emerald Avenue**: Runs promenade → junction (Penny Lane east) → "north end" room (park east entrance west, **Town Hall** east) → bends → Road Crossing → continues south → The Concourse.
- **Town Hall**: Waiting Room (secretary, 2 guards — no dialogue) + Mayor's Office. Nothing else.
- **Penny Lane**: e then n, DEAD END at fountain (drinkable). Gold pile found there (37 coins, taken 2026-07-18).
- **Park Road**: Runs promenade(west room) south past **Cityguard HQ** (locked door, west side) → Western Park Entrance east → bend → Road Crossing. East segment: Road Crossing → bend → south, **Elm Street** east (dead ends at old elm tree) → Concourse.
- **The Road Crossing**: Sign: N/S = Emerald Ave, E/W = Park Road, `up` chain → Redferne's Flying Citadel.
- **The Park**: 3 entrances (north w/ cafe, eastern → Emerald north end, western → Park Road). Paths connect them around **The Pond** (swim in; `drink` works while in pond — free water). Ducks, swans, sparrow.
- **Park Cafe** (east of north Park Entrance): Maid sells: water 2, coffee 8, tea 5. NO food. Sexton + gelatinous blob inside. Maid doesn't respond to `ask`.
- **The Concourse**: Ring road around park district along city wall. NE end ↔ Promenade east; NW end ↔ Promenade west, bridge north (unexplored, leads across river toward levee/warehouse). Graveyard behind iron grate (south, mid-east Concourse). SW corner has an unexplored west exit (city gate?).

## Key Mechanics Learned
- `where <mob name>` finds mobs in the CURRENT zone only (e.g. `where baker` worked from Market Square, not from park district).
- Hunger/thirst massively slow HP/mana/move regen — keep fed (bakery) and watered (fountains are free).
- Link-drop/reconnect returns character to Temple of Midgaard with restored movement.
- Read road/shop signs (`read sign`) — shops respond to `list` and `buy <item>`.
