# Color change lights server

## Server
get/change color of light


## Devices
on startup, get light color and set 

on button press, contact server to change color 


## Server Setup
python3 -m venv venv
pip install Flask
pip install -U flask-cors
pip install Flask-JWT
pip install flask_httpauth

Generate key, place in /usr/etc/key


## PI Setup
add to /etc/rc.local:
python /home/pi/src/zlight/client/client.py &

RGB LED Control
https://jackw01.github.io/led-control/

commenting out the line dtparam=audio=on in /boot/config.txt

NOTE: Not all commands here may have been necessary.

pip install rpi.gpio

    sudo apt-get install scons swig libev-dev python3-dev python3-setuptools
    pip install pytest-runner
    pip install wheel
    python -m pip install --upgrade pip
    python -m ensurepip


    https://learn.adafruit.com/circuitpython-on-raspberrypi-linux/installing-circuitpython-on-raspberry-pi
    https://learn.adafruit.com/adafruit-neopixel-uberguide/python-circuitpython#python-installation-of-neopixel-library-17-9sudo sudo sudo 
    pip install neopixel

