# libtinkerforge

## Introduction

This project offers a shared library for Tinkerforge's C/C++ bindings [1].

The Tinkerforge bindings (everything under ./tinkerforge except for tinkerforge.h) 
were released under public domain. [2]


## Installation

### Tarball 
	1. Download a tarballed release.
	2. Extract its conents (tar -zxvf <tarball name>).
	3. Chnage into the directory.
	4. ./configure 
	5. make 
	6. Run one of the following commands
		a. make install # as root; e.g. sudo make install
		b. checkinstall # as root; e.g. sudo checkinstall
	7. ldconfig # as root; e.g. sudo ldconf 

### Git Repository
	1. Clone the repository.
	2. Chnage into the directory.
	3. ./autogen.sh # requires autotools to be installed
	4. ./configure
	5. make 
	6. make install # as root; e.g. sudo make install
	7. ldconfig # as root; e.g. sudo ldconf 

[1]: http://www.tinkerforge.com/en/doc/Software/API_Bindings_C.html
[2]: http://www.tinkerforge.com/en/home/what_is_tinkerforge/
