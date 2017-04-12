### Goal
  1. users only need to run a shell script inside `Ubuntu 16.04.2 amd64` operating system on their own PC, and 'appifi development environment' will be ok after reboot.

### Configuration
+ **Host PC Related**
  - Architecture: X86
  - OS: Windows 7 ultimate 64bit
  - CPU: Intel(R) Core(TM) i3-4160 CPU @ 3.60GHz
  - Memory: 8.00GB
  - VMware: VMware Workstation 12 Pro
+ **Default Parameters in VMware** (develop environment)
  - CPU: 1 CPU 4 Core
  - Memory: 2G
  - Network: Bridge
  - Hard disk: 80G
  - Others: Default
+ **appifi-system Related**
  - OS: Ubuntu 16.04.2 amd64 Desktop

### Procedure
+ Run Ubuntu 16.04.2
+ Open shell
+ Download install-appifi.sh<p>
  `wget https://raw.githubusercontent.com/JiangWeiGitHub/appifi-system/master/amd64/pc/ubuntu-16-04-2-amd64/install-appifi.sh`<p>
+ Run install-appifi.sh<p>
  `chmod 755 ./install-appifi.sh`<p>
  `./install-appifi.sh`<p>
  - Install avahi with apt-get
  - Install Nodejs
  - Install docker
  - Enable & Disable some service with systemctl
  - Clean apt packages & tmp folder
+ Reboot system
+ Done
