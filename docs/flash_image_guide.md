## Prerequisites

- A windows, Linux or Mac computer with a [micro SD](https://simple.wikipedia.org/wiki/MicroSD) card slot
- A [micro SD](https://simple.wikipedia.org/wiki/MicroSD) card reader (if the computer does not have a dedicated micro SD / SD card slot)
- The storage card creator software [Balena etcher](https://etcher.balena.io/)
- A .sdcard image file with the Operating System

<span style="color: #be1e2d;">
Micro SD cards (and all  flash-based memory cards) suffer from internal wear as they are used.<br> 
If the Etcher softwar fails, or the device fails to boot, try using a different card.
</span>
<div style="margin: 2rem"></div>

<img src="/images/flashing_procedure-01.png" style="width: auto; border: 1px solid black;" />
Download and install the Etcher software. Once installed, choose the .sdcard file, select the target device, and then click 'Flash!' to create the micro SD card.<div style="margin: 2rem"></div>

<img src="/images/flashing_procedure-02.png" style="width: auto; border: 1px solid black;" />
Insert the card with the contacts facing down. The slot is **push-push** (push until 'click' to insert the card, push until 'click' to remove the card)
<div style="margin: 2rem"></div>

<img src="/images/flashing_procedure-03.png" style="width: auto; border: 1px solid black;" />
Use a small metal wire, like a SIM extraction tool or a paper clip, to **press and hold** the button inside the device for booting from the micro SD card. There are two slots; insert the tool into the one closer to the antenna connectors. The other slot is used for rebooting the device.<br>
<span style="color: #be1e2d;">
The button is somewhat difficult to press, and the 'click' feeling is very soft. It is advised to try pressing it a couple of times beforehand until you get used to it.</span>
<div style="margin: 2rem"></div>

<img src="/images/flashing_procedure-04.png" style="width: auto; border: 1px solid black;" />
**Without releasing the button**, insert the USB-C cable to power on the device. When booting from the micro SD card, the **CPU LED will light steady blue** after a second or so. Once this occurs, you can release the button.<br>

**If you experience any issues, please consider the following troubleshooting steps:**

- If the CPU LED does not light steady blue, and the device seems to boot as usual, ensure that you are pressing the side button properly.
- If no LEDs light up at all (and the device appears to be powered off), double-check that you are pressing the correct button.
- If no LEDs light up at all (and you are pressing the correct button), attempt the process with another SD card.
<div style="margin: 2rem"></div>

<img src="/images/flash_cpu.gif" style="width: auto; border: 1px solid black;" />
After a few seconds, the installation process begins. The device LEDs FIX, LOG, and NET will blink in the pattern shown above.

The Operating System installation typically takes between 2 to 5 minutes, varying based on the quality and wear of the SD card. Upon completion of the process, the three LEDs will illuminate in green for a brief period, and the device will then reboot using the installed operating system.
