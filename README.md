  Step by step tutorial to make your Raspberry pi pico / Raspberry pi pico w in to a bad usb.

Download the github file (and if its in a zip or winrar extract the content).

Begin with pressing the boot button on the raspberry pi pico (w) and plug it in your pc.

Now we are ready to begin with setting up the raspberry pi pico (w)

First open Step 1 and drag the flash_nuke.uf2 in to the pico (w) and wait untill it is back.

Now open Step 2 and drag the adafruit-circuitpython-raspberry_pi_pico-en_US-8.0.0.uf2 in to the pico or if you have a pico w drag adafruit-circuitpython-raspberry_pi_pico_w-en_US-8.0.0.uf2 in to the pico w and wait untill it is back.

Now open Step 3 and drag all the files in to the lib folder.

Now open Step 4 and drag all the files in the root directory (or main directory).

  ONLY IF YOU HAVE A PICO W
Now open Step 5 and drag the file secrets.py in the root directory (or main directory).

Now if you have done all the steps you can create a payload.
Please write it in ducky script and save it in the root directory (or main directory) and CALL IT 'payload.dd' (i have a file that you can use in Step 6).

Now you can unplug it and its done. 
If you want to the change the payload.dd file you cant. Im still working on that, but if you do want to change it please repeat all the steps.

(please note that my english is not great so sorry for that.)

  Here are some links to pre-made payloads by hak5.
https://hak5.org/blogs/payloads/ or
https://github.com/hak5/usbrubberducky-payloads/tree/master/payloads/library/exfiltration
