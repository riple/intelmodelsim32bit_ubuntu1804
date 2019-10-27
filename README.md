# intelmodelsim32bit_ubuntu1804
32bit packages that should be installed to run 32bit Modelsim on 64bit Ubuntu1804:

sudo apt-get install libc6:i386 libncurses5:i386 libstdc++6:i386

sudo apt-get install libx11-6:i386 libxtst6:i386 libxft2:i386

sudo apt-get install gawk

sudo apt-get install gcc-multilib g++-multilib


Add modelsim executables to PATH:

export PATH=/path/to/modelsim_ase/linuxaloem/:$PATH
export MTI_HOME=/path/to/modelsim_ase/
