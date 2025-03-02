## 1.0.14

* Updates to handle `Socket implements Stream<Uint8List>`

## 1.0.13

* Internal changes for consistency with the Dart SDK.

## 1.0.12

* Allow `stream_channel` version 2.x

## 1.0.11

* Fixed description in pubspec.

* Fixed lints in README.md.

## 1.0.10

* Fixed links in README.md.

* Added an example.

* Fixed analysis lints that affected package score.

## 1.0.9

* Set max SDK version to `<3.0.0`.

## 1.0.8

* Remove use of deprecated constant name.

## 1.0.7

* Support the latest dev SDK.

## 1.0.6

* Declare support for `async` 2.0.0.

## 1.0.5

* Increase the SDK version constraint to `<2.0.0-dev.infinity`.

## 1.0.4

* Support `crypto` 2.0.0.

## 1.0.3

* Fix all strong-mode errors and warnings.

* Fix a bug where `HtmlWebSocketChannel.close()` would crash on non-Dartium
  browsers if the close code and reason weren't provided explicitly.

## 1.0.2

* Properly use `BASE64` from `dart:convert` rather than `crypto`.

## 1.0.1

* Add support for `crypto` 1.0.0.

## 1.0.0

* Initial version
