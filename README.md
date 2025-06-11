---
# ReShade for Winlator

## V2 - Winlator ReShade Installer ✨

The latest and greatest! This version simplifies the patching process significantly.

### How to Use:

1.  **Download the `.exe`**: Grab the installer from the [releases page](https://github.com/mxxme-dev/Winlator-ReShade-patch/releases/download/v2.0.0/Install.Reshade.exe).
2.  **Run the Installer**: 
3.  **Choose Game Folder**: The installer will prompt you to select the folder where your game is located.
4.  **Input API**: You'll then be asked to specify the API your game uses. Supports DX9/10/11/12 and Opengl32/64 also Vulkan.

That's it! This version handles the rest for you.

---

## V1 - Winlator ReShade Installer // Injector Method 🛠️

For those who prefer a more hands-on approach or for reference, here's how the original V1 worked.

### How to Use:  
1.  **Download the `.7z`**: Grab the Archive from the [releases page](https://github.com/mxxme-dev/Winlator-ReShade-patch/releases/download/reshade-winlator-patches/ReShade.Winlator-Mxxme.Jhinzuo.7z) .
2.  **Edit `cfg_game.txt`**: Open the `cfg_game.txt` file using Notepad inside the Container.
    **Do not change it with any other Text-Editor !**
4.  **Configure Game Entry**: The file's content should follow this format:
    ```bash
    game.exe;64/32
    ```
    * Replace `game.exe` with the actual executable name of your game.
    * Specify `64` or `32` depending on whether your game is 64-bit or 32-bit.

    **Example:**
    ```bash
    BALDI.exe;64
    ```

---

### Credits:
* **Created by @jhinzuo and @mxxme-dev**
* [**ReShade**](https://reshade.me/)

