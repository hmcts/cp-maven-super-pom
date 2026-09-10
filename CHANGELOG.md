# Change Log
All notable changes to this project will be documented in this file, which follows the guidelines
on [Keep a CHANGELOG](http://keepachangelog.com/). This project adheres to
[Semantic Versioning](http://semver.org/).

## [25.104.1] - 2026-09-10
### Changed
Updated version properties for the following pugins to make them consistent, declared here so that all inheriting poms share a single
value:
- Updated Liquibase to 5.0.3
- Updated Build Helper Maven Plugin to 3.6.0
- Updated Buildnumber Maven Plugin to 3.2.0
- Updated Maven Assembly Plugin to 3.7.1
- Updated Maven Clean Plugin to 3.2.0
- Updated Maven Compiler Plugin to 3.15.0
- Updated Maven Dependency Plugin to 3.6.1
- Updated Maven Deploy Plugin to 3.1.4
- Updated Maven Enforcer Plugin to 3.4.1
- Updated Maven Failsafe Plugin to 3.5.6
- Updated Maven Install Plugin to 3.1.4
- Updated Maven Jar Plugin to 3.5.0
- Updated Maven Javadoc Plugin to 3.6.3
- Updated Maven Resources Plugin to 3.4.0
- Updated Maven Site Plugin to 3.12.1
- Updated Maven Source Plugin to 3.3.1
- Updated Maven Surefire Plugin to 3.5.6
- Updated Maven Wagon to 3.5.3
- Updated Maven WAR Plugin to 3.5.1
- Updated PIT Mutation Testing Plugin to 1.19.1
- Updated Versions Maven Plugin to 2.16.2

## [25.104.0] - 2026-09-07
### Added
- License file

### Changed
- Moved to the Java 25 / WildFly 40 release line and adopted the `25.104.0` version scheme,
  consolidating the `25.104.0-M1` milestone and the intermediate, never-released Java 21 /
  Jakarta EE 10 step
- Updated `README.md` to include the versioning strategy
- Migrated the repository to the HMCTS GitHub organisation

### Removed
- Redundant profile from `pom.xml`

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
