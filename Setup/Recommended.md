# Recommended Setup Steps

These are my recommended steps for setting up a Steam Deck. You do not need to follow every recommendation, but this is how I set up a Deck.

## Game Mode

- Steam Menu settings
  - enable Developer Mode
  - enable Bluetooth

## Desktop Mode

- Install from Discover
  - AnyDesk (remote desktop software - do typing-heavy tasks remotely from your PC)
  - Discord (video and text chat)
  - Discover Overlay (graphical overlay for Discord)
  - Flatseal (configure Flatpak app permissions)
  - Heroic Game Launcher (install GOG, Epic Store, etc games)
  - Lutris (game manager/installer)
  - Microsoft Edge (Xbox cloud gaming)
  - ProtonUp-Qt (install other Steam Play compatibility tools, eg. Luxtorpeda, Boxtron, GE-Proton)
  - Space Cadet Pinball (port of 3D Pinball from Windows 95)
  - Syncthing GTK (easy file transfer between PC and Deck)

- Open Konsole (command line)
  - Set sudo password for "deck" account (Konsole)
    - `passwd`
    - enter desired password
  - Install AppImageLauncher
    - [instructions](https://www.reddit.com/r/SteamDeck/comments/t9xwte/how_to_automatically_integrate_appimage_apps_into/
    - adds AppImage apps into SteamOS environment)
  - Install Lutris dependencies (Konsole)
    - `flatpak install flathub org.gnome.Platform.Compat.i386 org.freedesktop.Platform.GL32.default org.freedesktop.Platform.GL.default`
    - when prompted, choose the latest (highest version number) version of each
    - ref: https://www.gamingonlinux.com/2022/04/lutris-now-has-a-flatpak-beta-available-and-updated-for-the-steam-deck/

## Emulation

My preferred emulation setup is RetroArch for PSX/N64 era and earlier, and standalone emulators for PS2 and newer.

I *strongly* prefer the Steam version of RetroArch for one reason: cloud saves. Being able to seamlessly take your savegames and save states from desktop to Deck and back is a "killer app" level feature IMO.

The Steam version does have some downsides - namely, a limited number of cores compared to a standalone install, and the lack of the Online Updater feature to add new cores. However, we can manually add cores very easily to the Steam install, mitigating that limitation. In my view, cloud saves are a big enough deal to make the trade-off worth it.

For the rest of the emulators, I recommend running the EmuDeck script to install them.

- RetroArch
  - Install from Steam library 
  - Configure hotkeys to match [EmuDeck's hotkeys](https://github.com/dragoonDorise/EmuDeck)

- EmuDeck
  - [Download installer from emudeck.com](https://www.emudeck.com/)

## Cloud Gaming

- Xbox Cloud Gaming
  - [Microsoft's instructions](https://support.microsoft.com/en-gb/topic/xbox-cloud-gaming-in-microsoft-edge-with-steam-deck-43dd011b-0ce8-4810-8302-965be6d53296)
