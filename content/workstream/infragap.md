---
title: "Collection of infrastructure gaps"
draft: false
---

* Zero trust package builds: Suggested by Allan Jude
  Here is a talk on the general topic: Zero trust CI/CD pipeline – Amit Dube –
  [XConf Europe 2022](https://youtu.be/Z0JDOrGJYjY )
* Ports automation: At minimum, can we automate the testing of patches? 
* Layered repo support with Poudriere/pkg: Looking for a move towards something
  more like Ubuntu PPAs
* Enterprise CA: There is no canonical playbook for how CAs are managed in
  FreeBSD. Here are open issues:
  * https://bugs.freebsd.org/bugzilla/show_bug.cgi?id=256902
  * https://bugs.freebsd.org/bugzilla/show_bug.cgi?id=256923
  * https://bugs.freebsd.org/bugzilla/show_bug.cgi?id=253060
  * https://bugs.freebsd.org/bugzilla/show_bug.cgi?id=269473
  * 09/07/2023
    * advanced this as it seems relatively low effort and b/c Zero Trust Builds
      and Ports Automation are not actionable by the WG right now
    * Similar to AD/DNS, the next step here quick call – what’s open, what needs
      to be done, and we need someone who can get patches committed.
    * Greg to take action here to work with Joe/Ed/Others to figure out who is
      best person to help
* Reproducible builds: Suggested by Allan Jude
* SBOM for FreeBSD: Suggested by Allan Jude

