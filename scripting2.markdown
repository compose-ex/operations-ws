###Question 2:
```
# lxc-start -n c1
lxc-start: cgmanager.c: cgm_setup_limits: 1378 call to cgmanager_set_value_sync failed: invalid request
lxc-start: cgmanager.c: cgm_setup_limits: 1381 Error setting cgroup memory:lxc/c1 limit type memory.memsw.limit_in_bytes
lxc-start: start.c: lxc_spawn: 952 failed to setup the cgroup limits for 'c1'
lxc-start: start.c: __lxc_start: 1121 failed to spawn 'c1'
lxc-start: lxc_start.c: main: 341 The container failed to start.
lxc-start: lxc_start.c: main: 345 Additional information can be obtained by setting the --logfile and --logpriority options.
```