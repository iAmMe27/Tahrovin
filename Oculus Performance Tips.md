# Quest 2 Performance Tips
There are a couple things you can do that can help with performance that I recommend.

## Using OpenComposite
Open Composite can now use Steam! This is wierd I know but trust me for a minute. In MO2 under the YOUR CHOICES subheader disable SteamVR and enable Skyrim VR OpenComposite Fixes Custom Build (Requires Steam be set to manage OPENXR), to change back you just switch them back. Doing this requires you to set steam to be your openxr environmet. Go to your SteamVR settings, show advanced, go to openXR and set steam to be openXR it should look like the image below.This version and the latest version of Virtual Desktop are compatible!

![SteamVR OpenXR example](img/SteamVRopenXR.png)

Alternatively you can bypass steam altogether if you use Virtual Desktops new VDXR. Just make sure VDXR is enabled on Virtual Desktop Streamer, make sure OC is enabled instead of steamVR in MO2 and run!

![OC VDXR example](img/OCVDXRInstructions.png)

***Note:** OpenComposite does not work for any other headset than Oculus headsets!*

## Change Refresh Rate
Changing the refresh rate to a higher one in the Oculus settings reduces the maximum resolution delivered to your headset as well as offering a smoother feel to the game. The reduced resolution will help the game run at a more stable FPS and likely a higher FPS. Combine the higher FPS with the higher refresh rate of the Quest 2 and you have a much nicer game playing experience. 

So, to do this you need to start by connecting your Quest 2 headset to your PC via USB, power your headset on and then head over to **Devices** in the left-hand menu of the Oculus PC client.

![Oculus Client 1](img/OculusClient00.jpg)

When in there, connect select the top menu option:

![Oculus Client 2](img/OculusClient01.png)

In the right-hand menu that pops-up, scroll down to **Graphics Preferences**:

![Oculus Client 3](img/OculusClient02.png)

In the pop-up menu, ensure that the **Automatic** resolution scaling is *OFF*. I recommend trying each setting in turn to see at which point you get the best look vs performance. I can't tell you what point that would be because it's a subjective choice. Also ensure that the **Rendering Resolution** is at *1.0x* as stated in the main readme.

![Oculus Client 4](img/OculusClient03.png)

Once you've made your changes, click **OK**.

## Increase the Oculus Link USB Data Rate
For some odd reason, the default Oculus Link settings limit the USB data rate between your PC and the Oculus headset to 100Mbps but the maximum link speed is **500Mbps.** That's *5 times* the data rate over the regular setting.

Increasing the USB data rate means that your PC and your headset can communicate much faster, meaning that VR games will look sharper because there is less compression needed on the data as well as a noticeable reduction in artifacts and flickering in your vision.

To do this, head to the installation folder of the Oculus PC client, usually `C:\Program Files\Oculus`, and head into the **Support** folder:

![Explorer 1](img/Explorer00.png)

Once there, head into the **oculus-diagnostics** folder:

![Explorer 2](img/Explorer01.png)

Once there, run the **OculusDebugTool**:

![Explorer 3](img/Explorer02.png)

in the Oculus Debug Tool, change **Encode Bitrate (Mbps)** to 350. You can go as high as 500Mbps as mentioned earlier but try somewhere in the middle first before going all in.

![Oculus Debug Tool 1](img/OculusDebugTool00.png)

Once changed, close out the tool and done!

## Monitoring Performance with an Oculus Quest 2
The Oculus Debug Tool also comes with a performance overlay. Follow the steps above to open the Oculus Debug Tool and set the **Visible HUB** option to *Performance*.

***DON'T CLOSE THE OCULUS DEBUG TOOL AS THIS WILL ALSO CLOSE THE PERFORMANCE OVERLAY.***

You will know when it is enabled as soon as you put on your headset. You can use the info here to help with monitor the performance you are getting in-game.