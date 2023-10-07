---
title: "Collection of feature gaps"
draft: false
---

* Cloud native / K8s: Important to future of FreeBSD to have an OCI runtime 
* AD/DNS integration: This is non-existent. In a large environment it is 
  impossible to email the DNS admin about every single change, therefore Active
  Directory makes heavy use of dynamic DNS updates authenticated via GSS-TSIG
  (requires Kerberos)
* Nvidia / GPU support: Zoran at Supermicro indicated that they have the ability
  to do tests, but they lack some Nvidia GPU drivers
* smbfs 2 and 3 driver in kernel: The current smbfs driver is 1.0, totally
  unusable these days 
* Kerberos: Heimdal base is old.
  Splitting of MIT Kerberos port into client and server, like in many Linux distros would be ideal. 
  * https://bugs.freebsd.org/bugzilla/show_bug.cgi?id=256677 
  * https://bugs.freebsd.org/bugzilla/show_bug.cgi?id=247940 
* OpenJDK: No upstream BSD port in OpenJDK
* Samba 4.x: Since the inception of their new VFS layer, it has got even harder
  for FreeBSD. Too many changes living now in downstream (port). FreeBSD core
  pillars of ZFS and network capability must be in sync with Samba's features to
  have great file hosting.
* eBPF: https://ebpf.io/ 



## Updates

## Difficulty

## Dependencies

## Volunteers