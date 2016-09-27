### IEM_BigFixInstallation

Steps to install the Big Fix Installation or IEM "IBM End Point Manager"


http://support.bigfix.com/bes/release/9.5/patch2/?cm_mc_uid=14745911776914619207812&cm_mc_sid_50200000=1469006451

The server has to be installed on the RHEL only.
Server
Operating System    Version     Architecture    Build Number    Download
Windows     Server 2008 SP1 (or greater)    x86_64  56  Download
Red Hat Enterprise Linux    6, 7    x86_64  56  Download

#####  This wiki is about installing on the RHEL server

Install the sudoers to the user.

Has to be installed as 'root'

Prerequisites:

        libstdc++.i686

        pam.i686

        libpng12.x86_64

sudo yum install pam.i686
sudo yum install libpng12

#####  Install the server

sudo ./install.sh


At this time - I am logged in as root.
Installation was complete
