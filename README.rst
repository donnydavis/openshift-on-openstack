======================
OpenShift on OpenStack
======================

About
=====

A collection of documentation, Heat templates, Dockerfiles and everything else
that's necessary to deploy OpenShift Origin (v3) on an OpenStack-backed
infrastructure using Atomic Host images.


Prerequisities
==============

1. OpenStack version Juno or later with the Heat, Neutron, Ceilometer services
running

2. Atomic Host cloud image (we leverage cloud-init) loaded in Glance

3. An SSH keypair loaded to Nova

4. A (Neutron) network with a pool of floating IP addresses available



Copyright
=========

Copyright 2015 Red Hat, Inc.

Licensed under the Apache License, Version 2.0 (the "License");
you may not use this file except in compliance with the License.
You may obtain a copy of the License at

    http://www.apache.org/licenses/LICENSE-2.0

Unless required by applicable law or agreed to in writing, software
distributed under the License is distributed on an "AS IS" BASIS,
WITHOUT WARRANTIES OR CONDITIONS OF ANY KIND, either express or implied.
See the License for the specific language governing permissions and
limitations under the License.