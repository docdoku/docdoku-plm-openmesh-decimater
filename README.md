# DocDoku OpenMesh decimater

## Compiling requirements

To compile the decimater, you need to install a c++ compiler, Qt sdk

For Ubuntu / Debian users :

    apt-get install cmake g++ qt-sdk

First step is to install OpenMesh in release mode.
Download the archive from [this page](http://www.openmesh.org/media/Releases/3.2/OpenMesh-3.2.tar.gz),
Once you have downloaded the tar.gz file just uncompress and build it with following commands:
```
tar -xvf [tar.gz file]
cd [uncompress folder]
mkdir build
cd build 
cmake -DCMAKE_BUILD_TYPE=Release .. && make install;
```

Once OpenMesh installed, the decimater can be built :

    mkdir build && cd $_;
    qmake ../src/OpenMeshDecimater.pro && make
    
