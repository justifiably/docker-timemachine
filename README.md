Yet another Timemachine docker instance.

Adds /etc/netatalk as a volume so that additional shared directories,
quotas, etc, can be added.  I prefer to map a separate network volume
for each backed up mac.

Ideas/scripts from: 

* lvlie/timeachine
* arve0/timemachine

