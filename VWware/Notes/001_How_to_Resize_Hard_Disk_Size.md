# How to Resize Hard Disk Size

- [How to Resize Hard Disk Size](#how-to-resize-hard-disk-size)
  - [Host change](#host-change)
    - [Power off Guest OS](#power-off-guest-os)
    - [Go to setting](#go-to-setting)
    - [Resizing HD](#resizing-hd)
    - [Repartition](#repartition)
    - [Result after operation](#result-after-operation)
  - [Guest OS Change](#guest-os-change)
    - [How to repartition Hard Disk](#how-to-repartition-hard-disk)

## Host change

### Power off Guest OS

![00_Host_Power_Off_Guest_OS](../Images/001_How_to_Resize_Hard_Disk_Size/00_Host_Power_Off_Guest_OS.png)

### Go to setting

![01_Host_Resize_Setting](../Images/001_How_to_Resize_Hard_Disk_Size/01_Host_Resize_Setting.png)

### Resizing HD

![02_Host_Resize_Expand](../Images/001_How_to_Resize_Hard_Disk_Size/02_Host_Resize_Expand.png)

### Repartition

The most tricky problem:

1. Not aware of this notification and think with change above, expansion is complete.
2. Even got it and want do repartition, but failed to bootup guest OS.
   ![03_Host_Resize_Repartition](../Images/001_How_to_Resize_Hard_Disk_Size/03_Host_Resize_Repartition.png)

### Result after operation

![04_Result_100G](../Images/001_How_to_Resize_Hard_Disk_Size/04_Result_100G.png)
![05_Garted_Run](../Images/001_How_to_Resize_Hard_Disk_Size/05_Garted_Run.png)
![06_Gparted_Unallocated](../Images/001_How_to_Resize_Hard_Disk_Size/06_Gparted_Unallocated.png)
![07_Gparted_Unable_to_Resize](../Images/001_How_to_Resize_Hard_Disk_Size/07_Gparted_Unable_to_Resize.png)

## Guest OS Change

### [How to repartition Hard Disk](002_How_to_Repartition_Hard_Disk.md)