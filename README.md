# The One Script
This script will set up an nginx web server and deploy a ufw firewall.

1. The nginx web server will display a static html page containing:
- Kernel Release
- Operating System
- Date
- Number of Installed Packages

This updates the first time the script is run, and then every day at 5 am.

The ufw firewall will only allow http and ssh traffic (ssh rate limiting enabled).

## Requirements
* The script must be run with sudo or as root.

Example 1: Running the script from within the same directory.
```
sudo ./the_one_script
```

Example 2: Running the script from a different directory.
- ie. If you have cloned this repository into /home/arch/server-start, and you want to run the script without navigating to that folder,you could run the following command:
```
sudo /home/arch/server-start/the_one_script
```

