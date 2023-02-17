# Changelog

All notable changes to this project will be documented in this file. See [standard-version](https://github.com/conventional-changelog/standard-version) for commit guidelines.

### [1.2.1](https://github.com/christippett/terraform-google-cloud-sql-pgbouncer/compare/v1.2.0...v1.2.1) (2023-02-14)

## [1.2.0](https://github.com/christippett/terraform-google-cloud-sql-pgbouncer/compare/v1.1.1...v1.2.0) (2021-05-14)


### Features

* Upgrade default base image to Container-Optimized OS 89 ([3d7f3c8](https://github.com/christippett/terraform-google-cloud-sql-pgbouncer/commit/3d7f3c84bf24b50cff47504b84535367d2b2956a))


### Bug Fixes

* Add missing config values in pgbouncer.ini ([dbb5da4](https://github.com/christippett/terraform-google-cloud-sql-pgbouncer/commit/dbb5da4e74dcdb52a55bac812bbd3a8f191d7e74))
* Define permissions as strings in cloud-init config ([e16b061](https://github.com/christippett/terraform-google-cloud-sql-pgbouncer/commit/e16b06179aa957c1fd9062928b9bae74c58368e6))
* md5 password prefix ([977e769](https://github.com/christippett/terraform-google-cloud-sql-pgbouncer/commit/977e769dadf89c37d9b4b14b2055a834623d278a))

### [1.1.2](https://github.com/christippett/terraform-cloud-sql-pgbouncer/compare/v1.1.1...v1.1.2) (2020-07-05)

### [1.1.1](https://github.com/christippett/terraform-cloud-sql-pgbouncer/compare/v1.1.0...v1.1.1) (2020-06-14)

## [1.1.0](https://github.com/christippett/terraform-cloud-sql-pgbouncer/compare/v1.0.1...v1.1.0) (2020-06-14)


### Features

* :boom: Move creation of PgBouncer cloud-init config into sub-module ([9059b20](https://github.com/christippett/terraform-cloud-sql-pgbouncer/commit/9059b204e581a6eca06e152725b047fac9dd1829))

### [1.0.1](https://github.com/christippett/terraform-cloud-sql-pgbouncer/compare/v1.0.0...v1.0.1) (2020-06-14)


### Features

* Refactor & complete module Cloud SQL over private IP example ([13748e5](https://github.com/christippett/terraform-cloud-sql-pgbouncer/commit/13748e58aa7e117e6bc36fb6dcdebb1eecca6427))


### Bug Fixes

* Fix switched values for public/private IP address in output ([6f078a9](https://github.com/christippett/terraform-cloud-sql-pgbouncer/commit/6f078a9194617062fe2099f036e52288aefe9ca6))

## [1.0.0](https://github.com/christippett/terraform-cloud-sql-pgbouncer/compare/v1.0.0-alpha.0...v1.0.0) (2020-06-14)


### Features

* Move default value for `service_account_access_scopes` out of `variables.tf` ([5857353](https://github.com/christippett/terraform-cloud-sql-pgbouncer/commit/585735330bbba9ca188425469f7a78a964b475a1))


### Bug Fixes

* Fix incorrect default input value for `pool_mode` ([447a5cb](https://github.com/christippett/terraform-cloud-sql-pgbouncer/commit/447a5cb36b90d8d72564c419f3fcadaccdd8e6be))

## 1.0.0-alpha.0 (2020-06-14)


### Features

* Add usage example using Cloud SQL with a private IP ([b61754a](https://github.com/christippett/terraform-cloud-sql-pgbouncer/commit/b61754a9c3d6421247255b1d07e7c80198fdb0b3))
* Create a PgBouncer instance to connect Cloud SQL ([1573778](https://github.com/christippett/terraform-cloud-sql-pgbouncer/commit/1573778a8f3b1231f584815f30ad626612e609c6))
