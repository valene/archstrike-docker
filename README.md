##Intro##

This repo contains script for generating an archstrike docker image.

The script is a modified version of the original archlinux mkimage-arch.sh.


#Instructions#

The instructions are similar to archlinux docker image generation. 

get a copy of pacman.conf and rename it to mkimage-arch-pacman.conf 

place both the scripts in the same directory and run. 

or just refer to archstrike wiki for docker image build.

    $ chmod 755 mkimage-archstrike.sh
    $ cp /etc/pacman.conf ./mkimage-arch-pacman.conf
    $ ./mkimage-arch.sh
    # docker run -t -i archstrike-personal /bin/bash
