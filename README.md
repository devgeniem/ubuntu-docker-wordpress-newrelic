# Docker wordpress php7+nginx container with new relic agent
This is minimal container based in [devgeniem/ubuntu-docker-wordpress](https://github.com/devgeniem/ubuntu-docker-wordpress).

This container installs newrelic php agent.

## env configuration
Set these `env` for your container in order to use new relic.
```
NR_LICENSE_KEY: xxxxxxxxxxxxxxxxxxxx
NR_APP_NAME: WP-site
```
