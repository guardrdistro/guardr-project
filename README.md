# Guardr Composer Template for Secure Drupal Projects

## Build Status

[![Build Status](https://travis-ci.com/guardrdistro/guardr-project.svg?branch=8.x)](https://travis-ci.com/guardrdistro/guardr-project)

## Overview

[<img src="https://www.drupal.org/files/styles/grid-3-2x/public/project-images/Guardr%20Logo-Vertical-Default.png"
     alt="Guardr logo" align="right" width="150px" />](https://www.drupal.org/project/guardr)

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

This Guardr Composer Template is perfect for starting up a new secure site, if
you have an existing Drupal site that you would like to secure, the Guardr Core
project is right for you.

* [Guardr Drupal.org Project](https://www.drupal.org/project/guardr_core)

## Install Instructions

Install Guardr using Composer

```bash
composer create-project guardrdistro/guardr-project:8.x-dev some-dir --no-interaction
```

## Branch Details

* [8.x](https://github.com/guardrdistro/guardr-project/tree/8.x) - Stable branch. Stable releases will be tagged.
* [8.x-test](https://github.com/guardrdistro/guardr-project/tree/8.x-test) - Dev branch. Used for testing dev versions of [Guardr](https://www.drupal.org/project/guardr) and [Guardr Core](https://www.drupal.org/project/guardr_core).

## Guardr Community

* [Drupal Project Page](https://www.drupal.org/project/guardr)
* [Drupal Slack](https://www.drupal.org/slack) #contrib-guardr
* [Follow Guardr on Twitter](http://twitter.com/guardrproject)

## License

The Guardr Project is licensed under a GNU General Public License v2
[Read License](http://www.gnu.org/licenses/old-licenses/gpl-2.0.html)
