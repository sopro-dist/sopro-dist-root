sopro-dist-root
====

The root repository including all SoPro's *-dist submodules

sopro-dist-root#0.1.0 includes:  
SocietyPro/html5-pollmaster#0.1.0  
SocietyPro/html5-group-manager#0.1.0

Usage
=====

You probably do not need to clone this.

Since this repo is in the .gitmodules for Cambrian-src, you should probably do this instead:

    $ git clone --recursive https://github.com/SocietyPro/Cambrian-src.git

If you already have a Cambrian-src folder, you can instead go there and run:

    $ git submodule update --init --recursive


at which point you will have a sopro-dist-root folder within your Cambrian source code, ready to build and include the assets.


Development Usage
=================

Clone this repo into ./sopro-dist-root:

    $ git clone --recursive https://github.com/sopro-dist/sopro-dist-root.git#0.1.0
    $ cd sopro-dist-root

Download the releases that are included as submodules:

    $ git submodule update --init --recursive
  
