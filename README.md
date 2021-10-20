# ssh-utils
Utility to ssh to a device that is connected directly to a network interface.
Maybe I'll add other useful things later.

## Setup
- Copy the scripts somewhere in the PATH
- Add the following to the top of your ssh-config: `Include /path/to/ssh-utils/interface-ssh-config`

## Usage
Just ssh to the interface like this: `ssh root@eth0`
