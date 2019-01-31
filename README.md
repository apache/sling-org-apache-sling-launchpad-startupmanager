[<img src="https://sling.apache.org/res/logos/sling.png"/>](https://sling.apache.org)

 [![Build Status](https://builds.apache.org/buildStatus/icon?job=Sling/sling-org-apache-sling-launchpad-startupmanager/master)](https://builds.apache.org/job/Sling/job/sling-org-apache-sling-launchpad-startupmanager/job/master) [![License](https://img.shields.io/badge/License-Apache%202.0-blue.svg)](https://www.apache.org/licenses/LICENSE-2.0) [![launchpad](https://sling.apache.org/badges/group-launchpad.svg)](https://github.com/apache/sling-aggregator/blob/master/docs/groups/launchpad.md)

This module is part of the [Apache Sling](https://sling.apache.org) project.

## What is it?

The sling community agreed to drop the Launchpad API and removed all usage over time. It was only implemented fully in Launchpad Base and not in any other launcher. 

However, until that is done, the idea of the startupmanager is to move out what is needed to make the systems work (e.g. in other launchers) until we stop requiring the
launchpad api. It for the most part is just a couple of stub services (or with minimal implementations) that can be use in other launchers if there is a need for it - but it is not adviced.
