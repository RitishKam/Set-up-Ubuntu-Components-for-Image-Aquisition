# Set-up-Ubuntu-Components-for-Image-Acquisition

## Set up Ubuntu Components

### Flatpak Test Bundle Pre-release

1. **Ensure Flatpak support is installed:**

   - For Debian/Ubuntu GNOME:
     ```bash
     sudo apt install flatpak gnome-software-plugin-flatpak
     ```

   - For Debian/Ubuntu KDE Plasma:
     ```bash
     sudo apt install flatpak plasma-discover-backend-flatpak
     ```

2. **Restart Your Session or Computer**  
   - A restart may be required if Flatpak wasn't previously installed on your system.

3. **Download the Fiji Flatpak File**
   - Get the `Fiji.flatpak` file from the appropriate source.

4. **Install Fiji Flatpak Using GUI Tools**
   - Open the `.flatpak` file in GNOME Software (on GNOME) or KDE Discover (on Plasma) and proceed with the installation.

5. **Install Fiji Flatpak Using the Command Line (Alternative Method)**
   - For users without a GUI or preferring the terminal:
     ```bash
     flatpak install ./Fiji.flatpak
     ```
