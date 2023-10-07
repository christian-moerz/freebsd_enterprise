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
  * HPC, AI workloads: Many in these industries like FreeBSD but need more
    native support in nvidia. security is key for these workloads - train models
    on private data, then host on fbsd to benefit from zfs, security, etc. 
    protecting the data models is key
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
  * 09/07/2023
    * Earlier last week, we spoke with a developer with significant experience
      working with the Samba team. They will email the Samba team and offer to
      help get the patches upstream.
    * One of the things the Samba team, and other project, have asked for is
      GitHub Actions with FreeBSD to help automate things. The FreeBSD
      Foundation is going to connect with people at GutHub and Microsoft to try
      to get this in place.
    * Greg created a Wrike project with the above three tasks and will invite
      volunteers to join.
* eBPF: https://ebpf.io/ 

