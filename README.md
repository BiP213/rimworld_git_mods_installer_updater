# RimWorld Mods Updater ![](https://img.shields.io/badge/License-GPLv3-blue.svg) [![python](https://img.shields.io/badge/Python-3.10-3776AB.svg?style=flat&logo=python&logoColor=white)](https://www.python.org)

Python scripts for installing/updating RimWorld mods that have public git repositories.

## Installation

- Extract all `.py` files and `launch_mod_updater.bat` [Windows] or `launch_mod_updater.sh` [Linux] to `/RimWorld/Mods` folder

## Usage

- Open a terminal in `/RimWorld/Mods` folder  
- Run:
```
python ./rimworld_git_mods_installer_updater.py
```
> In some linux distributions you have to specify python version:
```
python3 rimworld_git_mods_installer_updater.py
```

## Updating using multiple instances

To split the mod list in multiple terminal instances, run it using the specific launcher for your OS that you extracted.  

> If you're on Linux, you must make `launch_mod_updater.sh` executable by running this command:
```
chmod +x launch_mod_updater.sh
```

You are able to modify it and define how many instances should be used.  
As it is, it launches 5 instances and splits my mod list (183 mods so far).  

Adjust it to your own needs! :)
