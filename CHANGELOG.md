# Changelog

All notable changes to this project will be documented in this file.
Each new release typically also includes the latest modulesync defaults.
These should not affect the functionality of the module.

## [v3.0.0](https://github.com/voxpupuli/puppet-mysql_java_connector/tree/v3.0.0) (2017-10-13)

[Full Changelog](https://github.com/voxpupuli/puppet-mysql_java_connector/compare/v2.3.0...v3.0.0)

**Breaking changes:**

- BREAKING: Drop puppet 3 support. Replace validate\_\* with datatypes [\#34](https://github.com/voxpupuli/puppet-mysql_java_connector/pull/34) ([bastelfreak](https://github.com/bastelfreak))

**Implemented enhancements:**

- Adding proxy support [\#36](https://github.com/voxpupuli/puppet-mysql_java_connector/pull/36) ([bt-lemery](https://github.com/bt-lemery))

**Merged pull requests:**

- release 2.3.0 [\#28](https://github.com/voxpupuli/puppet-mysql_java_connector/pull/28) ([bastelfreak](https://github.com/bastelfreak))

## [v2.3.0](https://github.com/voxpupuli/puppet-mysql_java_connector/tree/v2.3.0) (2017-01-13)

This is the last release with Puppet 3 support!
* Modulesync with latest Vox Pupuli defaults
* Fix several markdown issues
* Add missing badges
* rubocop: fix RSpec/ImplicitExpect
* Bump min version_requirement for Puppet + deps

## 2016-10-06 - Release 2.2.0

### **Major bug fix release**

Versions 2.0.0 to 2.1.1 were broken for most users.

* [GH-11](https://github.com/voxpupuli/puppet-mysql_java_connector/issues/11) Fix missing `archive` `extract_path`

## 2016-10-05 - Release 2.1.1

- Release of 2.1.0 again, which didn't make it to the forge on the first try

## 2016-10-05 - Release 2.1.0

- Modulesync with latest Vox Pupuli defaults
- Enhance spec test code quality
- Bump default connector version to 5.1.40
- validate $links with validate_array()

## 2016-05-21 - Release 2.0.0

- released under the voxpupuli namespace
- modulesync with voxpupuli defaults (0.6.2)
- bump default java version from 5.1.34 to 5.1.38
- rename parameter downloadURL to downloadurl
- replace staging with archive
- add support for STRICT_VARIABLES


## 2015-07-14 - Release 1.0.0

- First Release (by Merritt Krakowitzer)


\* *This Change Log was automatically generated by [github_changelog_generator](https://github.com/skywinder/Github-Changelog-Generator)*