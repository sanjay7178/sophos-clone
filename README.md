# sophos-clone
sophos client webpage clone with http post request method to capture the http post request packets using wireshark
## REQUIRED!
- A Linux operating system installed in VMWARE or VIRTUAL BOX and set the OS to bridged network mode in your respective Hypervisor.
- apache 2 to be installed
- git should be installed 
## Apache2
In UBUNTU/KALI_LINUX
```
sudo apt-get install apache2
```
## Git
```
sudo apt-get install git
```
## installation
```
sudo apt-get install apache2
sudo apt-get install git
git clone https://github.com/sanjay7178/sophos-clone.git
sudo mv sophos-clone sophos
sudo mv sophos /var/www/sophos
sudo systemctl start apache2
sudo systemctl stop apache2
```
##Apache2 web server running status
```
sudo systemctl status apache2
```
