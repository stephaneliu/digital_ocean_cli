Digital Ocean CLI
=================

## Installation
Clone this repo and symlink do_cli.rb into your /usr/bin or ~/bin directory. You will need to create an Digital Ocean API key for your account at https://cloud.digitalocean.com/settings/applications.

```
export DO_KEY=[your API key]
gem install barge
ln -s digital_ocean_cli/do_cli.rb ~/bin/DO
```

## Getting Started
``` DO help ```

Common commands

``` DO list regions```

``` DO list sizes```

``` DO list ssh_key```

``` DO create ``` (new droplet)

``` DO destroy ``` (destroy droplet)

Create and destroy will ask for confirmation before proceeding

