---
layout: default
title: Body Blocks for Scratch 3.0
---

<div class="step" markdown="1">
Body Blocks brings embodied interaction to Scratch programming through real-time pose detection with an Android phone (or a Kinect v2 sensor).  
Body Blocks works best with a laptop (Windows or Mac) and an Android Phone.  

Once you have installed and set up both the phone app and the desktop app, posing in front of your phone will send the positions of your head, hands etc. into Scratch. 

Move your body to control games and interactive projects!
</div>

# Set Up

## Download Body Blocks

<div class="info" markdown="1">
**❗Note**: You need **both** apps - Body Blocks for your laptop, *and* Body Blocks for your Android phone/tablet.
</div>

Choose your laptop platform below to download the latest version:
<div style="display: flex; flex-wrap: wrap; gap: 1rem; margin: 2rem 0;">
    <a href="https://github.com/stephenhowell/body-blocks/releases/latest" class="download-button">🪟 Windows</a>
    <a href="https://github.com/stephenhowell/body-blocks/releases/latest" class="download-button">🍎 Mac</a>
</div>

Choose your phone platform below to download the latest version:

<div style="display: flex; flex-wrap: wrap; gap: 1rem; margin: 2rem 0;">        
    <a href="https://github.com/stephenhowell/body-blocks/releases/latest" class="download-button">📱 Android APK</a>
    <a href="#ios-interest" class="download-button" style="opacity: 0.6; cursor: not-allowed;">📱 iOS - Sorry, not currently available</a>
</div>

<div class="warning" markdown="1">
**⚠️ Important:** Body Blocks apps are currently **unsigned**. This means you will see security warnings when first running the software. See platform-specific instructions below for how to proceed safely.
</div>

## Installation Instructions

<div class="step" markdown="1">

### Step 1: Install Body Blocks on Your Computer

#### Windows
1.  Download the Windows installer from the link above.
2.  When you run the installer, Windows Defender may show a warning.
3.  Click "More info" then "Run anyway" to proceed.
4.  Follow the installation wizard.

#### macOS
1.  Download the appropriate version for your Mac (Intel or Apple Silicon).
2.  Open the downloaded file.
3.  macOS will show a security warning because the app is unsigned.
4.  Go to **System Preferences → Security & Privacy**.
5.  Click "Open Anyway" next to the Body Blocks message.
6.  Drag Body Blocks to your Applications folder.

</div>

<div class="step" markdown="1">

### Step 2: Install the Mobile App

#### Android
1.  Download the APK file to your Android device.
2.  You may need to enable "Install from Unknown Sources" in your device settings.
3.  Open the APK file to install.
4.  Grant camera permissions when prompted.

<div class="info" markdown="1">
**Note:** iOS may be possible (I don't have a Mac or a iOS device to test on), please let me know if you're interested!
</div>
</div>

<div class="step" markdown="1">

### Step 3: Network Setup

<div class="warning" markdown="1">
**Important:** Both your computer and phone must be on the same WiFi network!
</div>

#### Firewall Configuration
- **Windows:** When prompted, allow Body Blocks through Windows Firewall on port 8183.
- **macOS:** If prompted, allow incoming connections for Body Blocks.

</div>

<div class="success" markdown="1">
**🔐 Note:** Body Blocks phone app sends data to the local (same wifi) Body Blocks laptop app only. It does not record video or images or send any telemetry to the cloud or anywhere else. The camera feed is processed on your phone using a machine learning (ML) model and 33 *landmarks* or body positions are sent as a list of numbers representing the x and y axes positions. This appears as a stream of numbers and contains no identifying information or images. 
</div>

## Running Body Blocks

<div class="step" markdown="1">

### Step 1: Start Body Blocks on Your Computer

1.  Launch Body Blocks from your Applications/Start Menu.
2.  Body Blocks will display your computer's IP address (e.g., `192.168.1.100`).
3.  Note this IP address - you'll need it for the mobile app.
4.  In Body Blocks (computer), click "Start Posing with Scratch!".
5.  A sample Scratch project will load automatically with the Body Blocks extension enabled.
6.  Click the green flag to run the project.

</div>

<div class="step" markdown="1">

### Step 2: Connect Your Phone

1.  Open the Body Blocks app on your phone.
2.  Enter the IP address that was shown on your computer (you only have to do this the first time - the app remembers it after that).
3.  Tap "Connect".
4.  The connection indicator should turn <span style="color: #03884a; font-weight: bold;">green</span> when connected.

</div>

<div class="step" markdown="1">

### Step 3: Start Posing!

1.  Stand in front of your (front) phone camera and start moving!
2.  I recommend you place the phone in a holder on a small tripod, so you can position it easily.
3.  The phone will show an outline on your body when a person is detected.
4.  While the app is connected, Body Blocks (in the block palette) will report the x, y position of body points on the Scratch stage.

</div>

<div class="success" markdown="1">
✨ You're now ready to create interactive projects with Body Blocks! Have fun learning! ✨
</div>

## Troubleshooting

<div class="step" markdown="1">
    
### Connection Issues?
- Ensure both devices are on the same WiFi network.
- If the phone cannot join the same network, consider using a hotspot from the phone.
- Check that port 8183 is not blocked by your firewall.

### Camera Not Working?
- Ensure you've granted camera permissions to the mobile app.
- Check that no other app is using the camera.
- Try restarting the mobile app.

### Performance Issues
- Ensure good lighting for optimal pose detection.
- Stay 1-3 meters from the camera or as far as you need for it to see all of you.
- Close other applications to on phone free up resources.
- Older phones and phones without GPUs may struggle, sorry.

</div>

## Next Steps

- Explore the [sample tutorials]({{ '/tutorials' | relative_url }}) to see what's possible.
- Learn how to [cite Body Blocks]({{ '/research' | relative_url }}) in your research.
- Send me feedback, or any questions to <a href="mailto:stephenhowell@outlook.ie">stephenhowell@outlook.ie</a>.

## Platform Availability

<div id="ios-interest" class="info" markdown="1">
**🍎 iOS Users:** If you're interested in Body Blocks but you only have access to an iPhone or iPad, please <a href="mailto:stephenhowell@outlook.ie?subject=Body%20Blocks%20for%20iOS">get in touch</a>!
</div>

---

<div style="text-align: center; margin-top: 3rem;">
    <p><em>Body Blocks: Making movement meaningful in computational thinking</em></p>
</div>
