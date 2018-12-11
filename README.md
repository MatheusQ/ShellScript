# ShellScript
Scripts that I developed to automate tasks on Linux

## upgradeRPi3
I need a initram image to be able to use and to boot the system in a external HD with LVM partitions. The Operation System Raspbian (for Raspberry Pi 3 B) haven't a initram image native, and so, when I update the system, the initram image that I created don’t update automatically. This is a problem when the kernel is updated, because the current kernel keep different than kernel that the initram image was created. This script solves the problem.
