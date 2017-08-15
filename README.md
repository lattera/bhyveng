bhyveng
=======

Bhyve Next Generation (bhyveng) is a second-generation version of
bhyve.

Plans
-----

1. Support libucl for configuration files
1. Support "obfuscation mode." Obfuscation mode will allow bhyve to
   obfuscate itself such that untrusted code in untrusted virtual
   machines (ie, malware) cannot identify the hypervisor.
1. Support "hypervisor emulation mode." Hypervisor emulation mode will
   allow bhyve to emulate the behavior of other hypervisors such that
   untrusted code in untrusted virtual machines (ie, malware) thinks
   it is running in a different hypervisor (ie, KVM on Linux or VMWare
   ESXi).

Sponsors
--------

1. G2, Inc
