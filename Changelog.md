# Changelog

## [Unreleased]

## [2.0.1] - 08 Jul 2020

### Changed

- Include supported Swift versions 4 and 5, in the Package manifest, by setting `swiftLanguageVersions: [4, 5]`

## [2.0.0] - 06 Jul 2020

### Added

- A dependency to the `RealModule` from the [swift-numerics package](https://github.com/apple/swift-numerics), in order to use the `Real` protocol.
- Support for Xcode 12 beta and Swift tools version v5.2

### Changed

- The generic `Curve` type and its properties are now constrained to types conforming to the `Real` protocol, instead of `FloatingPointMath`.
- Improved test coverage, with testing for `Float80` and `Double` arguments.

### Removed - Breaking

- `FloatingPointMath` protocol has been removed from the implementation and has been replaced with the `Real` protocol.

## [1.0.2] - 15 May 2020

### Changed

- Improve the maths of the back ease out curve, for smother animations.

## [1.0.1] - 8 Aug 2019

### Fixed

- Undeclared type XCTestCaseEntry build error when testing on iOS.

## [1.0.0] - 28 Jun 2019

### Added

- Swift Package Manager integration.

## [0.1.0] - 29 Mar 2019

### Added

- Add support for Xcode 10.2 and Swift 5.

[Unreleased]: https://github.com/manuelCarlos/Easing/compare/2.0.1...head
[2.0.1]: https://github.com/manuelCarlos/Easing/compare/2.0.0...2.0.1
[2.0.0]: https://github.com/manuelCarlos/Easing/compare/1.0.1...2.0.0
[1.0.2]: https://github.com/manuelCarlos/Easing/compare/1.0.1...1.0.2
[1.0.1]: https://github.com/manuelCarlos/Easing/compare/1.0.0...1.0.1
[1.0.0]: https://github.com/manuelCarlos/Easing/compare/0.1.0...1.0.0
[0.1.0]: https://github.com/manuelCarlos/Easing/compare/0.0.8...0.1.0


[better changelog]: https://keepachangelog.com
