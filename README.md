### A script that cleanes your linux machine

* This is a script that frees up space
* This script cleanes logs, journals, and cache

### Cloning this repo

* to clone this repository, make sure you have `git` install, usually it comes pre-installed in many distros, type this command to clone this repo
-     git clone https://github.com/frostycoding/clean_script.git
------
* After you cloned this repo, go into that directory
-     cd clean_script

### Using my script

* There are two scripts that you can use, the `clean_arch` script is for arch-based distros.
* The `clean_debian` is for debian-based distros.
-----
* After you choose the script for your distro, to use it, we need to make it an executable file
*     chmod +x clean_debian clean_arch
-----
* After that you can run your file for your distro, in this case, I am in an arch-based distro, So I will type
*     ./clean_arch
-----
* If your in a debian-based distro, type
*     ./clean_debian

### Accessing the script from any directory

* So, if you want to access this script from any directory, we need to copy the script for your distro to another folder
*     cp [SCRIPT_FOR_YOUR_DISTRO] /usr/local/bin/clean
-----
* Now whenever you run the command `clean` it cleanes all the cache, journal, and logs.
