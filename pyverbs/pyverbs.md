rpm -ivh http://mirror.centos.org/centos/8/PowerTools/x86_64/os/Packages/python3-Cython-0.28.1-3.el8.x86_64.rpm
yum install python3-devel
yum install libudev-devel
yum install pkgconfig valgrind-devel libudev-devel cmake libnl3-devel python3-devel python3-docutils

 ./build/bin/run_tests.py -v --dev qedr0
PYTHONPATH='/opt/rdma-core/build/python' exec '/usr/bin/python3' pyverbs/examples/ib_devices.p
