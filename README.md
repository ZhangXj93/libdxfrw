libdxfrw
==========

libdxfrw is a free C++ library to read and write DXF files in both formats, ascii and binary form.
 It is licensed under the terms of the GNU General Public License version 2 (or at you option
any later version).


If you are looking for general information about the project, check our website:
http://sourceforge.net/projects/libdxfrw


WARNING: This project is a fork to add a makefile for some of our downstream project's in LibreCAD.
==========

Building and installing the library
==========

mkdir build
cd build
cmake ..
make 
make install

For non-debug version:
==========

mkdir release
cd release
cmake -DCMAKE_BUILD_TYPE=Release ..
make 
make install



== Example usage of the library ==

See how we use it in LibreCAD V3 : https://github.com/LibreCAD/LibreCAD_3/tree/master/lcDXFDWG/lcDXF

