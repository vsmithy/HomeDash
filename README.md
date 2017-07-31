# HomeDash
A collection of apps and dashboards to act as an 'at a glance' home interface

## Concept
* This will be in the vein of a raspberry pi smart mirror, except without the mirror, and a lot more UI and functionality
* There will be a monitor, raspberry pi, arduino & several sensors (that I kind of already have laying around for the arduino), and some hardware buttons for screen navigation.
* Data will come from a variety of sources.

## Components
This will be a mix of:
* IoT
  * Raspberry Pi 3 for primary server: https://www.raspberrypi.org/
  * Arduino for some of the sensor I/O that the apps will control
* JavaScript, HTML, CSS
  * For the UI: http://googlecreativelab.github.io/coder/
* Python (maybe)
  * For some of the computation

## UI
Five screens to represent the various 'systems' I want to keep track of:
* Calendar - A calendar so that everyone in our home can know what's going on
* Maintenance - This view will aim to capture the essentials of home and device maintenance info
  * It will try to show dates and items such as auto maintenance, lawn care cycles, home air filter, etc
* Finances - Will require fingerprint for access
  * Financial dashboard showing income, expenses, and savings goals at a glance
  * Fingerprint reader: https://www.sparkfun.com/products/11792
* Food & Shopping
  * Considering including InStock as one of the screens
  * https://github.com/vsmithy/instock-native
* Combined View - Shows something from each of the 4 screens.
