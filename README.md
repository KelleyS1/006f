# 006f
 
Software needed: Max/MSP and Wekinator(free program download able at: http://www.wekinator.org/downloads/ )
Hardware: midi keyboard (screen and projector)
Sheet music: Pick which ever piece you would like to play. For example, I’ve used selections from Bartok Mikrokosmos. There is no specified duration for this work. 

The URL of the GitHub repository: https://github.com/KelleyS1/006f

More detailed instructions at in the pdf titled “006f Weki Setup Instructions” in the main folder.


Abstract

The Max patch has a midi input that constantly receiving 5 different parameters, which are ‘the number of notes(int)’, ‘pitch(MIDI)’, ‘velocity(MIDI)’, ‘note duration (ms)’ and the ‘interval time of note events(ms)’ .These parameters have been trained to effect the videos Brightness, Contrast, Saturation, HUE value, Edge, and Pixelation values of the video. Thus, you can play with real time audio-visual effect corresponding to your playing. 


How to run this project?

1.Open the ‘00f6.maxpat’ inside “Max Patch” folder. 

2.Once the Max patch is open follow steps within the patch to setup your midi controller and run the video. Make sure you can see midi controller’s key presses reflected within the keyboard in the patch. Responds to middle C to C6 (midi # 60-84). 

3. Open Wekinator program and load the file inside “wekMidi” folder. Do this through file > open project>(navigate to 006f-main/wekiMidi and select) WekinatorProject.wekproj. More through instructions in google doc listed above.

4. Once wekinator file is loaded click “start listening” (port 6448 should be the default). Then click “Run”. Now when you press your midi controller keys you should see wekinator reacting and the video changing to respond.


- - - - - - - - - - - - - - - - - - - - - - - - - - - - - - - - - - - - - - - - - - - - - - - - - - - - - - - - - - - - - - - - - -

Possible advanced customization of this piece: 
You can change the video (instead of the two flying kites) to any video you’d like. 
You can train the Wekinator program to entirely new settings.

If you’d like to do any of these and need guidance, contact me at KelleyLSheehan@gmail.com.
