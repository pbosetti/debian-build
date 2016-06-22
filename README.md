# Debian building machine

Provides make, GCC, Clang/LLVM, ruby and some gems.

# Build image

    docker build -t debian-build .

# Run image

    docker run -it --name debian-build -h dbm -v `pwd`:/root/build debian-build
