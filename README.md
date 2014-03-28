Flymir LuaDist Bootstrap
=================
This repository contains an installation script that will bootstrap a self contained LuaDist distribution. To build LuaDist please make sure your system has git, CMake 2.8 and a compiler tool-chain available. On Ubuntu this requires cmake 2.8 and build-essential. This build will take quite a while to compile, please be patient.

Checking out of git and run:

    git clone git://github.com/Flymir/bootstrap.git
	cd bootstrap
    ./bootstrap
   
Once the installation finishes the folder should contain a fully versioned LuaDist distribution in _install subdirectory:

    cd _install
    ./bin/luadist list # lists installed modules
    ./bin/luadist search # lists online repository
    ./bin/luadist install luaexpat # installs luaexpat     
	
You can move and rename the _install folder as desired.
