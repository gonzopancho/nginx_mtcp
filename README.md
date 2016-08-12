# nginx_mtcp

================================================================================
 nginx version
================================================================================
Documentation is available at http://nginx.org



================================================================================
 mTCP version
================================================================================

nginx_sample.conf is a sample configuration.

$ export RTE_SDK=$work_dir/mtcp/dpdk-16.04/
$ export RTE_TARGET=x86_64-native-linuxapp-gcc

$ export MTCP_PATH=${mtcp_path}
	e.g. export MTCP_PATH=$work_dir/mtcp
$ export DPDK_PATH=${dpdk_path}
	e.g. export DPDK_PATH=#work_dir/mtcp/dpdk
	
$ ./configure --with-mtcp && make
