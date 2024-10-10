<h1>Help Desk Ticket: Sound Device Troubleshooting</h1>

<h2>Description</h2>
A user had the following issue:<br>
I am trying to play some Christmas music on YouTube, but I have no sound. There is a red X on the speaker icon on the lower right-hand side of the screen, but the speakers are plugged in. I can live with this for now, but later, I have some Skype meetings.

<h2>Troubleshooting Process</h2>

Confirmed what user reported.

- <b>Theory 1: Theory 1: The correct output device is not selected: Right clicked on the sound icon and opened sound settings. The sound page in settings showed “No output devices found”.</b>

- <b>Theory 1: Theory 2: The computer does not recognize the device: I went into the device manager and it showed a “High Definition Audio Device” and when I clicked on it, I got the message “The device is disabled” (Code 22). It also said “Click Enable Device to enable this device.”, but the “Enable Device” button was not active, so I clicked “Change Settings”, entered the Password for the admin account, and could now click “Enable Device”. I tested the audio and it is working like expected.</b>

<h2>Resolution</h2>

- <b> Resolution (Internal): The speaker that the user was attempting to use was not enabled on the computer. I was able to go into the Device Manager and enable the speaker so it is now working.
- <b> Resolution (Client-Facing): The speaker you were trying to use required a setting to be changed in order for the computer to be able to use it. I changed that setting and now you are all set to listen to your Christmas music!

<h2>Environments Used </h2>

- <b>Windows 10</b> (21H2)
