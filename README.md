# LMU-Race-Engineer

## Overview
**LMU Race Engineer** gives you a virtual race engineer for **Le Mans Ultimate**.

Stay focused on the track while the app watches the session for you, showing the information that matters, calling out key stragegy, and helping you react faster when the race changes.

From chasing the car ahead to defending from pressure behind, LMU Race Engineer helps you drive with more awareness, better timing, and less distraction.


## Main Features

### Race Dashboard

See the key race information at a glance, including position, gaps, fuel, tyres, car settings, and nearby cars.

<img width="1920" height="1079" alt="image" src="https://github.com/user-attachments/assets/d8d2c710-7803-49f0-b523-a91f5bb1fa27" />

### Messages and Voice Calls

Receive simple on-screen messages and voice calls when something important happens, including attack opportunities, defence pressure, ahead and behind pace, track limits, and tyre wear updates.

<img width="1920" height="1079" alt="image" src="https://github.com/user-attachments/assets/dc12f75e-7b6a-410a-a517-5492a035ecaa" /><br>

<img width="1920" height="1079" alt="image" src="https://github.com/user-attachments/assets/dd495a60-683f-48d6-99e4-51872677df84" /><br>

<img width="1920" height="1079" alt="image" src="https://github.com/user-attachments/assets/4eb7425c-e418-4e93-95e6-c31b3beb484d" /><br>

<img width="1920" height="1079" alt="image" src="https://github.com/user-attachments/assets/8e4e5799-9564-407e-bc16-7b1ee6aca235" /><br>

<img width="1920" height="1079" alt="image" src="https://github.com/user-attachments/assets/733e265d-fbda-4729-9701-3d998df8eb7a" /><br>

<img width="1920" height="1079" alt="image" src="https://github.com/user-attachments/assets/18bf7f45-55c9-46fc-95a2-58cb122002da" /><br>




### Attack and Defend Mode

Get support when chasing the car ahead or defending from the car behind, using dashboard updates, on-screen messages, and voice calls.
<img width="1920" height="1079" alt="image" src="https://github.com/user-attachments/assets/6e2a34ce-5485-4c92-843a-ad1a94eaf935" />

<img width="1920" height="1079" alt="image" src="https://github.com/user-attachments/assets/6f793de2-e804-48a6-9abf-da2a78663e73" />

### Qualifying Dashboard

Focus on lap time with live pace, sector deltas, best lap, position, gap to pole, and session time remaining.
<img width="1920" height="1079" alt="image" src="https://github.com/user-attachments/assets/bde062f9-a0f5-4502-971e-274eb596fb91" />

Thought for a few seconds


## Setup

### Game Setup

In **Le Mans Ultimate**, make sure plugins are allowed/enabled.

Download the LMU-Race-Engineer.zip, unzip it.

Put this plugin file:

```txt
rFactor2SharedMemoryMapPlugin64.dll
```

inside:

```txt
Le Mans Ultimate\Plugins
```

If the `Plugins` folder does not exist, create it.

### Enable the Plugin

Open this file:

```txt
Le Mans Ultimate\UserData\Player\CustomPluginVariables.JSON
```

If the folder or file does not exist, create it.

Add this entry:

```json
"rFactor2SharedMemoryMapPlugin64.dll": {
  " Enabled": 0,
  "DebugISIInternals": 0,
  "DebugOutputLevel": 0,
  "DebugOutputSource": 1,
  "DedicatedServerMapGlobally": 0,
  "EnableDirectMemoryAccess": 0,
  "EnableHWControlInput": 1,
  "EnableRulesControlInput": 0,
  "EnableWeatherControlInput": 0,
  "UnsubscribedBuffersMask": 160
}
```

### Start the App

1. Keep these together:

```txt
LMU_Race_Engineer.exe
voice_clips
```

2. Double-click `LMU_Race_Engineer.exe`.

Keep it running during the session.

3. Start **Le Mans Ultimate**.

4. Click **Open Dashboard**.

To use a phone or tablet, connect it to the same Wi-Fi and type the URL shown in the app window.

To add it to your phone or tablet home screen:

- **iPhone / iPad:** open the URL in Safari, tap **Share**, then tap **Add to Home Screen**.
- **Android:** open the URL in Chrome, tap the menu, then tap **Add to Home screen** or **Install app**.

### Voice Test

Click **Test Voice Clip**.

If you hear sound, voice is working.

Close the app window when you are done.
