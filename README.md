# Dell-Linux
Documentation on installing Ubuntu Linux on Dell XPS 13 / 15 Laptops

This guide will provide you with information on running Ubuntu 18.04 Linux on a Dell XPS 13 or 15 Laptop. 


For starters, the guide will outline steps common to both models, with model-specific instructions listed under each model.
This guide is aimed at DevOps Engineers and Professional Researchers, but feel free to adapt to your own personal tastes and preferences. 

Additionally, this drive does not cover dual booting, or preserving the existing Windows 10 install. If you wish to run Windows in a dual boot, you'll need to use a gparted boot image to shrink the Windows partition before installing Ubuntu. 
If you plan to run Windows in a VM, you'll want to retrive your "product key" from the Windows install first. 

1.) Create a bootable install image of Ubuntu 20.04 ( burn to DVD if you have a portable USB DVD drive, or bootable USB stick)
https://ubuntu.com/download/desktop/thank-you?version=20.04.4&architecture=amd64

1a.) If you are on Windows, you can use Rufus (https://rufus.ie/) to create a bootable USB thumb drive. 
1b.) If you are on Linux, you can use UNetbootin (https://unetbootin.github.io/) to create a bootable USB thumb drive

2.) BIOS SETTINGS - Boot the laptop and enter the BIOS. You'll need to change several settings. 
2a.) Change the SATA setting from RAID, to AHCI.
2b.) Change "fast boot" to "throuough" 
2c.) (Optional) Disable "secure" boot. 
2d.) Save settings, attach external USB DVD with bootable Ubuntu DVD, or attach bootable Ubuntu USB thumb drive

3.) Boot Ubuntu install image, and start the installation process.


## XPS 13 
### (7390 - useful for other models as well)

## XPS 15
### (7590 - useful for other models as well)

## Optional - Dell D6000 USB-C Display Link Dock

### References: 

Dell Support, How to Install Ubuntu Linux on your Dell PC, https://www.dell.com/support/article/us/en/04/sln151664/how-to-install-ubuntu-linux-on-your-dell-pc?lang=en

Ubuntu Wiki, XPS-13-7390-2-in-1, https://wiki.ubuntu.com/Dell/XPS/XPS-13-7390-2-in-1

Arch Linux Wiki, Dell XPS 15 9570, https://wiki.archlinux.org/index.php/Dell_XPS_15_9570 
