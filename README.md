# radar
Display flight tracks on the UnicornHatHD module for Raspberry Pi

This will run without the UnicornHatHD module, but will simply print information to the console.

Dependencies: numpy, requests

Run the tracker.py module, specifying the coordinates you wish to track in the call to the track function. The range argument defaults to 25km but can be changed.

Acknowledgments: the Kalman Filter code is adapted from the examples at http://scottlobdell.me/2014/08/kalman-filtering-python-reading-sensor-input/
