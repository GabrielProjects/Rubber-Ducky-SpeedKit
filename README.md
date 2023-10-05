<h1 align="center">pico-ducky</h1>

<div align="center">
  <strong>Make a cheap but powerful USB Rubber Ducky with a Raspberry Pi Pico</strong>
</div>
<br />

## Quick Start Guide
1. First of all we need to attach the Raspberry Pi Pico to the machine we are usingh thru an USB cable while pressing the button on it.
   As soon as we have done that, we can see in the files the ``RPI-RP2`` directory.

2. We than have to insert in that the file that can be found in the Step1 folder.
   The device will than automatically copy the file we just putted into it, unplug itself and re-connect as the ``CIRCUITPY``.

3. We than have to delete everything inside the ``CIRCUITPY`` directory, copy everything inside Step2 folder and paste it inside the root of the ``CIRCUITPY``.

4. We'll just have one step left, witch is inserting the payload that we are going to use inside the ``CIRCUITPY`` root.
   Just pay attention, since as soon as you'll insert the payload into the ``CIRCUITPY`` root it will automatically run, 
   so you'll have to be quick and remove the USB cable as soon as it finish to copy the paload file.

5. After doing this, you'll have a fully-armed Rubber-Ducky.

6. If you want to modify the contents inside the ``CIRCUITPY`` root, you'll need to insert the raspberry pi pico while pressing it's button, and than insert the NUKE file inside the ``Reset`` Folder.
   It will delete every file that you putted inside the ``CIRCUITPY`` root and restore it to factory-settings (witch are the things that were actually inside of the Step1 file).

If you are searching for any payload, it would be usefoul to check: https://github.com/hak5/usbrubberducky-payloads/tree/master/payloads
