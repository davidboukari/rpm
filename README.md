# rpm


* Which package contains this file
``` 
rpm -qf /etc/logrotate.d
logrotate-3.8.6-19.el7.x86_64
```


* List files in installed rpm
```
rpm -ql logrotate-3.8.6-19.el7.x86_64
/etc/cron.daily/logrotate
/etc/logrotate.conf
/etc/logrotate.d
/etc/rwtab.d/logrotate
/usr/sbin/logrotate
/usr/share/doc/logrotate-3.8.6
/usr/share/doc/logrotate-3.8.6/CHANGES
/usr/share/doc/logrotate-3.8.6/COPYING
/usr/share/man/man5/logrotate.conf.5.gz
/usr/share/man/man8/logrotate.8.gz
/var/lib/logrotate
/var/lib/logrotate/logrotate.status
```

* extract an rpm
```
rpm2cpio php-5.1.4-1.esp1.x86_64.rpm | cpio -idm
```
