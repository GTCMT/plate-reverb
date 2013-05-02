plate-reverb
============

Greg Tronel, Jay Clark, Scott McCoid

This is a basic plate reverb implementation in Python.
To use the application, run the following from a command prompt / terminal:
$ python reverb.py input.wav output.wav

The application requires a mono input signal, and has a number of optional inputs:

--wetdry (0 - 1)
--damping (0 - 1)
--decay (0 - 1)
--predelay (0 - anything, it's in milliseconds)
--bandwidth (0 - 1)


