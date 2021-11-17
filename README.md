EECS 280 Setup Script
======================
By Andrew Kerr <kerrand@protonmail.com>

Set up EECS 280 project starter files with one command.

A basic shell script that:
- Downloads all the starter files for the 280 project you specify,
- removes all `.starter` files suffixes,
- deletes junk files, and
- moves your files to a custom-named folder (optional).


#### Install the Script
```
git clone https://github.com/andkerr/280setup.git
```

#### Run to Download Files
```
cd 280setup                                     # navigate to the cloned repository

./280setup <project name> [folder name]      # run to install starter files
```

#### Usage Instructions
```
usage: ./280setup <project name> [folder name]
       Project name must be typed as given in the
       wget url in the EECS 280 spec
       Examples: p2-cv, p1-stats
```

For example, to install project 5 starter files:
```
./280setup p5-ml
```

#### Relocate Downloaded Files Using `mv`
```
mv <starter file folder> path/to/another/directory
```

#### Disclaimer
This script has only been tested on EECS 280-recommended command line tools
(MacOS Terminal, WSL, Linux) and may not work on other systems.
