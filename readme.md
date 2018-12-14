# Bus-Probe-Tester-UI

To download the most recent project without installing GIT, please press the green "Clone or Download" button and select "Download ZIP".



The Steps 
-------------------

The following are the steps for setting up and polling our *Bus Probe Sensors* using a TPP2(G2) with LCD and Keypad.


1. *Upload* - The monitor and firmware is uploaded to the Probes

2. *Set ID* - Each Probe is given a unique ID between 1 and 247

3. *Scan* - A scan is carried out in order to detect each Probe

4. *Poll* - The Probes are polled on a timer and the latest values are displayed on screen

   

Step 1: Uploading the Monitor and Firmware
------------------

To begin, we must first ensure that the correct monitor and firmware are installed on the Probes. Start the **BP_Tester_UI** application and press the **Upload** button. Then, start the Probe in monitor mode by powering it on while holding the MD button on the Probe. The point of a pen or a pin can be used to press this MD button.  If we have successfully started the Probe in monitor mode, the LED light will be solid green. 

Next, we upload the monitor by pressing the **Upload Monitor** button. A loading bar will display on the screen to update us on the progress. If successful, a message box will be displayed on the screen. To complete the installation, we remove the power from the Probe and power it on again. The red LED light will turn solid for a few seconds, then blinking green and solid red, and finally just blinking green. The monitor has been updated!

Next, we update the firmware. Once again, we start the Probe in monitor mode by powering it on while holding its MD button. This time, we press **Upload Firmware**. Again, a message box will be displayed if successful. In order to complete the installation, we must once more disconnect the power and reconnect again.

This process should be repeated for each Probe we are connecting. For best results, uploading should be carried out with only one Probe connected at a time. When all Probes have both monitor and firmware uploaded, we can proceed to setting IDs.



## Step 2: Setting IDs

Navigate back to the home screen by pressing the **Exit** button. Then press the **Set ID** button. Use the **+** and **-** buttons to select the Probe number you wish to set. Then, press and hold the MD button on the desired Probe. The green LED should turn green. Then, press the **Set ID** button. If done correctly, the Probe ID will have been changed.

This process should be repeated for each Probe we are connecting. . Each Probe should be given its own **<u>UNIQUE</u>** ID between 1 and 247. Two Probes being assigned the same ID will cause erratic results.



## Step 3: Scanning for Probes

Navigate back to the home screen by pressing the **Exit** button. Then press the **Scan** button. A scan will be carried out and all Probes between 1 and 247 will be detected. We are now ready to poll.



## Step 4: Polling Probe 

To being polling Probes, press the **Poll** button. The Probes will be polled on a timer. A maximum of 6 Probes can be displayed per page. If more than 6 Probes have been connected, we can cycle through the pages by pressing the MD button on the TPP2(G2).