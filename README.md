# Vectrex lightpen with integrated buttons

![Lightpen1](https://github.com/rastislavz/Vectrex-Lightpen/assets/76251167/36eb5a88-e7e6-4596-9772-a70f264800ad)

# The construction details

The building of this lightpen is a bit tedious process since it uses the refillable whiteboard marker (PILOT V-Board Master 5979) instead some genuine build body.
The first step is to disembowel the marker guts: after the back is screwed open and the ink cartridge is taken out, the rest of the guts can be simply pulled out with the long nose pliers.
The next step is drilling the holes for cable and for 4 microswitch buttons. To drill the button holes precisely, i found the best way is to first apply the label with the precut button holes and to drill the holes after the label is applied. Since I had lots of labels made for the ordinary lightpen without precut holes, I have made the drill template (in svg directory) which I have printed out, overlaid with the label and than punched the holes with the leather holes puncher.

The cables are directly soldered into the PCBs. Both PCBs are designed with the holes for the cables which serves as strain relife when cables are threaded through the holes. The main body (or call it the lightpen box) PCB contains also smaller holes by which cables can be additionaly secured by cable ties.

The PCB with the microswitches and phototransistor has to be secure inside the pen with some piece of plastic/thick paper and glue.

Its quite interesting where I have found the plastic 9pin connector with 90° pins I have used in building the pen: when I needed 9pin cables for some Vectrex controllers I have used Sega etension cables and I have cut off the male part, and some of those had a small bump in it (like the one sold by console5 https://console5.com/store/atari-sega-commodore-6-1-8m-joystick-controller-extension-cable-cord.html). I was curious why that bump is there and when I have cracked it open, I have found out that Chinese have used the 90° PCB connectors for making the cable and they have just soldered wires onto the pins, but then they had to make that bump to fit. So you do not have to buy that connector if you are using the same cables for the build.

The box case is made with 2 laser cut acrilic (or whatewer material) sheet: in the svg folder.

Shield: [![CC BY-SA 4.0][cc-by-sa-shield]][cc-by-sa]

This work is licensed under a
[Creative Commons Attribution-ShareAlike 4.0 International License][cc-by-sa].

[![CC BY-SA 4.0][cc-by-sa-image]][cc-by-sa]

[cc-by-sa]: http://creativecommons.org/licenses/by-sa/4.0/
[cc-by-sa-image]: https://licensebuttons.net/l/by-sa/4.0/88x31.png
[cc-by-sa-shield]: https://img.shields.io/badge/License-CC%20BY--SA%204.0-lightgrey.svg
