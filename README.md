This is a generated Python package, made by:

  ncs-make-package --service-skeleton python-and-template \
                   --component-class main.Main day1_config

It contains a dummy YANG model which implements a minimal Service
and an Action that doesn't really do anything useful. They are
there just to get you going.

This Day 1 configuration template currently configures:

Hostname

Syslog

Domain DNS

SNMP

NTP

ISIS configuration(net id calculated from ID pool using resource manager)

Prefix SID for SR(calculated from ID pool using resource manager)

How to use:
```
day1_config name test dns 208.67.222.222 ntp 8.8.8.8 id_pool isis-pool 
deviceconfig <device name> 
hostname <hostname>
loopback 0
interface 0/0/0/0
commit
```

