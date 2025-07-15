---
layout: default
title: Body Blocks for Scratch 3.0
---

# Getting Started with Body Blocks

Body Blocks brings embodied interaction to Scratch programming through real-time pose detection. Move your body to control games and interactive projects!

## Download Body Blocks

Choose your platform below to download the latest version:

<div style="display: flex; flex-wrap: wrap; gap: 1rem; margin: 2rem 0;">
    <a href="https://github.com/stephenhowell/body-blocks/releases/latest" class="download-button">
        🪟 Windows
    </a>
    <a href="https://github.com/stephenhowell/body-blocks/releases/latest" class="download-button">
        💻 macOS - Intel and Applie Silicon builds available
    </a>
    <a href="#ios-interest" class="download-button" style="opacity: 0.6; cursor: not-allowed;">
        📱 iOS - Not currently available, let me know if you're interested!
    </a>
    <a href="https://github.com/stephenhowell/body-blocks/releases/latest" class="download-button">
        📱 Android APK
    </a>
</div>

<div class="warning">
<strong>⚠️ Important:</strong> Body Blocks apps are currently unsigned. You will see security warnings when first running the software. See platform-specific instructions below for how to proceed safely.
</div>

## Installation Instructions

<div class="step">

### Step 1: Install Body Blocks on Your Computer

#### Windows
1. Download the Windows installer from the link above
2. When you run the installer, Windows Defender may show a warning
3. Click "More info" then "Run anyway" to proceed
4. Follow the installation wizard

#### macOS
1. Download the appropriate version for your Mac (Intel or Apple Silicon)
2. Open the downloaded file
3. macOS will show a security warning because the app is unsigned
4. Go to System Preferences → Security & Privacy
5. Click "Open Anyway" next to the Body Blocks message
6. Drag Body Blocks to your Applications folder

</div>

<div class="step">

### Step 2: Install the Mobile App

#### Android
1. Download the APK file to your Android device
2. You may need to enable "Install from Unknown Sources" in your device settings
3. Open the APK file to install
4. Grant camera permissions when prompted

<div class="info">
<strong>Note:</strong> iOS may be possible (I don't have a Mac or a iOS device to test on), please let me know if you're interested!
</div>

<div class="step">

### Step 3: Network Setup

<div class="warning">
<strong>Important:</strong> Both your computer and phone must be on the same WiFi network!
</div>

#### Firewall Configuration
- **Windows:** When prompted, allow Body Blocks through Windows Firewall on port 8183
- **macOS:** If prompted, allow incoming connections for Body Blocks

</div>

## Running Body Blocks

<div class="step">

### Step 1: Start Body Blocks on Your Computer

1. Launch Body Blocks from your Applications/Start Menu
2. Body Blocks will display your computer's IP address (e.g., 192.168.1.100)
3. Note this IP address - you'll need it for the mobile app
4. In Body Blocks (computer), click "Start Posing"
5. A sample Scratch project will load automatically
6. Click the green flag to run the project

</div>

<div class="step">

### Step 2: Connect Your Phone

1. Open the Body Blocks app on your phone
2. Enter the IP address that was shown on your computer (first time only - the app remembers it)
3. Tap "Connect"
4. The connection indicator should turn <span style="color: #03884a; font-weight: bold;">green</span> when connected

</div>

<div class="step">

### Step 3: Connect Your Phone

1. Stand in front of your (front) phone camera and start moving!
1. The phone will show a outline on your body when a person is detected.
1. While app is connected, Body Blocks (in block palette) will report the x, y position of body points on the Scratch stage.

</div>

<div class="success">
✨ You're now ready to create interactive projects with Body Blocks!
</div>

</div>

## Troubleshooting

### Connection Issues
- Ensure both devices are on the same WiFi network
- If phone cannot join the same network, consider using a hotspot from phone
- Check that port 8183 is not blocked by your firewall

### Camera Not Working
- Ensure you've granted camera permissions to the mobile app
- Check that no other app is using the camera
- Try restarting the mobile app

### Performance Issues
- Ensure good lighting for optimal pose detection
- Stay 1-3 meters from the camera
- Close other applications to free up resources
- Older phones and phones without GPUs may struggle, sorry.

## Next Steps

- Explore the [sample tutorials]({{ '/tutorials' | relative_url }}) to see what's possible
- Learn how to [cite Body Blocks]({{ '/research' | relative_url }}) in your research
- Join our community of educators and creators!

## Platform Availability

<div id="ios-interest" class="info">
<strong>🍎 iOS Developers:</strong> If you're interested in Body Blocks but you only have access to iPhone and iPad, please <a href="mailto:stephenhowell@outlook.ie?subject=Body%20Blocks%20for%20iOS">get in touch</a>!
</div>

---

<div style="text-align: center; margin-top: 3rem;">
    <p><em>Body Blocks: Making movement meaningful in computational thinking</em></p>
</div>