🚗 Vehicle Underglow Toggle for FiveM
A lightweight and standalone script that lets players easily toggle their vehicle’s underglow lights using a configurable keybind. Works with any vehicle that supports underglow/neon lights.

🔧 Features
Toggle underglow lights on/off with a single keypress.

Easily configurable keybinding.

Supports both client- and server-side installation.

Works with all standard GTA V vehicles that support neon lights.

🧩 Requirements
A working FiveM server.

Vehicles with underglow (neon lights) installed and supported.

Basic understanding of where to install client-side scripts.

⌨️ Default Keybind
Default Toggle Key: J
You can change this in the client.lua or configure it with a keybinding resource of your choice.

📁 Installation
Download the Script
Clone or download the repository:
git clone https://github.com/highgamer420/-Release-Vehicle-Underglow-Toggle-for-FiveM.git

Place the Script
Put the folder in your server’s resources directory and rename it (recommended):
Example:
resources/[local]/vehicle_underglow

Add to Server Config
Add this line to your server.cfg:
ensure vehicle_underglow

Restart Your Server
Restart the server or use refresh and start vehicle_underglow in your console.

 Configuration
To change the key, open client.lua and modify the IsControlJustReleased line.
Example:
IsControlJustReleased(0, 74) -- 74 is the default key 'J'

💡 How It Works
When the configured key is pressed:

If the vehicle has neon lights installed, the script toggles them on or off.
Only works when the player is inside a vehicle.

join the discord https://discord.gg/sNANv4dJad
