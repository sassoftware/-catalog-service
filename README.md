# SAS App Engine Catalog Service-- Archived Repository  
**Notice: This repository is part of a Conary/rpath project at SAS that is no longer supported or maintained. Hence, the repository is being archived and will live in a read-only state moving forward. Issues, pull requests, and changes will no longer be accepted.**

==============================

Overview
--------

catalog-service is a library used to manage the deployment and launching of
virtual machines on numerous targets. Even though it is called "catalog
service", it is not actually a distinct service but rather a combination of a
library used by mint, and a rmake3 plugin used to deploy and launch systems.

Because different target types have different resources and configuration,
catalog-service is also responsible for encapsulating configuration into
*smartform* descriptors so that clients can interact with a variety of targets
without having any specific knowledge about how they work.
