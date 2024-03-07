# change brightness on linux

ls /sys/class/backlight/

Then you will see adapter (or idk what is that)

cat /sys/class/backlight/(adapter)/max_brightness # get max value

echo (new_brightness) > /sys/class/backlight/(adapter)/brightness # set brightness
