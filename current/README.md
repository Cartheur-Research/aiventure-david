## Setting-up the bipedal robot with linux

For reference, the [XU-4](https://magazine.odroid.com/odroid-xu4) manual is available.

1. Prepare the odroid with the ubuntu 22.04.6 [image](https://odroid.in/ubuntu_22.04lts/XU3_XU4_MC1_HC1_HC2/) provided by hardkernel
2. [install](https://wiki.odroid.com/odroid-xu4/getting_started/os_installation_guide?redirect=1) onto the eMMC
    - [this](https://forum.odroid.com/viewtopic.php?f=96&t=44932) is nice but need time to understand how the u-boot fusing works
3. Ensure that an account for `cartheur` is created for `ssh`
4. install software

`sudo apt install git espeak alsa-utils build-essential mplayer gcc automake autoconf libtool libasound2-dev`

5. Ensure connecting to the wifi, in lieu of connecting a cable is an optional usecase, with a USB adapter. In this case, a tp-link [T2U](https://www.tp-link.com/us/support/download/archer-t2u/)