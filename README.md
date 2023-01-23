# home-assistant-moonraker
Integration between Moonraker and Home Assistant


A lot of Template sensors and rest sensors to have all the information I need from Moonraker (Klipper) on Home Assistant.
This way I can create a dashboard using HADashboard (AppDaemon) to monitoring my printer.

To have all this sensors available on your Home Assistant you just need to copy ```moonraker.yaml``` to your packages folder and make sure you update the IP address. (Replace all instances of the text ```<moonraker-ip-address>``` in moonraker.yaml with the IP address of your installation.)

If you are using this for multiple Printers in the same Home Assistant instance, be sure to adjust all the friendly names so that you don't end up with tha same name-2 (unless that works for you).  Do this before you reload HA or HA will generate all -2 entities and you will need to go thru them in HA and change the friendly names there. (That gets kind of messy.)  The rest, rest_command, camera, and sensor values will need to be changed and the templates adjusted to match those names.  This is not intended to be used with multiple printers, but it is indeed possible.

I'm using a [7" Touchscreen](https://www.amazon.es/gp/product/B07K32M4LJ/ref=ppx_yo_dt_b_asin_title_o02_s00?ie=UTF8&psc=1) connected to a Raspberry Pi 4B.
I also design a case for this screen and it's available on [Cults3D](https://cults3d.com/en/3d-model/gadget/touchscreen-7-case)

![screenshot](screenshot.png?raw=true)




## Thank you

<a href="https://www.buymeacoffee.com/denkyem" target="_blank"><img src="https://www.buymeacoffee.com/assets/img/custom_images/orange_img.png"></a>
