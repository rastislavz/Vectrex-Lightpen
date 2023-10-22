# Vectrex lightpen with integrated buttons

![Lightpen1](https://github.com/rastislavz/Vectrex-Lightpen/assets/76251167/ea9eeb2e-9a6d-4a66-b298-c3a4d30d64f4)

# The construction details

The building of this lightpen is a bit tedious process since it uses the refillable whiteboard marker (PILOT V-Board Master 5979) instead some genuine build body.
The first step is to disembowel the marker guts: after the back is screwed open and the ink cartridge is taken out, the rest of the guts can be simply pulled out with the long nose pliers.
The next step is drilling the holes for cable and for 4 microswitch buttons. To drill the button holes precisely, i found the best way is to first apply the label with the precut button holes and to drill the holes after the label is applied. Since I had lots of labels made for the ordinary lightpen without precut holes, I have made the drill template (in svg directory) which I have printed out, overlaid with the label and than punched the holes with the leather holes puncher.

The cables are directly soldered into the PCBs. Both PCBs are designed with the holes for the cables which serves as strain relife when cables are threaded through the holes. The main body (or call it the lightpen box) PCB contains also smaller holes by which cables can be additionaly secured by cable ties.

The PCB with the microswitches and phototransistor has to be secure inside the pen with some piece of plastic/thick paper and glue.

Its quite interesting where I have found the plastic 9pin connector with 90° pins I have used in building the pen: when I needed 9pin cables for some Vectrex controllers I have used Sega etension cables and I have cut off the male part, and some of those had a small bump in it (like the one sold by console5 https://console5.com/store/atari-sega-commodore-6-1-8m-joystick-controller-extension-cable-cord.html). I was curious why that bump is there and when I have cracked it open, I have found out that Chinese have used the 90° PCB connectors for making the cable and they have just soldered wires onto the pins, but then they had to make that bump to fit. So you do not have to buy that connector if you are using the same cables for the build.
