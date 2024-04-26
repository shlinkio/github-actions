# github-actions

Internal Github workflows and actions for Shlink repositories.

## Reusable workflows:

* `docker-publish-image`: Publish multi-arch docker images in docker hub and GHCR.
* `docker-migrate-registry`: Migrate docker images from public registry to GHCR.
* `js-lib-ci`: Continuous integration for JS libraries.
* `js-lib-publish`: Publish JS library to npm registry and create GitHub release, when a JS library is tagged.
* `php-lib-ci`: Continuous integration for PHP libraries.
* `php-lib-publish-release`: Publish release with CHANGELOG when a PHP library is tagged.
* `web-app-ci`: Continuous integration for web apps.

## Regular workflows

* docker-migrate-registry: Migrate multi-arch docker images from docker hub to GHCR.
