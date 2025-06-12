# Change Log
All notable changes to this project will be documented in this file, which follows the guidelines
on [Keep a CHANGELOG](http://keepachangelog.com/). This project adheres to
[Semantic Versioning](http://semver.org/).

## [Unreleased]
- Github migration to HMCTS Organisation

## [17.0.0] - 2023-05-05
### Changed
- Release of Java 17 version
- Bumped the version number to 17.0.0 to match the java 17 versions of the framework

## [11.0.0] - 2023-01-25
### Changed
- Bumped the version number to 11.0.0 to match the java 11 versions of the framework

## [2.0.0] - 2020-09-22
### Changed
- Moved from bintray to cloudsmith for hosting of maven artifacts
- Removed bintray specific properties and/or replaced with those for cloudsmit
- Updated settings.xml to include the new cloudsmith profile - kept bintray profile for the time being
- Replaced encrypted bintray api key from .travis.yaml and added the encrypted `CLOUDSMITH_API_KEY` 

## [1.1.1] - 2017-07-27
### Changed
- Simplify the variable definitions so only cpp.repo.name needs to be set for bintray integration to work
- Use common build processes (in travis-settings)

## [1.1.0] - 2017-07-26
### Added
- Switch from IndigoBlue repository to Bintray (releases only)
### Changed
- Only deploy on tag
### Removed
- Deployment to IndigoBlue repository
## [1.0.0] - 2016-07-14
### Added
- Initial release of super POM
