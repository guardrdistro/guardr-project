# Guardr Composer Template for Secure Drupal Projects

## Build Status

[![Build Status](https://travis-ci.com/guardrdistro/guardr-project.svg?branch=8.x)](https://travis-ci.com/guardrdistro/guardr-project)

## Overview

This project template provides a starter kit for managing secure-first Guardr
Drupal projects.

Guardr is a Drupal distribution with a combination of modules and settings to
enhance a Drupal application's security and availability to meet enterprise
security requirements. Following the CIA Information Security Triad of
confidentiality, integrity and availability, the Guardr distribution aims to
provide a security minded foundation to Drupal applications.

Default Guardr installs make stronger password requirements, strengthens
logging, prevents PHP input for content, implements some best practices for
email content, and disables error display requiring you to opt in to debugging
information using a variety of contributed modules and custom solutions.

## Install Instructions

1. Clone the repository and install the project

```
git clone https://github.com/guardrdistro/guardr-project
cd guardr-project
composer install
```

2. Setup your local environment to use the web folder as webroot

3. Install Drupal using Drush or use the Drupal UI, making sure to select the
"Guardr" install profile

## Guardr Community

* [Drupal Project Page](http://twitter.com/guardrproject)
* [Drupal Slack](https://www.drupal.org/slack) #contrib-guardr
* [Follow Guardr on Twitter](http://twitter.com/guardrproject)

## License

The Guardr Project is licensed under a GNU General Public License v.2
[Read License](http://www.gnu.org/licenses/old-licenses/gpl-2.0.html)

