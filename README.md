#The One Script#
This script will set up an nginx web server displaying a static html page containing:
- Kernel Release
- Operating System
- Date
- Number of Installed Packages
This updates the first time the script is run, and then every day at 5 am.

This script will also configure a ufw firewall only allowing http and ssh traffic from anywhere. (SSH rate limiting enabled)

##Requirements##
* The script must be run with sudo or as root.

Example: Running the script from within the same directory.
```
sudo ./the_one_script
```

Example: Running the script from a different directory.
- ie. If you have cloned this repository into /home/arch/server-start, and you want to run the script without navigating to that folder,you could run the following command:
```
sudo /home/arch/server-start/the_one_script
```

