---
title: "Bhyve and jails management tooling"
draft: false
---

Within this group and out of the original feedback, one work stream emerged for
specifying and building a "definitive bhyve+jail management toolset" to be added
to FreeBSD base.

The main pain points mentioned in initial communications:
* High manual effort required to get jails running
* Lack of resources in maintaining ports providing utilities (i.e. run by one
  person) and some of them even not maintained and developed further at all
* Insufficient oversight and management of needs and requirements, lack of
  progress
* Low visibility and insufficient marketing of available technology options to
  enterprise customers

## Requirements Collection

We have established an initial [Product Requirements Document](https://docs.google.com/document/d/1_0LEJqHT6v089YUI3PTRnNCLH8L14UZclvs2x_YWjtY/edit#heading=h.uviovcski3bj) which
serves as documentation for a minimum viable product (MVP).

## Ongoing Activities

* 13 Oct 2023: Call w/ stakeholders who originally reported gaps
* Working on a communications plan, covering
  * relevant community stakeholders
  * FreeBSD Forum
  * LinkedIn
  * Mailing list
* Further updating PRD in terms of
  * Risks
  * requirements so far
* Update wrike
  * roadmap on how an actual implementation of an MVP could look like

## Updates

* 06 Oct 2023: initial call scheduled, planning
* 05 Oct 2023: presentation of Enterprise Work Group and BHYVE/jail work stream
  at the weekly bhyve developers/users call
* 04 Oct 2023: Chris Moerz onboarded as project lead

## Difficulty

* Establishing MVP requirements that can go into base
* Prioritization
* Identifying development resources

## Dependencies

* BHYVE development
* 14.0 release schedule

## Volunteers

* Chris Moerz (freebsd AT ny-central.org)