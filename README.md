# machineAccountQuota

This module will try to get the Machine Account Quota from the domain attribute ms-DS-MachineAccountQuota.
If the value is superior to 0, it opens new paths to enumerate further the target domain.
It is based on the impacket libraries.
