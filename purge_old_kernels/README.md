# Purge old kernels script

Script dows exactly what it's name says :-) 
Works well with Ubuntu. Regarding other deb-based distros - I have no idea.    

# Usage:

* Run with *sudo*
* This script will ALWAYS keep the currently running kernel
* Default is to keep 1 more, user overrides with --keep N
* Any unrecognized option will be passed straight through to apt-get
* I've add -yqq to deafault  apt-get options 

Originnaly This script was taken from [Dustin Kirkland's repo](https://code.launchpad.net/~bikeshed/bikeshed/trunk)