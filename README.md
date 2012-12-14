Description
===========

A skeleton for new Chef cookbooks. Fork it and adapt it to your needs.

Requirements
============

## Platform:

* Ubuntu
* Debian

## Cookbooks:

*No dependencies defined*

Attributes
==========

*No attributes defined*

Recipes
=======

## skeleton::default

Installs/configures something

Testing
=======

The cookbook comes with some testing facilities allowing you to iterate quickly.

Rake
----

You can execute the tests with [Rake](http://rake.rubyforge.org). The `Rakefile`
provides the following tasks:

    $ rake -T
    rake chefspec    # Run ChefSpec examples
    rake foodcritic  # Run Foodcritic lint checks
    rake knife       # Run knife cookbook test
    rake test        # Run all tests

Bundler
-------

If you prefer to let [Bundler](http://gembundler.com) install all required gems
(you should), run the tests this way:

    $ bundle install
    $ bundle exec rake test

Berkshelf
---------

[Berkshelf](http://berkshelf.com) is used to install the cookbook's dependencies
(as defined in `Berksfile`) prior to testing with Rake and Vagrant.

Vagrant
-------

With [Vagrant](http://vagrantup.com), you can spin up a virtual machine and run
your cookbook via Chef Solo. This will boot the VM:

    $ bundle exec vagrant up

Travis CI
---------

The cookbook includes a configuration for [Travis CI](https://travis-ci.org).
Simply enable Travis for your GitHub repository to get free continuous
integration.

License and Author
==================

Author:: Mathias Lafeldt (<mathias.lafeldt@gmail.com>)

Copyright:: 2012, Mathias Lafeldt

Licensed under the Apache License, Version 2.0 (the "License");
you may not use this file except in compliance with the License.
You may obtain a copy of the License at

    http://www.apache.org/licenses/LICENSE-2.0

Unless required by applicable law or agreed to in writing, software
distributed under the License is distributed on an "AS IS" BASIS,
WITHOUT WARRANTIES OR CONDITIONS OF ANY KIND, either express or implied.
See the License for the specific language governing permissions and
limitations under the License.