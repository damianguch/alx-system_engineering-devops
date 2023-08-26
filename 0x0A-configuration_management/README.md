# Configuration management

## Project Requirements

- The Puppet manifests must pass puppet-lint version 2.1.1 without any errors
- The  Puppet manifests must run without error
- The Puppet manifests first line must be a comment explaining what the Puppet
manifest is about
- The Puppet manifests files must end with the extension .pp

## Note on Versioning

Ubuntu 20.04 VM should have Puppet 5.5 preinstalled.

## Install puppet
```
$ apt-get install -y ruby=1:2.7+1 --allow-downgrades
$ apt-get install -y ruby-augeas
$ apt-get install -y ruby-shadow
$ apt-get install -y puppet
```
This project is simply a set of tasks to familiarize you with the basic level
syntax which is virtually identical in newer versions of Puppet.

## Install puppet-lint
```
$ gem install puppet-lint
```
