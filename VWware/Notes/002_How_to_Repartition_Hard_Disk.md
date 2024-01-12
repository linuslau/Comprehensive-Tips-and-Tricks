# How to Repartition Hard Disk

- [How to Repartition Hard Disk](#how-to-repartition-hard-disk)
  - [Repartition Step by Step](#repartition-step-by-step)
    - [Add a Ubuntu ISO to VM DVD](#add-a-ubuntu-iso-to-vm-dvd)
    - [Press F2 to BIOS](#press-f2-to-bios)
    - [BIOS Main Menu](#bios-main-menu)
    - [BIOS Boot Order](#bios-boot-order)
    - [BIOS CD First](#bios-cd-first)
    - [FPress F10 to save and exit](#fpress-f10-to-save-and-exit)
    - [Quit Installation](#quit-installation)
    - [Ubuntu Homescreen](#ubuntu-homescreen)
    - [Start GParted](#start-gparted)
    - [Check Unallocated](#check-unallocated)
    - [Partition Table](#partition-table)
    - [Select Partition to resize](#select-partition-to-resize)
    - [Drag to expand](#drag-to-expand)
    - [Apply Change](#apply-change)
    - [Applying Change](#applying-change)
    - [Applied Change](#applied-change)
    - [Restart Ubuntu](#restart-ubuntu)
    - [BIOS Boot Order Reversion](#bios-boot-order-reversion)
    - [BIOS Save and Reboot](#bios-save-and-reboot)
    - [Check New Partition Size with command](#check-new-partition-size-with-command)
    - [Check New Partition Size with GParted](#check-new-partition-size-with-gparted)

## Repartition Step by Step

### Add a Ubuntu ISO to VM DVD

![01_Add_DVD_Ubuntu_ISO](../Images/002_How_to_Repartition_Hard_Disk/01_Add_DVD_Ubuntu_ISO.png)

### Press F2 to BIOS
Click mouse once to be in guest so that F2 is intercepted)

![02_F2_to_BIOS](../Images/002_How_to_Repartition_Hard_Disk/02_F2_to_BIOS.png)

### BIOS Main Menu

![03_BIOS_Main](../Images/002_How_to_Repartition_Hard_Disk/03_BIOS_Main.png)

### BIOS Boot Order

![04_BIOS_Boot_Order](../Images/002_How_to_Repartition_Hard_Disk/04_BIOS_Boot_Order.png)

### BIOS CD First

![05_BIOS_Boot_Order_CD_First](../Images/002_How_to_Repartition_Hard_Disk/05_BIOS_Boot_Order_CD_First.png)

### FPress F10 to save and exit

![06_F10_Save_and_Reboot](../Images/002_How_to_Repartition_Hard_Disk/06_F10_Save_and_Reboot.png)

### Quit Installation
* If come to installation interface, quite it
![08_Quit_Installation](../Images/002_How_to_Repartition_Hard_Disk/08_Quit_Installation.png)
* If come to Try Ubuntu/Install Ubuntu interface, select Try Ubuntu
![08_Try_Ubuntu_or_Install_Ubuntu](../Images/002_How_to_Repartition_Hard_Disk/08_Try_Ubuntu_or_Install_Ubuntu.png)

### Ubuntu Homescreen

![09_Ubuntu_Homescreen](../Images/002_How_to_Repartition_Hard_Disk/09_Ubuntu_Homescreen.png)

### Start GParted

![10_Start_Gparted](../Images/002_How_to_Repartition_Hard_Disk/10_Start_Gparted.png)

### Check Unallocated

![11_Gparted_Unallocated](../Images/002_How_to_Repartition_Hard_Disk/11_Gparted_Unallocated.png)

### Partition Table

![12_Gparted_Select_Partition](../Images/002_How_to_Repartition_Hard_Disk/12_Gparted_Select_Partition.png)

### Select Partition to resize

![13_Gparted_Resize](../Images/002_How_to_Repartition_Hard_Disk/13_Gparted_Resize.png)

### Drag to expand

![14_Gparted_Resize_Drag_to_End](../Images/002_How_to_Repartition_Hard_Disk/14_Gparted_Resize_Drag_to_End.png)

### Apply Change

![16_Gparted_Apply_Change](../Images/002_How_to_Repartition_Hard_Disk/16_Gparted_Apply_Change.png)

### Applying Change

![17_Gparted_Applying](../Images/002_How_to_Repartition_Hard_Disk/17_Gparted_Applying.png)

### Applied Change

![18_Gparted_Applied](../Images/002_How_to_Repartition_Hard_Disk/18_Gparted_Applied.png)

### Restart Ubuntu

![19_Restart](../Images/002_How_to_Repartition_Hard_Disk/19_Restart.png)

### BIOS Boot Order Reversion

![20_BIOS_Order_Reversion](../Images/002_How_to_Repartition_Hard_Disk/20_BIOS_Order_Reversion.png)

### BIOS Save and Reboot

![21_BIOS_Order_Reversion_Save_Exit](../Images/002_How_to_Repartition_Hard_Disk/21_BIOS_Order_Reversion_Save_Exit.png)

### Check New Partition Size with command

![22_DF_Resized](../Images/002_How_to_Repartition_Hard_Disk/22_DF_Resized.png)

### Check New Partition Size with GParted

![23_GParted_Resized](../Images/002_How_to_Repartition_Hard_Disk/23_GParted_Resized.png)
