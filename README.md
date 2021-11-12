EECS 280 Setup Script
======================
Set up your EECS 280 starter files, pain free!

A basic shell script that:
- Downloads all the starter files for the 280 project you specify,
- removes all `.starter` files suffixes,
- deletes junk files, and
- moves your files to a custom-named directory (optional).


To install:
```bash
git clone https://github.com/andkerr/280test.git
```

To run:
```bash
cd 280setup     # navigate to the cloned repository

./280setup <project name> [directory name]      # run to install starter files
```

Insructions:
```bash
usage: 280setup <project name> [directory]
       Project name must be typed as given in the
       wget url in the EECS 280 spec
       Examples: p2-cv, p1-stats
```

For example, to install project 5 starter files:
```bash
./280setup p5-ml
```

#### Disclaimer
This script has only been tested on the Bash shell, which is used by WSL, MacOS,
and many Linux distributions. It may not work on other systems.


By Andrew Kerr <kerrand@protonmail.com>
