## Raspiradio
![Streamin_Client_with_Speaker](https://github.com/thk4711/raspiradio/blob/master/Images/Client_with_speaker.jpg)
In the 90th listening to music was mostly CD. Then there were MP3's which you could buy online and carry around on devices like an iPod. I still have a lot of CD's and still have many MP3's on my computer - but somehow I almost never use them. It is just so much more convenient to use streaming services like Spotify. Also a smartphone is a way better user interface than a traditional remote control or even a PC based player software. You can sit on your sofa and listen to more or less everything you like.

The same thing is with radio. It used to be mostly FM radio with just a very limited selection of stations which were mostly playing the same things over and over again. Now with Internet radio stations you have access to more or less the whole world. But here I still like the way tradidional radios work. You turn it on and just listen. No need to open an app or so.

With all the benefits of the new technology there are still some things I still like from "the good old days". I still like the idea of using a pair of well sounding speakers which are connected to a capable amplifier. Also the look of "traditional" HiFi components is still something I like. 

The things you can buy like Sonos speakers tend to be expansive and useless without a smart phone. Also there you have no choice which speakers you can connect to the system. There are also some devices in the classical HiFi design available - but they are also very expansive and often difficult to use.

If you want to know more - please watch the video.

[![Streaming Client](https://github.com/thk4711/raspiradio/blob/master/Images/video.jpg)](http://www.youtube.com/watch?v=7hVFVi_NzME)

The main features are:
- Internet radio which works without smart phone
- Status display
- Airplay
- Spotify Connect
- USB sound input to connect a PC
- AUX input
- Remote control 
- 3 band EQ
- Stereo power amplifier
- WiFi network
- Stand by power consumption < 1W
- decent audio quality

To get all this running a Raspberry Pi looked like the best choice. All the streaming services are available and it is the best documented single board computer. The GPIO's allow the connection to a lot of devices.

The software is written in phyton. This is my first project in that language. I would be happy to here what could be improved.

Please have a look at the [WIKI](https://github.com/thk4711/raspiradio/wiki) for more details.

### Todo
- Implement tone defeat function
- Figure out how to enable bluetooth
- Spotify connect for more than one user
- Metadata display for Airplay
- Design low cost and low effort hardware version without a lot of soldering
- Design better sounding high end hardware version (ES9018 DAC, LM3875 amplifier, PGA2311 volume control, bigger transformer)
- WEB interface
- files in "normal" locations (not everything under /install)
- debian package
- install script
- I2S based USB sound interface with digital switching between Raspberry Pi and USB sound
