###Question 1:
```
# lxc-start -n c0
lxc-start: cgmanager.c: cgm_setup_limits: 1378 call to cgmanager_set_value_sync failed: invalid request
lxc-start: cgmanager.c: cgm_setup_limits: 1381 Error setting cgroup cpuset:lxc/c0 limit type cpuset.cpus
lxc-start: start.c: lxc_spawn: 952 failed to setup the cgroup limits for 'c0'
lxc-start: start.c: __lxc_start: 1121 failed to spawn 'c0'
lxc-start: lxc_start.c: main: 341 The container failed to start.
lxc-start: lxc_start.c: main: 345 Additional information can be obtained by setting the --logfile and --logpriority options.
```