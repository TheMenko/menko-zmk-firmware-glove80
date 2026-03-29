# Glove80 ZMK based firmware with SOCD

## Firmware Files
To locate your firmware files and reflash your Glove80:
1. log into GitHub and navigate to your personal config repository you just uploaded your keymap changes to.
2. Click "Actions" in the main navigation, and in the left navigation click the "Build" link.
3. Select the desired workflow run in the centre area of the page (based on date and time of the build you wish to use). You can also start a new build from this page by clicking the "Run workflow" button.
4. After clicking the desired workflow run, you should be presented with a section at the bottom of the page called "Artifacts". This section contains the results of your build, in a file called `firmware.zip`.
5. Download `firmware.zip` and extract it to reveal two files, `glove80_lh-zmk.uf2` and `glove80_rh-zmk.uf2`: these are the firmware for the left and right sides of the keyboard respectively.
6. Flash the firmware to Glove80 according to the user documentation on the official Glove80 Support website (linked above). *Note that unlike firmware built with the standard Glove80 toolchain, you must select the correct firmware file to upload to each half of the keyboard.*

Your keyboard is now ready to use.
