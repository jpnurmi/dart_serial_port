## [0.0.6] - 2021-01-01

* Fixed dynamic library lookup caching

## [0.0.5] - 2020-12-17

* Fixed a null pointer dereference in SerialPort.availablePorts
  - Thanks @Coimbra1984!

## [0.0.4+1] - 2020-10-02

* Fixed the example snippet in the README

## [0.0.4] - 2020-10-02

* Added a note about flutter_serial_port "sibling" package

## [0.0.3] - 2020-09-27

* Made SerialPortReader report stream errors
* Added SerialPortReader.port getter
* Added SerialPort.isOpen getter
* Fixed SerialPortReader respect stream pause & resume
* Replaced SerialPort.lastErrorXxx with SerialPort.lastError
* Fixed handling of the LIBSERIALPORT_PATH environment variable
* Fixed error handling for errno=0 type of failures

## [0.0.2] - 2020-09-06

* Fixed a null pointer dereference

## [0.0.1+2] - 2020-09-02

* Example: added missing dispose() call to avoid leaks

## [0.0.1+1] - 2020-09-01

* Address pub.dev score

## [0.0.1] - 2020-09-01

* Initial release
