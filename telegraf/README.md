# Telegraf Plugin for Hassio

# Notable mentions

Forked from https://github.com/sabuto/hassio-repo, no Dockerfile there unfortunately.

# Description

This is a very simple hassio plugin that enables you to run telegraf on your hassio system.

# Installation

To Install this addon simply go to: Hassio->Addon-store.

Then add https://github.com/conrad784/hassio-repo in the add repository by URL box.

Scroll down to Repo and install Telegraf. Give it a few minutes to install and update.

# Config

Currently only possible to load from a file.
```bash
create config in /share/telegraf.conf
```

# Helpful Links
https://developers.home-assistant.io/docs/add-ons
https://github.com/home-assistant/addons-example

## Telegraf
https://github.com/influxdata/influxdata-docker


## Changes in s6, why we can't use it
https://community.home-assistant.io/t/hello-world-example-addon-from-developer-docs-stopped-working-s6-overlay-issue/421486/27
https://github.com/home-assistant/developers.home-assistant/pull/1336/files
https://github.com/just-containers/s6-overlay/issues/182#issuecomment-767251662

## Prometheus addon workaround
https://github.com/loganmarchione/hassos-addons/blob/main/prometheus_node_exporter/Dockerfile

## How it should be done today
https://github.com/hassio-addons/addon-glances

## How it was done previously
https://github.com/hassio-addons/addon-portainer/tree/main/portainer

# TO-DO
