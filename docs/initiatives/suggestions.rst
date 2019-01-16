===============================
Suggestions for LFN Initiatives
===============================

Update Infra
------------

LFN Projects are using a Gerrit+Jenkins+Nexus infra that is both antequated and
expensive to maintain.  More modern open source projects tend to use Github based
infra like:

* Github - SCM
* CircleCI or TravisCI or other cloud based CI - CI
* Various artifact repo as a service services
* Github Issues - Bug tracking
* Github + Hugo + Netlify - Websites/doc sites

This subgroup will explore cross project how to POC, and perhaps migrate LFN
projects to such more modern infra.  

It is important to be clear: no community should change if it does not see benefit.

CII Badging
-----------

LNF Projects should work together to meet CII Badging requirements.

CII Badging covers many aspects of project quality along an increasing
difficulty scale from Passing to Silver to Gold. At the high end of the scale,
the requirements are exceptionally difficult (binary-reproducible builds, 2FA
for all commits).

The CII Badging requirements are here:

https://github.com/coreinfrastructure/best-practices-badge/blob/master/README.md

ONAP has extensive CII Badging docs here:

https://wiki.onap.org/display/DW/CII+Badging+Program

Cross-Project Security
----------------------

Track and quash security vulnerabilities in LFN leveraging cross-project
advantages.

Cross-Project CI/CD
-------------------

Continue improving and extending LFN Cross-Project Continuous Integration
Testing (CI) and Continuous Delivery (CD) pipelines.

Examples:

* Provide continuous, automated builds in common package formats for
  consumption by other projects.
* Provide common configuration management tooling to facilitate installation
  and configuration by other projects.
* Provide pre-built/installed/configured containers to facilitate deployments
  by other projects.
* Run tests that consume LFN Project's CD pipelines and tooling, potentially
  integrating multiple LFN Projects, and validate deployment scenarios.

Identify Quality Tooling
------------------------

Leverage the shared knowledge and experience of LFN Projects to identify good
solutions to common tooling problems.

As always, LFN Projects are completely in control of what tooling they choose
to use.

Examples:
* Better options than Nexus IQ for scanning
