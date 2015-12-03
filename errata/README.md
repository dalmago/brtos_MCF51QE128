# Errata
Files that have to be modified when creating a new USBDM project on eclipse,
to make it work with the MCF51QE128 microcontroller.

* _vectors.c_ : security_information and interupt vectors corrected
* _system.c_ : "system.h" included
* _mcf51qe128.c_ : "@" removed from register address
