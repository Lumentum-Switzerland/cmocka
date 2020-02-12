CMocka 1.1.3 Lumentum extensions

Requirements:
sudo apt-get install cmake

Installation:
cmake -DCMAKE_TOOLCHAIN_FILE=cmocka-1.1.3/cmake/Toolchain-cross-m32.cmake cmocka-1.1.3/ -DCMAKE_INSTALL_PREFIX=/usr
sudo make install
