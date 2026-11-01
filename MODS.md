# The mods, one by one

What each mod does and how to use it. Version **v0.1.3**.

## Where to find the settings

Most mods are switched on per race in **Free Play**:

1. Start a Free Play race and open the race setup.
2. The top row, **Settings page: Game / Mods**, switches between the normal settings and the **Mods** page.
3. On the Mods page every mod has an **Off / On** switch and starts **Off**. Switch it On and its settings unfold below it.

**Settings → Mods** in the main menu shows an overview of every mod in the pack.

**Time Trial:** only **Race Data** and **Ghosts** work there (plus Car Unlock and TT Board, which change nothing about driving). Every other mod switches itself off, so a Time Trial lap is a stock lap and counts on the official leaderboard as normal.

---

## Race setup (Free Play → Mods page)

### Weather
Dry, light rain, heavy rain, or **Changing** (showers come and go during the race). A wet track has less grip, and the right tyre matters.

**Choosing your tyres**
- Press **T** (or **B** on an Xbox pad) to pick the tyres for your **next pit stop**. Each press moves to the next compound; a big coloured tyre in the middle of the screen shows what you picked.
- Dry: **Soft** (fastest, wears quickly) → **Medium** → **Hard** (slowest, lasts longest).
- With weather on, **Intermediate** (green, damp to wet) and **Wet** (blue, heavy rain) are added to the cycle.
- The tyres are changed when you **drive into the pits**. You can still change your mind while you are in the pit lane.
- A race that starts in the rain starts everyone on suitable tyres. After that, reading the weather is up to you: the AI pits for the right tyres too.
- The HUD tyre gauge shows what you have on: white slicks, green inters, blue wets.
- You can change the key under **Settings → Controls → Change tyres**.

### Time of Day
Day, dusk, night (with headlights), or a changing day that goes from day to night during the race.

### Track Surface
Turns a circuit's tarmac into dirt.

### Fuel Effect (row "Fuel load effect")
A full tank makes the car slower; it gets faster as the fuel burns off.

- **Only works when the race's Fuel use is above zero** (normal race settings). Without fuel use there is nothing to burn and the effect is invisible.
- **Choose your starting fuel:** on the grid you get about **8 seconds** before the countdown. Press **F** to step through **100 % → 75 % → 50 % → 25 %**. The screen shows `START FUEL` and the amount.
- **During the race** **F** sets how much fuel the crew puts in at your **next pit stop** (`NEXT FILL`). Less fuel means a shorter stop and a lighter car, but you may need to stop again.
- Testers can change how strong the effect is in `BepInEx\config\csup.raceoptions.cfg`, section `[Fuel]`. See `instructions.txt` in the download. Please mention the values you used when you report on fuel.

### AI Manners
How much room the AI gives you: from **1 Aggressive** to **5 Very friendly**.

### Blue Flags
Lapped cars get the blue flag and make room for the leaders.

### Bumpy Dirt
Real bumps on dirt, gravel and mud. Choose **Off** or a strength from **1 to 7**. Tarmac and kerbs stay smooth.

### Winter (experimental)
Row **Winter: Off / Snow**. Any circuit becomes a snow track: snow, frost, falling snow and low grip. Leave Track Surface on Stock for a winter race.

### Power Boost
A battery that fills as you drive (most under braking) and gives about **3 seconds of extra power**.
- Hold **Left Shift** (or **RB** on a pad) to use it.
- Row options: **Off / On / On + AI** (with On + AI the AI cars use it too).
- The blue bar with a lightning bolt next to the tyre and fuel gauges shows the charge.
- Extra rows set the recharge speed, boost power and battery size.

### Joker Lap
Rallycross rules. Two rows, each **Off / 1 / 2 / 3**:
- **Joker laps:** you race the short layout and must drive the long layout's extra loop that many times, on any laps you choose. Works on tracks with a short and a long layout (for example Magdalena Club, Tilksport Club, Copperwood Club, Lost Lagoons Club).
- **Joker drive-through:** you must drive through the pit lane that many times. **Don't stop in your box**, or it doesn't count. Works on almost every track.

When to take your joker is your choice: early and you drop into traffic, late and you risk getting stuck.

### Big Grid
Up to **24 cars** on the Free Play grid. Above 12 cars, cars share pit boxes.

### Race End
The chequered flag waits until the whole field has finished, and the results table scrolls so you can see everyone.

---

## Tracks

### Track Layouts
A new layout: **Lost Lagoons Club**. Pick it like any other layout in Free Play or Practice.

### Track Reverse
Reverse routes for **Faenza (Rivazza)**, **Magdalena** and **Lost Lagoons**. They appear next to the normal routes as *Reverse* in Free Play and Practice.

---

## Time Trial and practice

### Race Data
Sector times and the route's world record on the HUD, with the gap to your best lap. Press **F4** to hide or show it.

### Ghosts
Race up to **five ghosts** of other drivers in Time Trial and Practice. Press **F8** on the Time Trial screen to choose them.

### TT Board
A bigger Time Trial leaderboard: 100+ places, scrolling, points and world rank.
- **F6** sorts by points.
- **F7** builds a points ranking across boards.

---

## Always on

### Car Unlock
Every car and livery available, without having to unlock them first.

### Minimap
Driver initials and livery colours on the minimap.

### Stig Challenge Access
Opens the **Top Gear Stig Challenge**, which is no longer on sale, with OFG's agreement. If you don't own it, your Top Gear Time Trial times are not submitted.

### Mod Menu
**Settings → Mods**: an overview of the mods in this pack, plus the panel on the main menu. It only lets Time Trial times through while every mod is Time Trial safe.

### Offline Boot
Lets the modded copy start next to your normal Steam game. Nothing to do or test.
