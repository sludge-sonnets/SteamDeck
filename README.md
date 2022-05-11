# First Steps After Initial Login

## Game Mode

- Steam Menu settings
  - enable Developer Mode
  - enable Bluetooth

- RetroArch
  - Install from Steam library 
    - the Steam version's killer feature is cloud saves, allowing you to take the same savegames/states back and forth between desktop PC and Deck.
  - Configure hotkeys to match [EmuDeck's hotkeys](https://github.com/dragoonDorise/EmuDeck)

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
  
- EmuDeck
  - [Download installer from emudeck.com](https://www.emudeck.com/)

- Set sudo password for "deck" account (Konsole)
  - `passwd`
  - enter desired password

- Install from command line (Konsole)
  - AppImageLauncher ([instructions](https://www.reddit.com/r/SteamDeck/comments/t9xwte/how_to_automatically_integrate_appimage_apps_into/) - adds AppImage apps into SteamOS environment)
  
- Install Lutris dependencies (Konsole)
  - `flatpak install flathub org.gnome.Platform.Compat.i386 org.freedesktop.Platform.GL32.default org.freedesktop.Platform.GL.default`
  - when prompted, choose the latest (highest version number) version of each
  - ref: https://www.gamingonlinux.com/2022/04/lutris-now-has-a-flatpak-beta-available-and-updated-for-the-steam-deck/

- Xbox Cloud Gaming
  - [Microsoft's instructions](https://support.microsoft.com/en-gb/topic/xbox-cloud-gaming-in-microsoft-edge-with-steam-deck-43dd011b-0ce8-4810-8302-965be6d53296)

## Other Resources

- [mikeroyal/Steam-Deck-Guide](https://github.com/mikeroyal/Steam-Deck-Guide)
  - some good info but also a lot of fluff
  - some recommendations are questionable and clearly untested in a Deck environment
- [popsulfr/steam-deck-tricks](https://gitlab.com/popsulfr/steam-deck-tricks)
  - more hardcore, technical tricks
- Fan noise comparison
  - all Decks have fairly loud airflow whooshing when fan is at/near max, but some Decks have a mechanical whine on top of that
  - [example of a "good" fan](https://www.youtube.com/watch?v=UEY_FsvwBlo) (turn up volume to hear)
  - [example of a "bad" fan with whine](https://www.youtube.com/watch?v=s51a2kQJH0Y)
  - some people have "fixed" the whiny fan [with additional electrical tape](https://www.theverge.com/23047412/valve-steam-deck-fan-tape-fix-noise-whine) to apply pressure to the fan casing. Not recommended for people inexperienced with taking apart electronic devices.
