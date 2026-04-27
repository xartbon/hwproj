# Simple Linux project HW

Steps to build and install

Resolve dependencies:

- Install them with `sudo apt install build-essential automake autoconf`.

Clone the repository:

- `$ git clone https://github.com/xartbon/hwproj && cd hwproj`

Build:

- `$ ./autogen.sh`
- `$ ./configure`
- `$ make && sudo make install`

Run the program:

- `$ hwproj`
