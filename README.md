# flint-os-v3.2_dev-reupload

## This is the Official Flint OS Operating System. The Predecessor to FydeOS.
### I do not own this. This is a reupload of the FlintOS Operating System by *Flint Innovations Limited* as the OS cannot be downloaded anymore due to an acquisition by [Neverware](www.neverware.com).

### Based on Chromium R62
### Built on 21/12/2017

#### It supports all major Graphics Cards/Chips made either during/prior to 2017. Support for chips after 2017 is not certain.

#### This is the dev version of FlintOS and may not include Google Play Store.

## Official Release Highlights (Taken from the FlintOS Website):

* Refreshed UI for OOBE, app launcher and more

* Added “Advanced settings” menu in OOBE, allows broadcom wifi user to switch driver easily. Also allows changing trackpad working mode instantly

* Updated Flint OS Settings app

* Enhanced Docker support for optimised I/O

## How to Flash for installation:

### 1. Download balenaEtcher / Rufus.

[Rufus](https://rufus.ie/)

[balenaEtcher](https://www.balena.io/etcher/)

### 2. Go to the releases page for this GitHub.

Once you're there, download the FlintOS v3.2_dev img file.

### 3. Select your usb in either Rufus or balenaEtcher

The USB should be at least *8 Gigabytes* in size.
**If using balenaEtcher, follow step 4 first.**

### 4. Select the img file in either Rufus or balenaEtcher

**If using balenaEtcher, you have to follow this step first.**
Locate the img file you have just downloaded.

### 5. Start the flashing process.

Just click start and let the software do its magic.

## Installation (Taken From the FlintOS Website.):

### 1. Enter the terminal
After the GUI of Flint OS has been loaded, press **Ctrl+Alt+F2 (on some machines, including the Apple Macs the keys are Fn+Ctrl+Alt+F2)** to enter the tty command line interface. If needed, you can press **Ctrl+Alt+F1 (or Fn+Ctrl+Alt+F1)** to get back to GUI mode. Alternatively, you can press **Ctrl+Alt+t (or Fn+Ctrl+Alt+t)** with the Chromium browser launched to enter the Crosh, then enter ```shell``` to activate the Crosh shell.



### 2. Login
Flint OS will ask you for a login name and then a password. Before Flint OS for PC v0.3, the default username and password are both ```chronos```. If any later release of Flint OS was released for PC, they would not provide a default password for security reasons.



### 3. Determine the target drive
Enter command
  ```lsblk```
to obtain a list of attached physical hard drives recognised by the system. Under normal circumstances, your hard drives will be displayed assdxin the list printed by this command. You need to determine the label of the hard drive you want to install Flint OS to based on the size and the number of partitions, e.g.sda. The following command will use sda.



### 4. Run installation script
Enter command
```sudo /usr/sbin/chromeos-install --dst /dev/"your hard drive"```
You will get asked for sudo password. The installation script will confirm with you once again if you wish to continue and your hard drive will be erased. If this is what you really want, key in ```y```.

## If you have any other questions, you can check the [FAQ](https://flintos.io/faq/) which it still available, you can follow it for questions such as enabling multi-touch gestures on FlintOS.
