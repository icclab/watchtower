*Please note that all watchtower components are under heavy development and the norm is that things will break. Please be patient with us until the first stable release.*

<div align="center">
	<img src="https://raw.githubusercontent.com/icclab/watchtower-common/master/watchtower.png" alt="Watchtower" title="Watchtower">
</div>

# Overview

This repository provides documentation for **Watchtower** and pointers to the other repositories that make up the system.

### Features

The following are partially or fully implemented features:

* Automated Cloud Incident Lifecycle Management
* Flexible API designed for easy integration of 3rd Party Solutions
* Designed with scalability in mind
* Integrated with HP Monasca, Apache Kafka, Camunda, and Rundeck
* Multi-tenant support

### Components

As of v1.0.0, it has 6 components of which four provide running services:
* **watchtower-monitoring** - its primary role is to get, process, and forward events from the monitoring solutions to **watchtower-workflow**


### Roadmap

The current roadmap is focused on extending current functionality through additional components:

* Python client
* User interface in Horizon
* Anomaly detection and prediction in Monasca
* Event aggregation and correlation
* Root cause analysis tools in Horizon
* Integration with Keystone or another Identity Management Solution
* Integration with Hurdle and Cyclops

# Getting started

Soon to come!


# Repositories

| Component | Status |
|-----------|--------|
| [watchtower-common](https://github.com/icclab/watchtower-common) | [![Build Status](https://travis-ci.org/icclab/watchtower-common.svg?branch=master)](https://travis-ci.org/icclab/watchtower-common) [![Coverage Status](https://coveralls.io/repos/icclab/watchtower-common/badge.svg?branch=master)](https://coveralls.io/r/icclab/watchtower-common?branch=master) |

# License

Copyright 2015 Zurich University of Applied Sciences

Licensed under the Apache License, Version 2.0 (the "License");
you may not use this file except in compliance with the License.
You may obtain a copy of the License at

    http://www.apache.org/licenses/LICENSE-2.0
    
Unless required by applicable law or agreed to in writing, software
distributed under the License is distributed on an "AS IS" BASIS,
WITHOUT WARRANTIES OR CONDITIONS OF ANY KIND, either express or
implied.
See the License for the specific language governing permissions and
limitations under the License.

# Author Information

For further information or assistance please contact [**Victor Ion Munteanu**](https://github.com/nemros).
