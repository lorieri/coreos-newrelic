# coreos-newrelic
newrelic unit for coreos (any systemd?) to launch sysmond on each node

# how-to

 * edit the file changing NEW_RELIC_LICENSE_KEY to your key
 * launch the unit
  * ```fleetctl start newrelic-sysmond.service```
