# Multicast DNS package

[![pub package](https://img.shields.io/pub/v/multicast_dns.svg)](
https://pub.dartlang.org/packages/multicast_dns)

A Dart package to do service discovery over multicast DNS (mDNS), Bonjour, and Avahi.

## Usage
To use this package, add `multicast_dns` as a
[dependency in your pubspec.yaml file](https://flutter.io/platform-plugins/).

## Example

Import the library via
``` dart
import 'package:multicast_dns/mdns_client.dart';
```

Then use the `MDnsClient` Dart class in your code. To see how this is done,
check out the [example app](example/main.dart) or the sample implementations in
the [bin](bin/) directory.
