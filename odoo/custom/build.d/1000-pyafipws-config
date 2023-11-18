#!/bin/bash
log INFO pyafipws install - Creating pyafipws cache directory
cd /usr/local/lib/python3.10/site-packages/pyafipws
mkdir cache
log INFO pyafipws install -  Applying permissions to cache directory
chmod -R 777 cache
log INFO pyafipws install -  Cache directory successfully created
log INFO pyafipws install -  Changing SSL configuration
sed -i -e 's/DEFAULT@SECLEVEL=2/DEFAULT@SECLEVEL=1/' /etc/ssl/openssl.cnf
log INFO pyafipws install -  Pyafipws configuration sucess.
