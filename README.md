# SYSCONF profile 'sysconf.backuppc': BackupPC software + Gitted config

* Central URL: git@github.com:geonef/sysconf.backuppc.git


## Usage instructions

* For more information, see: http://gitted.io/

Integrate this Sysconf profile using git subtree:
```
git subtree add sysconf.backuppc git@github.com:geonef/sysconf.backuppc.git master
```

Then, update the ```deps``` file to tell Sysconf to use it:
```
echo sysconf.backuppc >>actual/deps
```

## Authors and history

* 20150406 Created by JF Gigand <jf@geonef.fr>
