# RISC-V-Tapeout-Program---VSD

In this [program](https://www.vlsisystemdesign.com/soc-labs/), we learn to design a System-on-Chip (SoC) from basic RTL to GDSII using open-source tools. 

<details>
	<summary>Week 0 - Tools Installation </summary>
	
# Day 0 - Tools Installation
## Yosys
```
$ git clone https://github.com/YosysHQ/yosys.git
$ cd yosys 
$ sudo apt install make (If make is not installed please install it) 
$ sudo apt-get install build-essential clang bison flex \
    libreadline-dev gawk tcl-dev libffi-dev git \
    graphviz xdot pkg-config python3 libboost-system-dev \
    libboost-python-dev libboost-filesystem-dev zlib1g-dev
$ git submodule update --init --recursive
$ make 
$ sudo make install
$ yosys
```
<img width="575" alt="yosys" src="Images/Week 0/yosys.png">

## Iverilog
```
$ sudo apt-get install iverilog
$ iverilog -v
```
<img width="702" alt="iverilog" src="Images/Week 0/iverilog.png">

## GTKWave
```
$ sudo apt update
$ sudo apt install gtkwave
```
<img width="1008" alt="gtkwave1" src="Images/Week 0/gtkwave.png">

## Ngspice
```
$ sudo apt update
$ sudo apt install ngspice
```
<img width="702" alt="iverilog" src="Images/Week 0/ngspice.png">

## Magic VLSI
```
$ sudo apt-get install m4
$ sudo apt-get install tcsh
$ sudo apt-get install csh
$ sudo apt-get install libx11-dev
$ sudo apt-get install tcl-dev tk-dev
$ sudo apt-get install libcairo2-dev
$ sudo apt-get install mesa-common-dev libglu1-mesa-dev
$ sudo apt-get install libncurses-dev
$ git clone https://github.com/RTimothyEdwards/magic
$ cd magic
$ ./configure
$ make
$ make install
```

<img width="1008" alt="magic" src="Images/Week 0/magic.png">

</details>
