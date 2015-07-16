# perf-benchmark-bootable-vm
The primary goal of this project is to create a Bootable, portable ISO for benchmarking IO and network performance on hyperconverged systems.

Leveraging industry-standard IO performance toolkits for disk benchmarking and network performance:

1.  FIO
2.  iperf
3.  sockperf
4.  iftop
5.  ioping
6.  sysbench

The ISO will be a bootable pre-built Ubuntu-based ISO that will run performance tests on a guest VM.

## Requirements:
1.  Each guest will require a 20G disk attached to the VM.  The disk can be thin-provisioned, but is required for storing test files
2.  Preferably, internet access to distribute test results (if desired)

