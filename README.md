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

## Important things to know

The hosts to backup should be accessed once manuelly before the
backups could take place. Because SSH will ask "Are you sure you want
to continue connecting" when it does not know the host.


## Authors and history

* 20150406 Created by JF Gigand <jf@geonef.fr>
