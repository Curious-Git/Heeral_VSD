# Heeral_VSD
Weekly basis progress documentation of the VSD tapeout curse

VSD Hardware Design Program
Tools Installation
All the instructions for installation of required tools can be found here:
System Requirements

    6 GB RAM
    50 GB HDD
    Ubuntu 20.04 or higher
    4 vCPU

### TOOL CHECK
## Yosys

    $ sudo apt-get update
    $ git clone https://github.com/YosysHQ/yosys.git
    $ cd yosys
    $ sudo apt install make               # If make is not installed
    $ sudo apt-get install build-essential clang bison flex \
        libreadline-dev gawk tcl-dev libffi-dev git \
        graphviz xdot pkg-config python3 libboost-system-dev \
        libboost-python-dev libboost-filesystem-dev zlib1g-dev
    $ make config-gcc
    #Yosys build depends on a Git submodule called abc, which hasn't been initialized yet. You need to run the following command before running make
    $ git submodule update --init --recursive
    $ make 
    $ sudo make install


<img width="734" height="189" alt="yosys_installed" src="https://github.com/user-attachments/assets/d85daa16-8af8-440b-9a5e-4c9e45271bf9" />

## Iverilog
    
    $ sudo apt-get update
    $ sudo apt-get install iverilog





<img width="730" height="243" alt="iverilog_installed" src="https://github.com/user-attachments/assets/8a718bbf-48fb-4a28-9eaf-6ace488b1e14" />

## gtkwave

    $ sudo apt-get update
    $ sudo apt install gtkwave




<img width="1764" height="715" alt="gtkwave_installed" src="https://github.com/user-attachments/assets/3a9bbc67-f748-4c95-9386-5bad74a08631" />



