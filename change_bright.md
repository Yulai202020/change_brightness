ls /sys/class/backlight/
then you will see adapter (or idk what is that) (folder)

cat /sys/class/backlight/(adapter)/max_brightness // get max value

echo (new_brightness) > /sys/class/backlight/(adapter)/brightness // set brightness
