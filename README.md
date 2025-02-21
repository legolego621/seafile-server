# Description

This is helm chart for deploy seafile-server community edition to kubernetes cluster.

Based on manuals for deploy seafile-server to k8s and with docker-compose (for 12 version seafile).
- https://manual.seafile.com/12.0/setup/k8s_single_node/#gettings-started
- https://manual.seafile.com/12.0/setup/setup_ce_by_docker/#getting-started

# Setup steps
- See `values.yaml` file and descriptions. Create `my-values.yaml` file with you setup.
- install chart
```
$ helm install my-cloud oci://registry-1.docker.io/londinzer/seafile --version 0.1.0 -f my-values.yaml
```