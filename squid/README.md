# Install

* get sources via `wget`
* unpack `tar xfv`
* `mv squid-SQUID-<release> squid`
* `cd squid`
* if sources from github `./bootstrap.sh`
* `./configure --prefix=/home/$USER/squid/ && make && make install`

# Configure

* use config file next to this file at ~/squid/etc/squid.conf
* htpasswd squid/etc/passwords <desired_username>
* precaution: create dirs etc `squid/sbin/squid -z -f squid/etc/squid.conf`

# Create Daemon

[guide](https://manual.uberspace.de/daemons-supervisord/) no success yet

