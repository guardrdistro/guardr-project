## Overview

Guardr is a Drupal distrobution with a combination of modules and settings to
enhance a Drupal application's security and availabilit to meet enterprise
security requirements.  Following the CIA Information Security Triad of
confidentiality, integrity and availability, the Guardr distrobution aims to
provide a security minded foundation to Drupal applications.

Default Guardr installs make stronger password requirements, strengthens
logging, prevents PHP input for content, implements some best practices for
email content, and disables error display requiring you to opt in to debugging
information using a variety of contrib modules and custom solutions.

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

* [Named Link](http://twitter.com/guardrproject) "Drupal Project Page"
* [Named Link](https://www.drupal.org/slack) "Drupal Slack" #contrib-guardr
* IRC #drupal-guardr at <irc.freenode.net>
* [Named Link](http://twitter.com/guardrproject) "Follow Guardr on Twitter"

##License

The Guardr Project is licensed under a GNU General Public License v.2
[Named Link](http://www.gnu.org/licenses/old-licenses/gpl-2.0.html) "Read
License"

