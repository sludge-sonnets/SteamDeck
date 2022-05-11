# First Steps After Initial Login

## Game Mode

- Steam Menu settings
  - enable Developer Mode
  - enable Bluetooth

- Install RetroArch
  - the Steam version of RetroArch supports cloud saves, which is a killer feature that you don't get from the standalone install.

## Desktop Mode

- Install from Discover
  - AnyDesk (remote desktop software - do typing-heavy tasks remotely from your PC)
  - Discord (video and text chat)
  - Discover Overlay (graphical overlay for Discord)
  - Flatseal (configure Flatpak app permissions)
  - Lutris (game manager/installer)
  - Heroic Game Launcher (install GOG, Epic Store, etc games)
  - ProtonUp-Qt (install other Steam Play compatibility tools, eg. Luxtorpeda, Boxtron, GE-Proton)
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
