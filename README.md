# Platform.sh Third-Party Resources

This is a Big List of known third party resources for Platform.sh. These resources are not published or vetted by Platform.sh, but may be useful for people working with the platform.

This list is maintained by @xtfer. Pull Requests welcome.

## Blogs

* "[The future of the PHP PaaS is here: Our journey to Platform.sh](https://www.cloud-solutions.net/en/blog/entry/cs-tech/the-future-of-the-php-paas-is-here-our-journey-to-platform-sh)", by Marcus Hausammann
* An [introduction to Platform.sh](https://www.sitepoint.com/first-look-platform-sh-development-deployment-saas/) from Chris Ward 

## Guides

* How to [connect to your MySQL database](https://www.thinktandem.io/blog/2017/03/03/connecting-to-a-remote-platform-sh-database) using Sequel Pro 
* All the stuff you need for a [pro-dev-flow using platform.sh](https://github.com/thinktandem/platform-workflow-demo) as your deploy target  again by https://www.thinktandem.io
* How to [set up XDebug](https://ghosty.co.uk/2015/09/debugging-on-platform-sh/) 
* Official [Symfony documentation](http://symfony.com/doc/current/deployment/platformsh.html) on deploying to Platform.sh 
* Official [Sylius](http://docs.sylius.org/en/latest/cookbook/platform-sh.html) documentation on deploying to Platform.sh
* How Platform.sh can [simplify your contribution workflow on GitHub](https://medium.com/akeneo-labs/how-platform-sh-can-simplify-your-contribution-workflow-on-github-6e2a557a1bcc) by Mickaël Andrieu from Akeneo
* [A guide in French](http://thomas-asnar.github.io/platform-sh-orange-cloud/) on deploying to Platform.sh by Thomas Asnar [FR]
* Nacho Digital has a guide on [moving an existing site](http://www.nachodigital.com.ar/content/moving-existing-site-platformsh) to Platform.sh 
* How to set up [SSL with Cloudflare](https://www.ignoredbydinosaurs.com/posts/307-setting-up-ssl-on-your-platformsh-site-with-cloudflare)
* Introduction to [using PostgreSQL](https://www.ignoredbydinosaurs.com/posts/296-postgres-on-platform) 

### Drupal

* [Modifying distribution make files for Platform.sh](https://www.nickvahalik.com/blog-entry/modifying-distribution-makefiles-within-your-own-project-makefile-platformsh) 
* Platform.sh [Drupal 8 Development Workflow](https://github.com/JohnatasJMO/platformsh-development-workflow) by @JohnatasJMO
* [Log using Monolog](https://gist.github.com/janstoeckler/7f251bf10fedbfb7f752b61ee5d2ef5e) to keep log files out of the database (and/or use whatever processors & handlers you want)

### Magento

* [Deploying Magento 2 with Redis on Platform.sh](https://rafaelstz.github.io/magento2/Deploying-Magento2-Redis-Platformsh.html) by [@rafaelcgstz](https://twitter.com/rafaelcgstz)

## Examples

Platform.sh lists maintained examples on its Github page, with some cross-referencing from http://docs.platform.sh. Examples listed below could work fine, or may be out-of-date or unmaintained. Use at your own risk.

### NodeJS

Framework  | Credit | Date added
-----------|--------|-----------
[MEAN stack](https://github.com/OriPekelman/platformsh-example-mean)|[@OriPekelman](https://github.com/OriPekelman)|May 2017

### Python

Framework  | Credit | Date added
-----------|--------|-----------
Python [**Flask using gunicorn**](https://github.com/etoulas/platformsh-example-flask)|[@etoulas](https://github.com/etoulas)|May 2017
[**Odoo**](https://github.com/OriPekelman/platformsh-example-odoo) Open Source ERP and CRM|[@OriPekelman](https://github.com/OriPekelman)|May 2017

### PHP

Framework  | Credit | Date added
-----------|--------|-----------
[**Akeneo** example](https://github.com/maciejzgadzaj/akeneo-on-platformsh-example)|[@maciejzgadzaj](https://github.com/maciejzgadzaj)|May 2017
[**API Platform** with a **ReactJS** client](https://github.com/GuGuss/platformsh-api-platform-admin) admin |[@GuGuss](https://github.com/GuGuss)|May 2017
[**Backdrop** example](https://github.com/gmoigneu/platformsh-example-backdrop)|[@gmoigneu](https://github.com/gmoigneu)|May 2017
[**Headless Drupal 8 with Angular**](https://github.com/GuGuss/headless-drupal8-platformsh)|[@GuGuss](https://github.com/GuGuss)|May 2017
[**Laravel** example](https://github.com/JGrubb/platformsh-laravel-example)|[@JGrubb](https://github.com/JGrubb)|May 2017
[**Moodle** example](https://github.com/JGrubb/platform-sh-moodle-example)|[@JGrubb](https://github.com/JGrubb)|May 2017
[**Mouf framework** example](https://github.com/xhuberty/RhMachine)|[The Coding Machine](https://github.com/xhuberty)|May 2017
[**Neos/Flow** example](https://github.com/ttreeagency/neos-base-distribution)|Dominique Feyer|May 2017
A more up-to-date (and very awesome) starting point for [**Neos/Flow**](https://github.com/DavidSporer/flow-neos-platformsh)|[@DavidSporer](https://github.com/DavidSporer)|May 2017
[**Silex** example](https://github.com/JGrubb/platformsh-silex-intro)|[@JGrubb](https://github.com/JGrubb)|May 2017
[**Silverstripe** example](https://github.com/gmoigneu/platformsh-example-silverstripe)|[@gmoigneu](https://github.com/gmoigneu)|May 2017
[**Thunder** example](https://github.com/md-systems/platformsh-example-thunder)|[maintained by the MD Systems team](https://github.com/md-systems)|May 2017
[**WooCommerce** example](https://github.com/liip/woocommerce-demo)|[@Liip](https://github.com/liip)|May 2017

### Ruby

Framework  | Credit | Date added
-----------|--------|-----------
[**Jekyll** example](https://github.com/JGrubb/platformsh-jekyll)|[@JGrubb](https://github.com/JGrubb)|May 2017

## Integrations

* [Integrate GitLab with Platform.sh using Gitlab-CI](https://github.com/axelerant/pushtoplatformsh), by [@Axelerant](https://github.com/axelerant)
* Platform.sh's original (unsupported) scripts for **GitLab** https://gist.github.com/pjcdawkins/0b3f7a6da963c129030961f0947746c4 
* **Scrutinizer CI** https://scrutinizer-ci.com/docs/guides/deploying/platform_sh
* An adapter from platform.sh webhook to **slack** incoming webhook that can be hosted on a platform.sh app https://github.com/hanoii/platformsh2slack
* How to [call the NewRelic API on deploy](https://github.com/platformsh/platformsh-docs/pull/536#issuecomment-295578188) (by @christopher-hopper)

## Tools

* **MySQL disk space** monitor https://github.com/galister/platformsh_mysqlmon
* Library for creating **Symfony Console build and deploy steps** https://github.com/dnunez24/platformsh-deploy-php
* A small tool from Hanoii https://github.com/hanoii/drocal
* **Ansible** playbook for setting up Vagrant and VirtualBox for use with a Platform.sh project https://github.com/DurableDrupal/ansible-vm-platformsh
* Another **Ansible** setup https://github.com/mglaman/platformsh-vagrant
* Script to **sync a Drupal site** from Production to Local https://github.com/pjcdawkins/platformsh-sync
* A **Docker** image with the Platform.sh CLI on it https://github.com/maxc0d3r/docker-platformshcli
* Some tips on using Platform.sh with **DrupalVM** https://github.com/geerlingguy/drupal-vm/issues/984
* Matt Pope's [Platform.sh automated mysql and files backup script](https://bitbucket.org/snippets/kaypro4/gnB4E)

## Archive

* Roll your own **Lets Encrypt** support https://github.com/reload/acme-platform.sh (probably no longer required, Platform.sh now supports Lets Encrypt)
