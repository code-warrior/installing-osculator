# Installing OSCulator
**Note**: OSCulator is macOS-only. Download from [https://osculator.net/download/](https://osculator.net/download/)  
**Burden**: ~10 mins

---

1. [Download OSCulator](https://osculator.net/download/) for macOS.
2. During the installation process, you’ll be presented with a dialog box titled **Accessibility Access**. Click `Open System Preferences`.<br>
   <img src="images/Screen Shot 2021-11-15 at 6.29.06 AM.png">
3. Click the **Privacy** tab under **Security & Privacy**. If the lock in the lower left corner is engaged, unlock it in order to check off the box associated with `OSCulator.app`, which appears on the right side. Once you check off `OSCulator.app`, relock the **Privacy** window.<br>
   <img src="images/Screen Shot 2021-11-15 at 6.29.22 AM.png" title="The Privacy window before unlocking it.">
   <img src="images/Screen Shot 2021-11-15 at 6.29.33 AM.png" title="The Privacy window after unlocking it.">
   <img src="images/Screen Shot 2021-11-15 at 6.29.35 AM.png" title="The Privacy window with the OSCulator.app box checked.">
   <img src="images/Screen Shot 2021-11-15 at 6.29.41 AM.png" title="The Privacy window locked, after having checked off the OSCulator.app checkbox.">
4. Launch OSCulator, then open the parameters window by clicking the cog wheel in the upper right hand corner.
   <img src="images/Screen Shot 2021-11-15 at 6.34.49 AM.png">
5. Choose **Devices** in the top left corner of the window, then **Wiimote** along the left column.<br>
   <img src="images/Screen Shot 2021-11-15 at 6.34.58 AM.png">
6. Locate your Wii remote. Assuming batteries have already been installed, turn the Wii remote over and press the sync button on the battery cover. Between one and four lights will flash on the remote, depending on the batteries’ capacity. Your Wii is now in Bluetooth pairing mode.<br>
7. Make sure Bluetooth is enabled on your computer. Click the **Pair a Wiimote** button in the right area, to the right of **Setup**. A sequence of hex-based, dash-separated numbers should appear under **Address**. (This is the MAC address of the Wii remote. Think of it as its serial number.) Highlight the MAC address by clicking it.<br>
   <img src="images/Screen Shot 2021-11-15 at 6.37.31 AM.png">
8. To the right of **Settings** in the same window listed under the previous step, check off **Attitude Angles (pitch, roll, yaw)**, then, on the bottom, check off **Send Battery Level**. (Ignore that it’s unchecked in the screen shot above.)<br>
9. Go back to the OSCulator window rendered in step 4 of this tutorial, then, press _all_ the buttons on the Wii. If you see buttons in the OSCulator window on the left (to the right of the checkboxes) light up as you press buttons on the remote, then you’ve successfully paired the Wii to OSCulator via Bluetooth. Close the settings window, then save the current OSCulator configuration.
10. We’re not done yet. The Bluetooth signal that OSCulator is receiving needs to now be repeated by your computer to Max. Select everything by typing `Command + A`. With all items highlighted, place your mouse below **Event Type** and click. Choose **OSC Message**.<br>
   <img src="images/Screen Shot 2021-11-15 at 7.09.57 AM.png">
10. With all the items still highlighted, position your mouse under the **Value** column. Click and choose **New**. The opened window should be focused on the **OSC Routes** tab at the top.<br>
   <img src="images/Screen Shot 2021-11-15 at 7.10.08 AM.png">
11. Locate the arrow next to the grey cogwheel under the section **OSC URL or Nearby OSC Service**. Click it and choose **localhost:9000 (Max/MSP or Pure Data)**<br>
   <img src="images/Screen Shot 2021-11-15 at 7.10.13 AM.png">
12. Clicking the buttons on the Wii should now trigger green LEDs in the OSCUlator window, indicating that OSCulator is now transmitting OSC data to Max/MSP. Save this configuration again.

---

**Note**: The OSCulator manual is available from [https://dl.OSCulator.net/doc/OSCulator+2.12+Manual.pdf](https://dl.OSCulator.net/doc/OSCulator+2.12+Manual.pdf).
