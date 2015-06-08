# Golang playbook

[![License](https://img.shields.io/badge/license-New%20BSD-blue.svg?style=flat)](https://raw.githubusercontent.com/mediaFORGE/utahgophers-go-playbook/master/LICENSE)
[![Build Status](https://travis-ci.org/mediaFORGE/utahgophers-go-playbook.svg?branch=master)](https://travis-ci.org/mediaFORGE/utahgophers-go-playbook)

[![Platform](http://img.shields.io/badge/platform-debian-a80030.svg?style=flat)](#)
[![Platform](http://img.shields.io/badge/platform-macosx-000000.svg?style=flat)](#)
[![Platform](http://img.shields.io/badge/platform-ubuntu-dd4814.svg?style=flat)](#)

[![Project Stats](https://www.openhub.net/p/mediaFORGE-utahgophers-go-playbook/widgets/project_thin_badge.gif)](https://www.openhub.net/p/mediaFORGE-utahgophers-go-playbook/)

Ansible role to setup Go in Ubuntu and OSX environments.


## Tests

| Family | Distribution | Version | Test Status |
|:-:|:-:|:-:|:-:|
| Debian | Ubuntu  | Precise | [![x86](http://img.shields.io/badge/x86-n/a-cccccc.svg?style=flat)](#) [![x86_64](http://img.shields.io/badge/x86_64-n/a-cccccc.svg?style=flat)](#)  |
| Debian | Ubuntu  | Trusty  | [![x86](http://img.shields.io/badge/x86-n/a-cccccc.svg?style=flat)](#) [![x86_64](http://img.shields.io/badge/x86_64-n/a-cccccc.svg?style=flat)](#) |
| Debian | Ubuntu  | Vivid   | [![x86](http://img.shields.io/badge/x86-n/a-cccccc.svg?style=flat)](#) [![x86_64](http://img.shields.io/badge/x86_64-n/a-cccccc.svg?style=flat)](#) |


## Requirements

- ansible == 1.9.0.1


## Role Variables

TODO


## Dependencies

None.


## Playbooks

An example to setup Go on localhost.

    $ ansible-playbook -i localhost, --connection=local site.yml


## Changelog

- v1.0.0 : 8 Jun 2015
    - installation of Go on Debian-based Linux distributions using apt
    - installation of Go on MacOSX systems using macports


## Links

- [Utah Gophers User Group](http://utahgophers.com/)


## License

[![License](https://img.shields.io/badge/license-New%20BSD-blue.svg?style=flat)](https://raw.githubusercontent.com/mediaFORGE/utahgophers-go-playbook/master/LICENSE)


## Author Information

- [Rakuten Marketing](http://www.rakutenmarketing.com/)
- [steenzout](http://github.com/steenzout/)