# Level2_CodeClub_Printer
This is a simple repo so that people can look into how the octoprint instance is setuo on the Prusa Mk3s which is at Level2.(and so that i don't forget either)





The Pi has Octoprint installed, the webuser is felix and the password is written underneath the Pi.
The root user is pi as usual and the password is also written underneath the pi. 
Octoprint is a standart installation with the few tweaks for the Mk3s, google to find them. 
I installed a light strip on top so that I can actually see what I am doing. They are also controlled by the Pi using the Enclosure plugin. 
In the plugin, add a simple output with Neopixels direct on the gpio pin 21, with 15 neopixels.
The setting autostart with server is toggled on. 
After that simply wire the 5V and Gnd wires to their respectives pins and the datawire to pin 21 and you should be good to go.
