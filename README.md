# Reverse shell in kernel module

<p>
Load this module to create a reverse shell. </ br>
This module can be loaded in docker containers as long as it has the cap_sys_module capability, usually found in containers that use the --privileged flag.
</p>

# Load module

```
# Compile the code with the follow command:
$ make install

# Load module
$ insmod reverseshell_module.ko

```