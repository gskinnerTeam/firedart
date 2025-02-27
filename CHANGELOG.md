
## [1.0.0-nullsafety] - 16 March 2021.

* Migrate to nnbd

## [0.8.3] - 26 October 2020.

* Update dependencies and regenerate RPC stubs

## [0.8.2] - 16 June 2020.

* Add anonymous sign-in (thanks @bierbaumtim)

## [0.8.1] - 12 June 2020.

* Add SignedOutException when calling protected methods while signed out
* Add AuthException with error details to all Auth calls

## [0.8.0+1] - 02 June 2020.

* Update documentation

## [0.8.0] - 01 June 2020.

* Implement collection queries (thanks @SwissCheese)
* Improve translation between Dart and Firebase data types

## [0.7.2] - 05 May 2020.

* Logout user on account deletion

## [0.7.1] - 05 May 2020.

* Fix requesting email confirmation
* Add User.toMap() method

## [0.7.0] - 29 March 2020.

* Implement paging
* Expose document creation and update times
* Fix collections only returning up to 20 documents

## [0.6.5] - 4 January 2020.

* Return user on signup and signin
* Expose Firebase user id
* Fix code warnings

## [0.6.4] - 13 December 2019.

* Update to latest Firebase auth endpoints
* Remove dart:io dependency
* Throw exception on auth errors

## [0.6.3] - 20 November 2019.

* Fix linter warnings

## [0.6.2] - 20 November 2019.

* Update Protobug and GRPC dependencies to latest versions

## [0.6.1] - 21 July 2019.

* Add generic Reference factory

## [0.6.0] - 21 July 2019.

* Implement collection streaming
* Deprecate some getter methods in favour of dart's getter syntax

## [0.5.1] - 17 July 2019.

* Improve token storage

## [0.5.0+1] - 16 July 2019.

* Cleanup to satisfy dart pub analysis

## [0.5.0] - 16 July 2019.

* Refactor the code to use RPC instead of REST for Firestore.
* Implement listening to document real-time updates.

## [0.1.0] - 26 June 2019.

* Fix issues identified in the dart pub analysis.

## [0.0.1] - 26 June 2019.

* Initial release.
