# Change Log
This is the Maleficarum RabbitMQ component implementation. 

## [7.1.0] - 2018-09-14
### Changed
- When attempting to create a connection there will be a double retry from now on. (Exactly 3 attempts will be made to establish the connection).
- Increased connection timeout parameters from 3s to 10s.

## [7.0.0] - 2017-08-03
### Changed
- Make use of nullable types provided in PHP 7.1 (http://php.net/manual/en/migration71.new-features.php)
- Fix tests

## [6.0.3] - 2017-05-10
### Fixed
- Cast port to integer

## [6.0.2] - 2017-04-06
### Fixed
- Cast port to integer

## [6.0.1] - 2017-04-06
### Fixed
- Move delcare before namespace delcaration

## [6.0.0] - 2017-03-24
### Changed
- Changed internal structure.
- Added default package initializer.

## [5.0.2] - 2017-03-08
### Fixed
- Fix addRawMessage method by passing AMQPMessage object instead of string

## [5.0.1] - 2017-03-08
### Fixed
- Replace deprecated AMQPConnection with AMQPStreamConnection

## [5.0.0] - 2017-03-08
### Added
- Add connection parameters to constructor
- Fix tests

## [4.1.0] - 2017-03-07
### Added
- Add method for raw message push

## [4.0.0] - 2017-03-01
### Changed
- Remove config component
- Fix tests

## [3.0.1] - 2017-02-15
### Added
- Add tests

## [3.0.0] - 2017-01-30
### Changed
- Changed namespace of command component

## [2.0.0] - 2017-01-23
### Changed
- Add return and argument types declaration

## [1.0.0] - 2017-01-09
### Added
- This was an initial release based on the code written by pharaun13 and added to the repo by me
