EECS 280 Setup Script
======================
Set up your EECS 280 starter files, pain free!

A basic shell script that:
- Downloads all the starter files for the 280 project you specify,
- removes all `.starter` files suffixes,
- deletes junk files, and
- moves your files to a custom-named directory (optional)


To install:
```
git clone https://github.com/andkerr/280test.git
```

To run:
```
cd 280setup # navigate to the cloned repo

./280setup # run to install starter files
```

Insructions:
```
usage: 280setup <project name> [directory]
       Project name must be typed as given in the
       wget url in the EECS 280 spec
       Examples: p2-cv, p1-stats
```

By Andrew Kerr <kerrand@protonmail.com>
