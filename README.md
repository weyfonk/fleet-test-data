# Fleet Test Data

This repo contains test data for the fleet tests at https://github.com/rancher/fleet/e2e.

## Adding Test Data

The namespaces for bundles must be unique, otherwise tests running in parallel could conflict.
It's also possible to override the namespace from a `GitRepo` resource.

## Test Data in Branches

There are also `test-` prefixed branches, which contain more test workloads. This is useful, if for example the whole repo is used in a test, instead of a sub path.
