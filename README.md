# midi2hydrogen.pl

#    ____________________________________________________________________
#   /                                                                    \
#  |               ____  __      ___          _____  /     ___    ___     |
#  |     ____       /  \/  \  ' /   \      / /      /__   /   \  /   \    |
#  |    / _  \     /   /   / / /    /  ___/  \__   /     /____/ /    /    |
#  |   / |_  /    /   /   / / /    / /   /      \ /     /      /____/     |
#  |   \____/    /   /    \/_/    /  \__/  _____/ \__/  \___/ /           |
#  |                                                         /            |
#  |                                                                      |
#  |   Copyright (c) 2007                     Herve Masson, MindStep SARL |
#  |   rvmindstep@users.sourceforge.net                                   |
#   \____________________________________________________________________/


midi2hydrogen.pl - MIDI file conversion script for hydrogen (hydrogen-music.org)

==> Read the usage message below for more info

**Note:** was created on ubuntu 7.x using perl 5.8, with the additional CPAN
packages XML-Simple and MIDI-Perl

**To use in MX Linux 21 (debian 11)**
Install:

    sudo apt-get install libmidi-perl

    sudo apt-get install libxml-simple-perl


Ideas/TODOs:

- some quantization would probably be useful
- detect identical patterns (that's tricky)
- load instruments from multiple kits
- ~home/.midi2hydrogen.cfg config file instead of options
- find a way to implement some midi controls (volume, pan,...)

To convert a midi file to h2song (in the same place where is the program -you need place your midi file there-):

    perl midi2hydrogen.pl input.midi output.h2song

Source:

[Risolto] [Audio] midi2hydrogen: importare file midi in Hydrogen
https://forum.ubuntu-it.org/download/file.php?id=106874&sid=da03a111e5c2a7d7024454f77036782f
