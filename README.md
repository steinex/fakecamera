## What this does

Shares an individual screen as a virtual webcam on Linux.

## How to use

* Make sure you have installed ffmpeg and v4l2loopback
* Start fakecamera script and choose which screen you want to share
* Choose myFakeCam as webcam in browser

You can switch between webcams freely (at least in Google Hangouts / Meet, didn't test others)

Hint: If your meeting tool does not flip your webcam (Hangouts / Meet does this), remove `-vf 'hflip'` from ffmpeg call in the script.

