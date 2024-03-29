[![Apache Sling](https://sling.apache.org/res/logos/sling.png)](https://sling.apache.org)

&#32;[![Build Status](https://ci-builds.apache.org/job/Sling/job/modules/job/sling-org-apache-sling-launchpad-startupmanager/job/master/badge/icon)](https://ci-builds.apache.org/job/Sling/job/modules/job/sling-org-apache-sling-launchpad-startupmanager/job/master/)&#32;[![Coverage](https://sonarcloud.io/api/project_badges/measure?project=apache_sling-org-apache-sling-launchpad-startupmanager&metric=coverage)](https://sonarcloud.io/dashboard?id=apache_sling-org-apache-sling-launchpad-startupmanager)&#32;[![Sonarcloud Status](https://sonarcloud.io/api/project_badges/measure?project=apache_sling-org-apache-sling-launchpad-startupmanager&metric=alert_status)](https://sonarcloud.io/dashboard?id=apache_sling-org-apache-sling-launchpad-startupmanager)&#32;[![JavaDoc](https://www.javadoc.io/badge/org.apache.sling/org.apache.sling.launchpad.startupmanager.svg)](https://www.javadoc.io/doc/org.apache.sling/org.apache.sling.launchpad.startupmanager)&#32;[![Maven Central](https://maven-badges.herokuapp.com/maven-central/org.apache.sling/org.apache.sling.launchpad.startupmanager/badge.svg)](https://search.maven.org/#search%7Cga%7C1%7Cg%3A%22org.apache.sling%22%20a%3A%22org.apache.sling.launchpad.startupmanager%22)&#32;[![launchpad](https://sling.apache.org/badges/group-launchpad.svg)](https://github.com/apache/sling-aggregator/blob/master/docs/groups/launchpad.md) [![License](https://img.shields.io/badge/License-Apache%202.0-blue.svg)](https://www.apache.org/licenses/LICENSE-2.0)

This module is part of the [Apache Sling](https://sling.apache.org) project.

## What is it?

The sling community agreed to drop the Launchpad API and removed all usage over time. It was only implemented fully in Launchpad Base and not in any other launcher. 

However, until that is done, the idea of the startupmanager is to move out what is needed to make the systems work (e.g. in other launchers) until we stop requiring the
launchpad api. It for the most part is just a couple of stub services (or with minimal implementations) that can be use in other launchers if there is a need for it - but it is not adviced.
