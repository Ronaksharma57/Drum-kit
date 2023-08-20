# Drum-kit
Drum-kit With Sound
This is a drum kit web app that allows you to play different drum sounds.

To play a drum sound, click on the corresponding button. The buttons are labeled with the letters w, a, s, d, j, k, and l.

The sounds are loaded from the sounds/ folder. The filenames of the sounds correspond to the letters on the buttons.

For example, the sound file crash.mp3 is loaded when the w button is clicked.

The code for the drum kit is in the index.html file. The code for the sounds is in the sounds/ folder.

Here is a step-by-step explanation of how the code works:

1. The index.html file loads the sounds/ folder.
2. The index.html file creates the buttons and assigns them onclick handlers.
3. The onclick handlers call the corresponding function to play the sound.
4. The functions play the sound by creating an Audio object and calling the play() method.

