# Installing the mods

## Install

1. Download the latest `CSUP-Mods-Test-*.zip` from [Releases](../../releases/latest) and unzip it anywhere (for example in Downloads).
2. Double-click **`Setup.bat`** and choose **Install / update the test**.
   Setup finds your Steam game, offers to make a **copy** of it, checks that the copy is the right game version, and asks before it changes anything. Your Steam installation is never modified.
   Windows may show *"Windows protected your PC"*: click *More info* → *Run anyway*.
3. Start the game with the **CSUP Mods Test** shortcut (or `Launch This Copy.bat` in the copy). **Steam must be running.**

The version number is shown at the bottom of the screen (*"CSUP test mod by Timmerzz - v0.1.5"*) and in the welcome panel. Mention it whenever you report something.

How to use each mod: see **[MODS.md](MODS.md)**.

## Updating

Download the new zip, run its `Setup.bat` and choose **Install / update the test** again.

## Reporting a bug

`Setup.bat` can also make a bug report for you: one zip on your desktop with your text, screenshots and, only if you tick it, your logs. Nothing is sent automatically. Post the zip in Discord `#csup-feedback` or attach it to a [bug report](../../issues/new?template=bug.yml).

## Troubleshooting

- **Antivirus warning about `winhttp.dll`:** this is the BepInEx mod loader, the file that loads the mods into the game. It is a known false positive, but you decide whether to trust it.
- **The game does not start:** make sure Steam is running and signed in.
- **Something else:** `Setup.bat` can open the log of your last race. Post it in `#csup-feedback`.

## Uninstall

Run `Setup.bat` and choose remove, or simply delete the copied game folder.
