# Pushwoosh Inbox UI

[![GitHub release](https://img.shields.io/github/release/Pushwoosh/pushwoosh-inbox-ui-ios-sdk.svg?style=flat-square)](https://github.com/Pushwoosh/pushwoosh-inbox-ui-ios-sdk/releases)
[![CocoaPods compatible](https://img.shields.io/cocoapods/v/PushwooshInboxUI.svg)](https://cocoapods.org/?q=pushwooshinboxui)
[![Carthage compatible](https://img.shields.io/badge/Carthage-compatible-4BC51D.svg?style=flat)](https://github.com/Carthage/Carthage)

You are welcome to contact [Pushwoosh Support](https://www.pushwoosh.com/contact-us/) if you have any questions regarding Pushwoosh Message Inbox.

## Communication

- If you **need help**, use [Stack Overflow](https://stackoverflow.com/questions/tagged/pushwoosh). (Tag 'pushwoosh')
- If you'd like to **ask a general question**, use [Stack Overflow](https://stackoverflow.com/questions/tagged/pushwoosh).
- If you **found a bug**, _and can provide steps to reliably reproduce it_, open an issue.
- If you **have a feature request**, open an issue.
- If you **want to contribute**, submit a pull request.

## Implementation

PushwooshInboxUI supports multiple methods of installing the library into your project.

### Installation with CocoaPods

[CocoaPods](http://cocoapods.org) is a dependency manager for Objective-C, which automates and simplifies the process of using 3rd-party libraries like PushwooshInboxUI in your projects. See the ["Getting Started" guide for more information](http://docs.pushwoosh.com/docs/native-ios-sdk). You can install it with the following command:

```bash
$ gem install cocoapods
```
> CocoaPods 0.39.0+ is required to build PushwooshInboxUI 5.5.0+.

#### Podfile

To integrate PushwooshInboxUI into your Xcode project using CocoaPods, specify it in your `Podfile`:

```ruby
source 'https://github.com/CocoaPods/Specs.git'
platform :ios, '10.0'

target 'TargetName' do
pod 'PushwooshInboxUI', '~> 5.5'
pod 'Pushwoosh', '~> 5.5'
end
```

Then, run the following command:

```bash
$ pod install
```

### Installation with Carthage

[Carthage](https://github.com/Carthage/Carthage) is a decentralized dependency manager that builds your dependencies and provides you with binary frameworks.

You can install Carthage with [Homebrew](http://brew.sh/) using the following command:

```bash
$ brew update
$ brew install carthage
```

To integrate PushwooshInboxUI into your Xcode project using Carthage, specify it in your `Cartfile`:

```ogdl
github "Pushwoosh/pushwoosh-inbox-ui-ios-sdk" ~> 5.5
```

Run `carthage` to build the framework and drag the built `PushwooshInboxUI.framework` into your Xcode project.

### To show Inbox UI in your app, you can:

* Create `PWIInboxViewController` with the default style
```swift
PWIInboxUI.createInboxController(with: PWIInboxStyle.default())
```
* Specify custom `PWIInboxViewController` class for your `UIViewController` in the storyboard or XIB

#### If you'd like to customize PWIInboxViewController design, please see this class for details: [PWIInboxStyle](https://github.com/Pushwoosh/pushwoosh-inbox-ui-ios-sdk/master/Documentation/PWIInboxStyle.md)

You can change all parameters of PWIInboxStyle to make the inbox match your app's design.

#### Change Log

See this repository's [release tags](https://github.com/Pushwoosh/pushwoosh-inbox-ui-ios-sdk/releases) for a complete change log of every released version.

## License

PushwooshInboxUI is released under the MIT license. See LICENSE for details.
