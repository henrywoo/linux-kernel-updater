
# Latest updates

- Updated for Ubuntu 19.04


This is to maintain a workable version of Ukuu as the original Ukuu goes to paid version. If you have money, please support [Ukuu](https://teejeetech.in/2019/01/20/ukuu-v19-01/) as possible as you can. If not, you can manually build with this repo.

### Ubuntu Kernel Update Utility (Ukuu)

This is a tool for installing the latest mainline Linux kernel on Ubuntu-based distributions.

![](https://2.bp.blogspot.com/-76C_l3BcJyg/WNdzTpSoiKI/AAAAAAAAGKs/xOvB-LCH2cYiDpdbqWkeOLhY9I7TVACJwCLcB/s1600/ukuu_main_window.png)

### Features

*   Fetches list of kernels from [kernel.ubuntu.com](http://kernel.ubuntu.com/~kernel-ppa/mainline/)
*   Displays notifications when a new kernel update is available.
*   Downloads and installs packages automatically

### Screenshots

![](https://2.bp.blogspot.com/-76C_l3BcJyg/WNdzTpSoiKI/AAAAAAAAGKs/xOvB-LCH2cYiDpdbqWkeOLhY9I7TVACJwCLcB/s1600/ukuu_main_window.png)
_Main Window_

![](https://2.bp.blogspot.com/-ATv4vsOVOnc/WNdztEZHJNI/AAAAAAAAGKw/1pOIuyu8ITo4z8mnMK6MfCZ3T_Nd4gQNQCLcB/s1600/ukuu_settings.png)
_Settings Window_

![](https://4.bp.blogspot.com/-Y-1zhHcpk1M/WNd42_ybTyI/AAAAAAAAGLE/gLaBdWpoh54OGrvF81Ka1bCVJjZ0WqKrQCLcB/s1600/ukuu_console_options.png)
_Console Options_

### Installation

#### Debian & Other Linux Distributions
This application fetches kernels from [kernel.ubuntu.com](http://kernel.ubuntu.com/~kernel-ppa/mainline/) which are provided by Canonical and meant for installation on Ubuntu-based distributions. These should not be used on Debian and other non-Ubuntu distributions such as Arch Linux, Fedora, etc.


### Downloads & Source Code 
Ukuu is written using Vala and GTK3 toolkit. Source code and binaries are available from the [GitHub project page](https://github.com/henrywoo/linux-kernel-updater).

### Build instruction

#### Ubuntu-based Distributions (Ubuntu, Linux Mint, Elementary, etc)  

 in a terminal window:  

    sudo apt-get install libgee-0.8-dev libjson-glib-dev libvte-2.91-dev valac
    git clone https://github.com/henrywoo/linux-kernel-updater.git
    cd linux-kernel-updater
    make all
    sudo make install
