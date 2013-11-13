# PostgreSQL Puppet Module for Boxen

[![Build Status](https://travis-ci.org/boxen/puppet-postgresql.png?branch=master)](https://travis-ci.org/boxen/puppet-postgresql)

## Usage

```puppet
# install postgres and run the service
include postgresql

# do the above automatically, and create a db
postgresql::db { 'mydb': }
```

## Required Puppet Modules

* `boxen`
* `homebrew`
* `stdlib`
* `sysctl`

*Note: Overide typical boxen install on port 15432 to run on standard 5432.*

Then write some code. Run `script/cibuild` to test it. Check the `script`
directory for other useful tools.
