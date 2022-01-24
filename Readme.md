An example of using CMake with Rust.

[![Build Status](https://travis-ci.org/SiegeLord/RustCMake.png)](https://travis-ci.org/SiegeLord/RustCMake)

Try it!
~~~
mkdir build
cd build
cmake .. -DCMAKE_INSTALL_PREFIX=/tmp
make -j
make test -j
make doc -j
make install

cd examples
./example1
./example2
~~~