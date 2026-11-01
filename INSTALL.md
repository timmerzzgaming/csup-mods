# Installing the mods

## 1. Make a copy of the game

1. In Steam: right-click **Circuit Superstars** → *Manage* → *Browse local files*.
2. Copy the whole folder to a new place, for example `C:\Games\Circuit Superstars Modded`.
   Your Steam version stays untouched.

## 2. Install the pack

1. Download the latest `CSUP-Mods-*.zip` from [Releases](../../releases/latest).
2. Unzip it **into the copied game folder** (the folder that contains `circuit-superstars.exe`).
3. Double-click `Install.bat`.
   Windows may show *"Windows protected your PC"*: click *More info* → *Run anyway*.

## 3. Play

1. Make sure Steam is running.
2. Start `circuit-superstars.exe` in the **copied** folder.
3. The welcome panel in the main menu shows your **version number** (for example v0.1.3). Mention it whenever you report something.

## Troubleshooting

- **Nothing modded shows up:** check that the zip was unpacked in the right folder, not one level too deep.
- **Antivirus warning about `winhttp.dll`:** this is the BepInEx loader and is a known false positive.
- **Crash or error:** send `BepInEx\LogOutput.log` from the copied folder via Discord `#csup-feedback` or a [bug report](../../issues/new?template=bug.yml).

## Uninstall

Delete the copied folder. Nothing else was changed.
