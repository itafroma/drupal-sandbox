# Drupal Sandbox

This module provides an easy entrypoint for testing the Drupal API by providing
a single route, `/sandbox`, and page callback, `sandbox_view()`.

## Requirements

* [Drupal 7][1]

## Installation

Download the module via one of the download methods below and enable the module.
If you need help, Drupal.org has [more information about installing contributed
modules][1].

### Download via [Composer][3] (recommended)

Add the following to your `composer.json` file in `sites/all`, `sites/default`,
or `sites/example.com` and run `composer install`:

```json
{
    "require": {
        "itafroma/drupal-sandbox": "~1.0.0",
    }
}
```

### Download via Git

Clone the repository into your preferred modules directory:

```sh
git clone https://github.com/itafroma/drupal-sandbox.git sandbox
```

## Author and contact

The author of this module is Mark Trapp.

* [Author website][5]
* [Author email][6]
* [Module issue queue][7]

## Copyright and license

This module is licensed via the [GNU General Public License, v2.0 only][4].
Where applicable, it is copyright © 2013 Mark Trapp with all rights otherwise
reserved. A copy of this license can be found in the LICENSE file.

## Other links

* [Canonical project URL][8]
* [Current source code][9]

[1]: https://drupal.org/project/drupal "Drupal 7 download"
[2]: https://drupal.org/node/895232 "Installing contributed modules (Drupal 7)"
[3]: http://getcomposer.org "Composer Dependency Manager website"
[4]: http://www.gnu.org/licenses/gpl-2.0.html "GNU General Public License, version 2"
[5]: http://marktrapp.com "Mark Trapp's website"
[6]: mailto:mark@marktrapp.com "Mark Trapp's email address"
[7]: https://github.com/itafroma/sandbox/issues "Github issue queue"
[8]: https://github.com/itafroma/sandbox "Github project page"
[9]: https://github.com/itafroma/sandbox "Github project page"

