# Illuminat3's CS2 AutoExec

This is the autoexec im currently using in cs2.  
[Steam Profile](https://steamcommunity.com/profiles/76561199504498601)

---

## Table of Contents

1. [Autoexec Breakdown](#breakdown)
2. [Installation Steps](#installation-steps)
3. [Verification](#verification)
4. [Troubleshooting](#troubleshooting)
5. [Prerequisites](#prerequisites)

---

## Breakdown

### Autoexec.cfg

This is used to call all the different exec files and will clear the console after execution.  

### Audio.cfg

This is used for all the audio settings.  
There are comments breaking it down into each section.

### Bind.cfg

This is used to handle binding all the keys along with a couple of keyboard optimizations

### Crosshair.cfg

This handles the crosshair and the custom nade crosshair setup.  
I use Austincs_'s crosshair.

### Hud.cfg

This handles everything you can see in game.  
This is broken down with comments.  

### Mouse.cfg

This handles mouse sensitivities.  
Do not change `m_pitch` and `m_yaw` unless you know what you're doing.

### Network.cfg

This handles networking, the new damage prediction and the lobby settings.  

### Script.cfg

This handles all the custom alias commands I use.  
Note that for the welcome command, you can change this to be any music kit you want.
You can find a list of sounds [here](https://github.com/schalkburger/cs2-sounds/blob/main/sounds.txt).  
All music kits are in the `sounds/music/` directory.  

### Video.cfg

This handles all the video settings that are currently available in the cs2 console.  
If your game crashes after using the config trying increasing the `engine_no_focus_sleep` value.  
There are also comments with all of the recommended video settings.  

---

## Prerequisites

- **[Counter-Strike 2](https://store.steampowered.com/app/730/CounterStrike_2/)** - duh

---

## Installation Steps

### 1. Clone the Repository
First, clone the repository to your local machine:

```bash
git clone https://github.com/illuminat3/autoexec.git
```

Alternatively, you can download the repository as a ZIP file:
1. Navigate to the repository URL: [illuminat3/autoexec](https://github.com/illuminat3/autoexec).
2. Click on the **Code** button.
3. Select **Download ZIP** and extract it to a location of your choice.

---

### 2. Locate the CS2 Configuration Folder
1. Open **File Explorer** and navigate to the CS2 installation directory.
2. The configuration folder is typically located at:
   - **Windows**: `C:\Program Files (x86)\Steam\steamapps\common\Counter-Strike Global Offensive\game\csgo\cfg`
   - **Linux**: `~/.steam/steam/steamapps/common/Counter-Strike Global Offensive/game/csgo/cfg`

---

### 3. Copy the Autoexec File
1. From the cloned repository, locate the `cfg` folder.
2. Copy the contents of this folder into the `cfg` folder you located earlier.

---

### 4. Enable Autoexec Execution
1. Launch Steam and go to your Library.
2. Right-click **Counter-Strike 2** and select **Properties**.
3. Under the **General** tab, locate the **Launch Options** field.
4. Add the following command:
   ```
   +exec autoexec.cfg
   ```

---

## Verification
1. Launch CS2 and open the console by pressing `'`
2. Type `exec autoexec` and press Enter. If no errors appear, the autoexec is loaded successfully.

---

## Troubleshooting
- **Autoexec Not Loading**: Ensure the file is named `autoexec.cfg` and is placed in the correct `cfg` folder.
- **Launch Options Missing**: Double-check the launch options in Steam and verify the `+exec autoexec.cfg` command is present.
- **Console Not Working**: Enable the developer console in the game's settings menu.

For further assistance, [open an issue](https://github.com/illuminat3/autoexec/issues).
