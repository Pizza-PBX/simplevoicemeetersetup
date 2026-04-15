# How To Set Up Voicemeeter Banana for Prank Calling / Audio Routing

**This setup will only work if you have Voicemeeter Cable A and B installed.**  
You can download them from the official VB-Audio website.

### 10 Easy Steps to Set Up Voicemeeter Banana

**Step 1:** Download Voicemeeter Banana  
[Download Link](https://web.archive.org/web/20230323031739/https://vb-audio.com/Voicemeeter/banana.htm)

**Step 2:** Extract the file to your Desktop, then run the Setup and install it.  
(It will ask you to reboot — hold off for now.)

**Step 3:** Download and extract the **VB-Cable Pack** to your Desktop.

**Step 4:** Unzip **Cable A** and run `Setup x64.exe` as Administrator.  
This installs the first virtual cable. (It will ask you to reboot — hold off.)

**Step 5:** Unzip **Cable B** and run `Setup x64.exe` as Administrator.  
This installs the second virtual cable. Now you can reboot your computer when prompted.

**Step 6:** After rebooting, open Windows **Sound Settings**:
- Set **Output** to `Voicemeeter Aux Input`
- Set **Input** to `Voicemeeter Aux Output`

**Step 7:** Go to **Change System Sounds**:
- Click on **Playback** tab → Scroll down to `Voicemeeter Aux Input` → Right-click → **Set as Default Communication Device**
- Click on **Recording** tab → Scroll down to `Voicemeeter Aux Output` → Right-click → **Set as Default Communication Device**

**Step 8:** Open **Voicemeeter Banana** (search for it in the Windows search bar).  
Pin it to your taskbar for convenience.

**Step 9:** Copy the following settings in Voicemeeter Banana:
- Under **Hardware Input 1 (Me)**: Choose your Microphone → Select **MME** for best sound quality.
- In the top right corner under **VBAN / A1**: Click it and choose your Headphones/Speakers → Select **MME** for best sound quality.

**Step 10:** Click **Menu** → **Save Settings**, name your settings and save them.  
Then go back to **Menu** → **Load Settings on Startup** and select the settings you just saved.  
(This ensures Voicemeeter loads your configuration automatically every time.)

### Optional: Enable Two-Way Audio with Discord (for the caller to hear Discord audio)
If you want people in Discord to be able to talk to the person you're calling:
- Enable **B1** and **B2** on **Line 5** (under Chrome / Browser section).  
This routes audio from Discord, YouTube, soundboards, etc. to your calling software (e.g. MicroSIP).

---

**Tip:** Always run Voicemeeter Banana as Administrator for best compatibility.

You can now copy and paste the entire block above.
