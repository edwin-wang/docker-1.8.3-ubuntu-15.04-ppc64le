# docker-1.8.3-ubuntu-15.04-ppc64le
Docker 1.8.3 binary for Ubuntu 15.04 ppc64le

Might need add soft link for libdevmapper.so.
e.g. ln -s /lib/powerpc64le-linux-gnu/libdevmapper.so.1.02.1 /lib/powerpc64le-linux-gnu/libdevmapper.so.1.02 && ldconfig
