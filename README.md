# nvidia

# nvlink
- centos 7.9 安装驱动命令
- wget https://www.mellanox.com/page/mlnx_ofed_eula?mtag=linux_sw_drivers&mrequest=downloads&mtype=ofed&mver=MLNX_OFED-5.4-3.1.0.0&mname=MLNX_OFED_LINUX-5.4-3.1.0.0-rhel7.9-x86_64.tgz
- scl enable devtoolset-8  "./mlnxofedinstall --force --skip-distro-check --add-kernel-support --without-fw-update --ovs-dpdk --distro rhel7.9"
