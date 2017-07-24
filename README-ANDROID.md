```
mkdir build-android && cd build-android
cmake -DBUILD_SHARED_LIBS=OFF -DCMAKE_TOOLCHAIN_FILE=~/src/android-cmake/android.toolchain.cmake -DANDROID_STANDALONE_TOOLCHAIN=/opt/crystax-standalone-toolchain -DCMAKE_BUILD_TYPE=Release -DCMAKE_INSTALL_PREFIX=/opt/crystax-standalone-toolchain/sysroot/usr/ ..
make -j 5
sudo make install
```
