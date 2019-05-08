# Grafana
Setting up grafana in a Docker container.

## Overview
* *docker_run.sh*:
  * create named volume *grafana-data*
  * create named network *ape*
  * start the container
    * detached mode
    * named *grafana*
    * publish ports 3000
    * mount the named volume *grafana-data*
    * link the network *ape*
  * copy *settings.js* to the container

## Getting started
1. clone this repository
2. run the docker script
`$./docker_run.sh`

# Author

**Brent Maranzano**

# License

This project is licensed under the MIT License - see the LICENSE file for details
