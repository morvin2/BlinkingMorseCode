# BlinkingMorseCode
the program translates morse code generated by blinking. Uses only opencv and haar cascade. No use of Dlib

Long blink is equal to dash

Short blink is equal to dot

refer https://en.wikipedia.org/wiki/Morse_code#/media/File:International_Morse_Code.svg for the morse code.

Tips for optimum results--
1. The face needs to be pretty close to the screen for it to work properly.
2. The long blinks are not very long, just half a second and the short blinks are like regular blinks
3. You have to wait a little for it to register that letter and move on to the next one
4. Space is registered when 7 consecutive short blinks are registered
