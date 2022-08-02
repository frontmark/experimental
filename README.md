# experimental

[![License: MIT](https://img.shields.io/badge/License-MIT-yellow.svg)](https://opensource.org/licenses/MIT)
[![frontmark](https://img.shields.io/badge/powered%20by-frontmark-lightgrey.svg)](https://www.frontmark.de/)

Public playground. The code might be a work in progress.\*

\*) i.e., it SHOULD work, but is not guaranteed to. Watch out for the edge cases!

## :cloud: ionos-cloud-init

Initially developed as part of a working student's project in 2021/2022.

The - dockerized - `cloud-init.py` script leverages the [IONOS Cloud API (6.0)](https://api.ionos.com/docs/cloud/v6/), which can be seen "as an alternative to the "Data Center Designer" (DCD) browser-based tool" and "can be used to perform a multitude of management tasks, including adding servers, volumes, configuring networks, and so on."

To do so, the `cloud-init.py` script expects a datacenter to be defined with JSON and YAML config files ("Infrastructure as Code"). The JSON files define the servers (`type` of server, e.g., "ENTERPRISE" or "CUBE"; `ram`; `cores`; etc.) and the YAML files can be used to initialize the OS itself (adding users, keys and packages; disk setup; etc.): [[...]](ionos-cloud-init)


