# Awesome

[![Slack](https://img.shields.io/badge/join-slack-745EAF.svg?style=flat)](http://bit.ly/2B0dEyt)
[![Version](https://img.shields.io/cocoapods/v/AwesomeEnum.svg?style=flat)](http://cocoapods.org/pods/AwesomeEnum)
[![License](https://img.shields.io/cocoapods/l/AwesomeEnum.svg?style=flat)](http://cocoapods.org/pods/AwesomeEnum)
[![Platform](https://img.shields.io/cocoapods/p/AwesomeEnum.svg?style=flat)](http://cocoapods.org/pods/AwesomeEnum)

## 

Super easy to use library containing the brand new FontAwesome 5, completely redesigned for Swift 4

## Slack

Get help using and installing this product on our [Slack](http://bit.ly/2B0dEyt), channel <b>#help-awesome</b>

## Example

To run the example project, clone the repo, and run `pod install` from the Example directory first.

## Installation

Awesome is available through [CocoaPods](http://cocoapods.org). To install
it, simply add the following line to your Podfile:

```ruby
pod 'AwesomeEnum'
```

for Carthage just do:

```ruby
github "LiveUI/Awesome"
```

## Usage

Import will be slightly different for Cocoapods/Carthage. Sorry for the confusion of names but some unreasonable fellow has already registered an `Awesome` pod before us :).

```swift
import AwesomeEnum // Cocoapods
import Awesome // Carthage
```

All icons are available through autogenerated enums like this:

```swift
let image = Awesome.solid.handScissors.asImage(size: 40.0)
// or
let image = Awesome.brand.android.asImage(size: CGSize(width: 40, height: 40), color: .red, backgroundColor: .blue) // :trollface:
// or
let attributedText = Awesome.regular.envelopeOpen.asAttributedText(fontSize: 17, color: .red, backgroundColor: .blue)
```

## Author

Ondrej Rafaj , development@mangoweb.cz

## License

Awesome is available under the MIT license. See the LICENSE file for more info. All fonts are property of Font Awesome!
