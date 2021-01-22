# Changelog
- All notable changes to this project will be documented in this file.
- See [changelog structure](https://keepachangelog.com/en/0.3.0/) for more information of how to write perfect changelog.

## Release note
- Make sure what version is required for the client. Is it production or testing
- Make sure why developing, set DISABLE_CACHE to true in order for dependency injection loaded containers would change.
  Otherwise, they are in immutable state.
- When providing the zip , make sure there are no .git or var folder
- Install vendors using composer install --no-dev --optimize-autoloader
- Use existing vendor if exists in repository for compatability issues


## [3.1.1] - 2021-01-11

### Changed
- prestashop 1.7.7 controllers created for printing service
- order view page compatibility update, parameters changes, new hooks instantiated
- order add page new parameters added, logic changed for version compliance
- javascript changes for prestashop 1.7.7
- bootstrap update to version 4 in backoffice pages

## [3.1.2] - 2021-01-22

### Changed
- Show prestashop version in shipment reference