# Webcraft - Web-Based Minecraft with Mobile Support

A web-based version of Minecraft with full mobile support, featuring touch controls optimized for smartphones and tablets. This project is built on [Eaglercraft](https://github.com/LAX1DUDE/eaglercraft), an implementation of Minecraft Java Edition 1.8 for the browser.

## 🎮 Features

### Core Gameplay
- **Full Minecraft Java 1.8 Experience** - Play classic Minecraft directly in your web browser
- **Multiplayer Support** - Connect to multiple public servers including:
  - AssPixel
  - Ayunboom
  - Aeon Network
  - VanillaCraft
  - CraftClue
  - Asian F4rmer
  - SealCraft
  - And more...

### Mobile Optimizations
- **Touch Controls** - Intuitive on-screen buttons designed for mobile gameplay
- **Responsive Design** - Adapts perfectly to any screen size and orientation
- **Mobile-Optimized UI** - Touch-friendly button layout with visual feedback
- **Compatibility Mode** - Includes keyboard compatibility settings for various mobile browsers
- **Landscape Orientation** - Optimized for landscape play on mobile devices

### Control Features
- **D-Pad Navigation** - Move forward, backward, left, right with directional buttons
- **Attack & Place Buttons** - Intuitive combat and building controls
- **Jump & Crouch Buttons** - With toggle options for ease of use
- **Sprint Toggle** - Quick sprint activation
- **Inventory & Chat** - Full access to inventory and chat systems
- **Pause & Settings** - In-game menu and customization options
- **Perspective Toggle** - Switch between first and third person views
- **Screenshot Button** - Capture your gameplay moments

## 📱 Supported Devices

- Smartphones (iOS and Android)
- Tablets (iPad, Android tablets, etc.)
- Desktop browsers (with touch support or via mouse)
- Any device with a modern web browser and JavaScript support

## 🚀 Getting Started

### Requirements
- Modern web browser (Chrome, Firefox, Safari, Edge)
- HTTP/HTTPS connection (local file access is not supported)
- Touch-enabled device or mouse input

### Running Locally

1. Clone or download this repository
2. Serve the files using an HTTP server:
   ```bash
   # Using Python 3
   python -m http.server 8000
   
   # Using Node.js
   npx http-server
   
   # Using PHP
   php -S localhost:8000
   ```
3. Open your browser to `http://localhost:8000`
4. Start playing!

### Online Version
Visit [minecraft-so-tuff.vercel.app](https://minecraft-so-tuff.vercel.app/) for a hosted online version.

## 🎯 Controls

### Touch Controls (Mobile)
- **Movement**: D-Pad buttons (up, down, left, right)
- **Attack**: Red punch button
- **Place/Interact**: Green place button
- **Jump**: Jump button
- **Crouch/Sneak**: Crouch button with lock toggle
- **Sprint**: Sprint button with toggle
- **Inventory**: Inventory button
- **Chat**: Chat button
- **Pause**: Pause button
- **Keyboard**: On-screen keyboard toggle
- **Compass**: Directional compass
- **Perspective**: Switch camera view
- **Screenshots**: Capture gameplay

### Keyboard Controls (Desktop)
- **W/A/S/D** - Move
- **Space** - Jump
- **Shift** - Crouch/Sneak
- **Ctrl** - Sprint
- **E** - Open Inventory
- **T** - Chat
- **ESC** - Menu/Pause
- **Mouse** - Look around / Attack / Place

## 📁 Project Structure

```
MinecraftSoTuff/
├── index.html                 # Main HTML file with Eaglercraft initialization
├── eaglermobile.user.js       # Mobile functionality and touch controls
├── eaglermobile-ef.js         # Additional mobile enhancements
├── manifest.json              # PWA manifest for installation
├── images/                    # Mobile UI button graphics
│   ├── attack.png
│   ├── jumpButton.png
│   ├── inventory.png
│   └── ... (50+ UI button images)
└── README.md                  # This file
```

## 🛠️ Technologies

- **Eaglercraft** - Minecraft Java 1.8 implementation for the browser
- **WebGL** - For 3D rendering
- **Touch API** - For mobile input handling
- **PWA (Progressive Web App)** - Installable on mobile devices

## 🔧 Configuration

The main configuration is in `index.html`. You can:
- Add or remove servers from the server list
- Change the container ID
- Modify asset and locale URLs
- Adjust display settings

## ⚙️ Mobile Script Features

The mobile enhancement scripts (`eaglermobile.user.js` and `eaglermobile-ef.js`) provide:
- Automatic mobile detection
- Touch event handling and gesture recognition
- Virtual joystick and button controls
- Keyboard compatibility mode
- Mobile crash fixes and optimizations
- Crouch and sprint lock toggles

## 📝 License

This project uses Eaglercraft and related components. Please refer to their respective licenses:
- Eaglercraft - Licensed under appropriate terms
- EaglerMobile enhancements - Apache License 2.0

## 🐛 Troubleshooting

### Game Won't Load
- Ensure you're accessing via HTTP/HTTPS, not file://
- Check that your browser supports WebGL
- Clear browser cache and try again

### Controls Not Responding
- Ensure touch is enabled on your device
- Try refreshing the page
- Check browser console for JavaScript errors

### Poor Performance
- Close other applications to free up memory
- Try lowering graphics settings in-game
- Disable background tabs

## 🤝 Contributing

This project builds on Eaglercraft. For improvements:
1. Test changes on multiple devices
2. Ensure mobile controls remain intuitive
3. Maintain compatibility with the underlying Eaglercraft version

## 📞 Support

For issues with:
- **Gameplay**: Check the Eaglercraft documentation
- **Mobile Controls**: Review the control mappings above
- **Server Connectivity**: Ensure the server is online

## 🎉 Have Fun!

Enjoy Minecraft anywhere, anytime on your mobile device! Build, explore, and survive with friends on multiplayer servers.

---

**Last Updated**: February 2026  
**Version**: 1.0
