# The One Script
### This script will: 
#### 1) Set up an nginx web server displaying a static html page containing:

- Kernel Release
- Operating System
- Date
- Number of Installed Packages

Note: This html page updates the first time the script is run, and then every day at 5 am.


#### 2) Configure a ufw firewall that only allows http and ssh traffic (ssh rate limiting enabled).

## Requirements
* The script must be run with sudo or as root.


## Running the script
Once this repository has been transferred to your machine you may choose to run the command to start the script from within the same directory as the script, or from a different directory.

Example 1: Running the script from within the same directory.
```
sudo ./the_one_script
```

Example 2: Running the script from a different directory.
- ie. If you have cloned this repository into /home/arch/server-start, and you want to run the script without navigating to that folder,you could run the following command:
```
sudo /home/arch/server-start/the_one_script
```

