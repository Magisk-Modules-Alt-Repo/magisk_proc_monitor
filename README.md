# Magisk Process Monitor Tool (Dynamic Mount)

- Simple tool for monitoring app process start and allow modules to run script in app process namespace without inject into app process
- Every [dynmount.sh](./dynmount.sh) in module folder will be run when an app process start, before and after enter the mount namespace of app process (`prepareEnterMntNs` and `EnterMntNs`)
- You can dynamically mount and unmount something which only apply for that app process when `EnterMntNs`
- <https://github.com/Magisk-Modules-Alt-Repo/data_isolation_support> is a good example module.

## Links:

- Source code: https://github.com/HuskyDG/magisk_proc_monitor
