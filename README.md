# i3-gaps-popos
This is a fork of i3-gaps-deb to run on Pop_!OS. It simply skips the sources check since those are already maintained on Pop_!OS.   

Tool to create and install Pop_!OS packages of _i3-gaps_.

I highly recommend installing i3 beforehand and upgrading with this tool to i3-gaps after installing and running.

## How does it work?
It uses the newest stuff from [here](https://github.com/Airblader/i3),
makes some modifications (only if necessary for the _building step_)
and finally produces common Debian packages.

## What's the purpose?
_i3-gaps_ simply does not exist in Debian (so far).

## How do I use it?
    $ git clone https://github.com/swip3798/i3-gaps-popos.git
    $ cd i3-gaps-popos
    $ ./i3-gaps-deb
    $ # Follow the interactive prompts.

## Works for what?
  - Pop_!OS 21.10
  - Probably on older versions as well

## Credits
Thanks to [stapelberg](https://github.com/stapelberg) for creating
[i3](http://i3wm.org/) and [Airblader](https://github.com/Airblader)
for the _gaps part_  (...and of course to _anyone else_ contributing to _i3_).

## Beer
Hey, I'm [thirsty](http://gunbomber.org/donation.html) like hell... _;-)_
