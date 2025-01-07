The controller that came with my Simsonn Sim Racing Pedals is a cut down version of freejoy.

I installed a larger 64kb chip on the controller but the pcb leaves Boot1 floating.

This causes it to intermittently boot into either normal or flasher mode so I disabled the onboard flash mode.

See Releases page for binary

I flashed with 

st-flash erase

st-flash write SIMSONN_FreeJoy_v1_7_1b3.bin 0x08000000


For some reason the app part of the program doesn't compile properly on my system so I just used the binary compiled by FreeJoy
