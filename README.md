# chromeduino
Abstraction utility and workaround for the limitations of Arduino programming on ChromeOS

# The Problem:
When learning to program for both the Arduino Nano and Arduino Mega, I attempted to utilize my AMD64 Chromebook to code in the lab, much to my dismay I found that there didn't seem to be any IDE that supported Arduino boards larger than an Uno for ChromeOS. 


Both the Arduino Cloud Editor and Web Editor only support the following boards using their software:
![web_editor_on_chromebook](https://github.com/baronarkas/chroduino/assets/149717373/80c0cb4c-7cac-4f94-91f2-1243c652862e)


# The Solution:
Using some linux know-how, I was able to successfully compile and upload .ino source code to an Arduino Mega from my ChromeOS device!


The following process will work for both AMD and ARM chipset Chromebooks.
