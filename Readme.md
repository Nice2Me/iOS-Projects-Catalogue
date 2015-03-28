# iOS Projects Catalogue

This is the catalogue of iOS/Objective-C Open Source projects. I created it to have a fast access to any Mac/iOS-related projects I recently Github-starred or explored.

It will grow as fast as it is possible with my ability to add/explore new projects around the net, Github, etc.

If you liked it, feel free to suggest any new projects that are not
present in the current list. See [Contribution](https://github.com/stanislaw/iOS-Projects-Catalogue/blob/master/Contribution.md).

You may start watching this repo to receive notifications about new incoming projects. New projects are added via Pull Requests to 'new' branch so all watchers of this repository receive corresponding email notifications.

Also I keep another catalogue of projects: it contains [the list of candidates for this
catalogue](https://github.com/stanislaw/iOS-Projects-Catalogue/blob/master/Candidates.md). After I am sure enough that a particular candidate-project deserves its place here, I move it here from the list of Candidates.

Note! This catalogue also includes a number of projects which are not open-source but are still somehow related to a development of iOS/Objective-C applications.

Suggestions are welcome! New projects are welcome!

Last update: 2015-03-28

----

<!-- START doctoc generated TOC please keep comment here to allow auto update -->
<!-- DON'T EDIT THIS SECTION, INSTEAD RE-RUN doctoc TO UPDATE -->
**Table of Contents**  *generated with [DocToc](http://doctoc.herokuapp.com/)*

- [Contents](#contents)
  - [Catalogues](#catalogues)
  - [Objective-C and Cocoa](#objective-c-and-cocoa)
    - [Frameworks](#frameworks)
    - [Extensions for Objective-C and Cocoa frameworks](#extensions-for-objective-c-and-cocoa-frameworks)
    - [Macros utilities](#macros-utilities)
    - [Low level](#low-level)
  - [Dependency Management](#dependency-management)
  - [Auto-updates](#auto-updates)
  - [Design Patterns](#design-patterns)
    - [Promises / Futures / Deferred](#promises--futures--deferred)
    - [Observer / Binding](#observer--binding)
  - [Algorithms](#algorithms)
  - [Data structures](#data-structures)
  - [Conventions / Style guides / Best practices](#conventions--style-guides--best-practices)
    - [Objective-C](#objective-c)
    - [Swift](#swift)
  - [Cross-platform development](#cross-platform-development)
  - [Application Platforms](#application-platforms)
  - [Networking](#networking)
    - [Servers](#servers)
    - [Sockets](#sockets)
    - [Logging](#logging)
    - [Other](#other)
  - [Database](#database)
    - [Core Data](#core-data)
    - [SQLite-based](#sqlite-based)
    - [NoSQL](#nosql)
    - [Key-Value stores](#key-value-stores)
    - [Encryption](#encryption)
  - [Data](#data)
  - [Debugging](#debugging)
    - [Logging](#logging-1)
    - [Core Data](#core-data-1)
  - [Build Tools](#build-tools)
  - [Testing](#testing)
    - [Testing frameworks](#testing-frameworks)
    - [Test Automation](#test-automation)
    - [Stubbing tools](#stubbing-tools)
    - [VCR tools](#vcr-tools)
    - [Other](#other-1)
  - [Deployment](#deployment)
  - [Beta testing](#beta-testing)
  - [Analytics](#analytics)
    - [Providers](#providers)
    - [Crash reporting tools](#crash-reporting-tools)
  - [Command-line tools](#command-line-tools)
  - [Device information](#device-information)
  - [Documentation](#documentation)
  - [Xcode. Tools and Plugins](#xcode-tools-and-plugins)
    - [Plugins](#plugins)
  - [UI](#ui)
    - [Storyboards](#storyboards)
    - [Stylesheets](#stylesheets)
    - [Transitions](#transitions)
    - [Auto Layout](#auto-layout)
    - [UIKit extensions](#uikit-extensions)
  - [Social](#social)
  - [Maps](#maps)
    - [Geometry](#geometry)
    - [Clustering](#clustering)
  - [Graphics](#graphics)
    - [SVG](#svg)
  - [Audio](#audio)
  - [Video](#video)
  - [Games](#games)
  - [Applications](#applications)
    - [Browsers](#browsers)
    - [Graphics](#graphics-1)
  - [Code Examples](#code-examples)
    - [Low-level](#low-level)
  - [Compilers](#compilers)

<!-- END doctoc generated TOC please keep comment here to allow auto update -->

# Contents

## Catalogues

* [Awesome iOS](https://github.com/vsouza/awesome-ios)

> A curated list of awesome iOS frameworks, libraries, tutorials, xcode
plugins and components.

* [Awesome Swift](https://github.com/matteocrippa/awesome-swift)

> A collaborative list of awesome swift resources. Feel free to contribute!

* [open-source-ios-apps](https://github.com/dkhamsing/open-source-ios-apps)

> Collaborative List of Open-Source iOS Apps

* [iOSDevTools](https://github.com/EvgenyKarkan/iOSDevTools)

> Set of repositories for different development tasks.

## Objective-C and Cocoa

### Frameworks

* [AFNetworking](http://afnetworking.com/)

> A delightful networking framework for iOS and OSX

* [ReactiveCocoa](https://github.com/ReactiveCocoa/ReactiveCocoa)

> A framework for composing and transforming streams of values

* [Mantle](https://github.com/github/Mantle)

> Model framework for Cocoa and Cocoa Touch

* [ComponentKit](http://componentkit.org/)

> A React-Inspired View Framework for iOS

* [RestKit](https://github.com/RestKit/RestKit)

> RestKit is a framework for consuming and modeling RESTful web resources
on iOS and OS X 

* [GNUstep](https://github.com/gnustep/gnustep-base)

> GNUstep is a mature Framework, suited both for advanced GUI desktop applications as well as server applications. The framework closely follows Apple's Cocoa (formerly NeXT's OpenStep) APIs but is portable to a variety of platforms and architectures.

* [NimbusKit](http://nimbuskit.info/)

> Nimbus is a toolkit for experienced iOS software designers. It provides well-documented, modular components that solve a number of common iOS software requirements. This includes: a rich text label with hyperlinks; a web view controller; a simple approach to table models, radio groups, and table actions; standardized interapp communication, and powerful debugging tools, amongst many other features.

* [Sparrow-Framework](https://github.com/Gamua/Sparrow-Framework)

> The Open Source Game Engine for iOS http://www.sparrow-framework.org/

* [epam/road-ios-framework](https://github.com/epam/road-ios-framework)

> ROAD - Rapid Objective-C Applications Development
 
### Extensions for Objective-C and Cocoa frameworks

* [libextobjc](https://github.com/jspahrsummers/libextobjc)

> A Cocoa library to extend the Objective-C programming language.

* [ObjectiveSugar](https://github.com/mneorr/ObjectiveSugar)

> ObjectiveC additions for humans. Ruby style.

* [Underscore.m](https://github.com/robb/Underscore.m)

> Underscore.m is a small utility library to facilitate working with common data structures in Objective-C.
It tries to encourage chaining by eschewing the square bracket]]]]]].
It is inspired by the awesome underscore.js.

* [BloodMagic](https://github.com/railsware/BloodMagic)

> Custom attributes for ObjC properties.

* [pandamonia/BlocksKit](https://github.com/pandamonia/BlocksKit)

> The Objective-C block utilities you always wish you had.

* [FoundationKit](https://github.com/foundationkit/FoundationKit)

> Everything that really should be in Foundation, but isn't.
Future-proof with ARC

* [QSKit](https://github.com/quartermaster/QSKit)

> Q Branch’s collection of Cocoa categories and utilities.

* [gh-kit](https://github.com/gabriel/gh-kit)

> Utilities and categories for Objective-C

* [NNKit](https://github.com/numist/NNKit)

> A Swiss Army Knife for Objective-C developers

### Macros utilities

* [robrix/RXPreprocessing](https://github.com/robrix/RXPreprocessing)

> A variety of utilities for the C preprocessor.

* [JREnum](https://github.com/rentzsch/JREnum)

> macros that automate vending an NSString given an enum value (f.x.
MyEnumToString(value))

* [swansontec/map-macro](https://github.com/swansontec/map-macro)

> A recursive C preprocessor macro which performs an operation on each
element of a list

### Low level

* [Hopper](http://www.hopperapp.com/index.html)

> Hopper is a reverse engineering tool for OS X, that lets you disassemble, decompile and debug your 32/64bits Intel Mac, Windows and iOS executables!

* [RuntimeBrowser](https://github.com/nst/RuntimeBrowser)

> Objective-C Runtime Browser, for Mac OS X and iOS

* [nickhutchinson/libdispatch](https://github.com/nickhutchinson/libdispatch)

> Linux port of Apple's open-source concurrency library

* [rentzsch/mach_inject](https://github.com/rentzsch/mach_inject)

> interprocess code injection for Mac OS X

* [rentzsch/mach_override](https://github.com/rentzsch/mach_override)

> runtime function overriding for Mac OS X

* [RDInjectionWizard](https://github.com/rodionovd/RDInjectionWizard)

> Painless code injection for OS X

## Dependency Management

* [CocoaPods](cocoapods.org/)

> The Dependency Manager for Objective C.

* [Carthage](https://github.com/Carthage/Carthage)

> A simple, decentralized dependency manager for Cocoa

## Auto-updates

* [Harpy](https://github.com/ArtSabintsev/Harpy) and [Siren](https://github.com/ArtSabintsev/Siren)

> Notify users when a new version of your iOS app is available, and prompt them with the App Store link.

[Squirrel.Mac](https://github.com/Squirrel/Squirrel.Mac)

> :shipit: Cocoa framework for updating OS X apps :shipit:

[Sparkle](https://github.com/sparkle-project/Sparkle)

> A software update framework for OS X. http://sparkle-project.org/

## Design Patterns

* [Design-Patterns-In-Swift](https://github.com/ochococo/Design-Patterns-In-Swift)

> Design Patterns implemented in Swift

* [java-design-patterns](https://github.com/iluwatar/java-design-patterns)

> Design pattern samples implemented in Java

### Promises / Futures / Deferred

* [PromiseKit](https://github.com/mxcl/PromiseKit)

> A delightful Promises implementation for iOS

* [RXPromise](https://github.com/couchdeveloper/RXPromise)

> An Objective-C Class which implements the Promises/A+ specification.

* [objc-promise](https://github.com/mproberts/objc-promise)

> Objective-C Promises in the CommonJS style

* [deferred](https://github.com/kseebaldt/deferred)

> Async library inspired by CommonJS Promises/A spec

### Observer / Binding

* [BIND](https://github.com/markohlebar/BIND)

Data Binding and MVVM for iOS

* [KVOController](https://github.com/facebook/KVOController)

Simple, modern, thread-safe key-value observing for iOS and OS X.

* [Bond](https://github.com/SwiftBond/Bond)

A Swift binding framework

## Algorithms

* [EvgenyKarkan/EKAlgorithms](https://github.com/EvgenyKarkan/EKAlgorithms)

> EKAlgorithms contains some well known CS algorithms and other stuff.

* [Dijkstra-swift](https://github.com/juliengomes/Dijkstra-swift)

> A swift based implementation of the Dijkstra algorithm

## Data structures

* [TPCircularBuffer](https://github.com/michaeltyson/TPCircularBuffer)

> A simple, fast circular buffer implementation

* [NSTree](https://github.com/carlinyuen/NSTree)
 
> Tree data structure implementation for iOS without using CFTree. Keywords: iOS, tree, algorithms, data structures, binary, b-trees.

## Conventions / Style guides / Best practices

* [The Power of Ten – Rules for Developing Safety Critical Code](http://pixelscommander.com/wp-content/uploads/2014/12/P10.pdf)

> Jet Propulsion Laboratory – scientific institution making a lot of research and development for NASA. JPL have been developing software for most of unmanned missions in the field of deep space and other planets exploaration. Their portfolio includes such famous missons as Curiosity Mars rover and Voyager probe which left solar system after 25 years of flight and still providing scientific information. High level of automatization and long duration of missions led to superior demands to software quality. As a result of JPL amazing experience a set of code guidelines was developed and published recently.

### Objective-C

* [github/objective-c-conventions](https://github.com/github/objective-c-conventions)

> Coding conventions for Objective-C projects.

* [NYTimes/objective-c-style-guide](https://github.com/NYTimes/objective-c-style-guide)

> The New York Times Mobile Team’s Objective-C Style Guide.

* [objc-zen-book](https://github.com/objc-zen/objc-zen-book)

> Zen and the Art of the Objective-C Craftsmanship

* [iwasrobbed/Objective-C-CheatSheet](https://github.com/iwasrobbed/Objective-C-CheatSheet)

> A quick reference cheat sheet for common, high level topics in Objective-C.

### Swift

* [github/swift-style-guide](https://github.com/github/swift-style-guide)

> Style guide & coding conventions for Swift projects

* [raywenderlich/swift-style-guide](https://github.com/raywenderlich/swift-style-guide)

> The official Swift style guide for raywenderlich.com.

## Cross-platform development

* [Apportable](http://www.apportable.com/)

> Objective-C for Android. Write your apps entirely in Objective-C. Share the same code on iOS and Android. 

* [Xamarin](https://xamarin.com/)

> Create Native iOS, Android, Mac and Windows apps in C#.

* [Marmalade Juice](https://www.madewithmarmalade.com/products/juice)

> Marmalade Juice is a new and innovative technology which gives developers the ability to recompile their iOS projects natively for Android. And, because there is no need for laborious re-writing, you can focus on making your game the best it can be. 

## Application Platforms

* [Parse](https://parse.com/)

> The complete mobile app platform Focus on creating unique & engaging apps on any platform. We take care of everything else your app needs, from the core of your app to analytics and push notifications.

* [C2Call](https://www.c2call.com/en/)

> C2Call empowers your apps' communication with its cutting-edge, cross-platform 7-way Group Video Calling, Voice and Instant Messaging featured technology for Mobiles, Tablets and Desktops.

## Networking

* [Alamofire](https://github.com/Alamofire/Alamofire)

> Elegant HTTP Networking in Swift

### Servers

* [CocoaHTTPServer](https://github.com/robbiehanson/CocoaHTTPServer)

> A small, lightweight, embeddable HTTP server for Mac OS X or iOS
applications

* [GCDWebServer](https://github.com/swisspol/GCDWebServer)

> Lightweight GCD based HTTP server for OS X & iOS (includes web based
uploader & WebDAV server)

### Sockets

* [CocoaAsyncSocket](https://github.com/robbiehanson/CocoaAsyncSocket)

> Asynchronous socket networking library for Mac and iOS

* [SocketRocket](https://github.com/square/SocketRocket)
  
> A conforming Objective-C WebSocket client library.

* [fast-socket](https://github.com/dreese/fast-socket)

> A fast, synchronous Objective-C wrapper around BSD sockets for iOS and
OS X.

* [CocoaPort](https://github.com/chrisdevereux/CocoaPort)

> An asynchronous, futures-based distributed objects library for Objective-C

### Logging

* [AFHTTPRequestOperationLogger](https://github.com/AFNetworking/AFHTTPRequestOperationLogger)

> AFNetworking Extension for HTTP Request Logging

### Other 

* [socket.IO-objc](https://github.com/pkyeck/socket.IO-objc)

> socket.io v0.7.2+ for iOS devices

* [tonymillion/Reachability](https://github.com/tonymillion/Reachability)

> ARC and GCD Compatible Reachability Class for iOS and MacOS. Drop in
replacement for Apple Reachability

* [CocoaSPDY](https://github.com/twitter/CocoaSPDY)

> SPDY for iOS and OS X

* [masscan](https://github.com/robertdavidgraham/masscan)

> TCP port scanner, spews SYN packets asynchronously, scanning entire Internet in under 5 minutes.

## Database

* [realm-cocoa](https://github.com/realm/realm-cocoa)

> Realm is a mobile database: a replacement for Core Data & SQLite

* [etoile/CoreObject](https://github.com/etoile/CoreObject)

> Distributed version control + object persistence framework http://coreobject.org

### Core Data

* [ObjectiveRecord](https://github.com/mneorr/ObjectiveRecord)

> A lightweight Active Record - style of managing CoreData objects.

### SQLite-based 

* [FMDB](https://github.com/ccgus/fmdb)

> A Cocoa / Objective-C wrapper around SQLite

* [FCModel](https://github.com/marcoarment/FCModel)

> An alternative to Core Data for people who like having direct SQL access.

* [iActiveRecord](https://github.com/AlexDenisov/iActiveRecord)

> ActiveRecord for iOS without CoreData, only SQLite.

### NoSQL

* [Couchbase Lite](https://github.com/couchbase/couchbase-lite-ios)

> Couchbase Lite is an embedded lightweight, document-oriented (NoSQL),
syncable database engine.  

* [NyaruDB](https://github.com/kelp404/NyaruDB)

> A simple NoSQL database(key-value pair) in Objective-C. It runs on iOS and OS X.

### Key-Value stores

* [YapDatabase](https://github.com/yaptv/YapDatabase)
 
> YapDatabase is a "key/value store and MORE" built atop sqlite for iOS & Mac.

* [NULevelDB](https://github.com/nulayer/NULevelDB)

> Objective-C interface to Google's LevelDB key/value embedded database

* [kvdb](https://github.com/colinyoung/kvdb)

> a key-value object store backed by sqlite3 for ios

### Encryption

* [SQLCipher](https://github.com/sqlcipher/sqlcipher)

> SQLCipher is an SQLite extension that provides 256 bit AES encryption of database files.  http://sqlcipher.net/


## Data

* [RestKit/RKValueTransformers](https://github.com/RestKit/RKValueTransformers)

> A powerful value transformation API extracted from RestKit

* [mattt/TransformerKit](https://github.com/mattt/TransformerKit)

> A block-based API for NSValueTransformer, with a growing collection of
useful examples.

* [nicklockwood/FastCoding](https://github.com/nicklockwood/FastCoding)

> A faster and more flexible binary file format replacement for Property
Lists and JSON

* [nicklockwood/AutoCoding](https://github.com/nicklockwood/AutoCoding)

> AutoCoding is a category on NSObject that provides automatic support
for NSCoding and NSCopying to every object.

* [EasyMapping](https://github.com/lucasmedeirosleite/EasyMapping)

> The easiest way to marshall and unmarshall Dictionary representations
such as JSON representation

* [FastEasyMapping](https://github.com/Yalantis/FastEasyMapping)

> EasyMapping fork. [From JSON to Core Data Fast and Effectively](http://yalantis.com/blog/2014/03/17/from-json-to-core-data-fast-and-effectively/(

* [pegkit](https://github.com/itod/pegkit)

> 'Parsing Expression Grammar' toolkit for Cocoa/Objective-C

* [ParseKit](https://github.com/itod/parsekit/)

> Objective-C Tokenizer and Parser Generator. Supports Grammars.

## Debugging

* [PLCrashReporter](https://www.plcrashreporter.org/)

> Plausible CrashReporter provides an in-process crash reporting framework for use on both iOS and Mac OS X, and powers most of the crash reporting services available for iOS, including HockeyApp, Flurry, and Crittercism. 

* [facebook/chisel](https://github.com/facebook/chisel)

> Chisel is a collection of LLDB commands to assist debugging iOS apps.

* [FLEX](https://github.com/Flipboard/FLEX)

> An in-app debugging and exploration tool for iOS

* [heardrwt/RHObjectiveBeagle](https://github.com/heardrwt/RHObjectiveBeagle/)

> Beagle is an Objective C debugging tool that can sniff out class instances on the heap.

* [VMInstrumenter](https://github.com/vittoriom/VMInstrumenter)

> A simple Objective-C singleton to instrument, protect, trace, and
suppress selectors at runtime

* [dyci-main](https://github.com/DyCI/dyci-main)

> Dynamic code injection Tool

* [Xtrace](https://github.com/johnno1962/Xtrace)

> Trace Objective-C method calls by class or instance)

### Logging

* [NSLogger](https://github.com/fpillet/NSLogger)

> A modern, flexible logging tool

* [CocoaLumberjack](https://github.com/robbiehanson/CocoaLumberjack)

> A fast & simple, yet powerful & flexible logging framework for Mac and iOS

* [XLFacility](https://github.com/swisspol/XLFacility)

> Elegant and extensive logging facility for OS X & iOS (includes database, Telnet and HTTP servers)

* [JRLog](https://github.com/rentzsch/JRLog)

> Simple but flexible Log4J-like logging system for Objective-C

* [UrbanApps/UALogger](https://github.com/UrbanApps/UALogger)

> A powerful and flexible logging utility for Mac/iOS apps

* [MTLog](https://github.com/icanzilb/MTLog)

> NSLog replacement for coders!

* [rabovik/ATLog](https://github.com/rabovik/ATLog)

> Log common structures without boring conversions.
ATLog(@"%@",CGPointMake(1,1)); // No need for NSStringFromCGPoint.

### Core Data

* [GDCoreDataConcurrencyDebugging](https://github.com/GrahamDennis/GDCoreDataConcurrencyDebugging)

> GDCoreDataConcurrencyDebugging helps you find cases where
NSManagedObject's are being called on the wrong thread or dispatch
queue.

## Build Tools

* [bazel](https://github.com/google/bazel)

> Correct, reproducible, and fast builds for everyone.

## Testing

### Testing frameworks

* [Kiwi](https://github.com/allending/Kiwi)

> BDD for iOS

* [specta](https://github.com/specta/specta)

> A light-weight TDD / BDD framework for Objective-C & Cocoa

* [Cedar](https://github.com/pivotal/cedar)

> BDD-style testing using Objective-C

* [Quick](https://github.com/Quick/Quick)

> The Swift (and Objective-C) testing framework.

* [Unity](https://github.com/ThrowTheSwitch/Unity)

> Simple Unit Testing for C http://throwtheswitch.org/

### Test Automation

* [Frank](https://github.com/moredip/Frank)

> Automated acceptance tests for native iOS apps.

* [KIF](https://github.com/kif-framework/KIF)

> Keep It Functional - An iOS Functional Testing Framework

* [calabash-ios](https://github.com/calabash/calabash-ios)

> Calabash is an automated testing technology for Android and iOS native
and hybrid applications.

* [Subliminal](https://github.com/inkling/Subliminal)

> An understated approach to iOS integration testing.

* [ios-driver](http://ios-driver.github.io/ios-driver/index.html)

> IOS automation for native, hybrid and mobile web.

> Test any IOS native, hybrid, or mobile web application using the
Selenium / Webdriver API. IOS automation is as easy as automation for a
browser, due to reuse of the well known API. You can reuse the helper
classes from your web tests to i.e. create data, and follow the same
design patterns you're used to (Page Object etc.). 

* [Appium](http://appium.io/)

> Appium is an open source test automation framework for use with native and hybrid mobile apps.
It drives iOS and Android apps using the WebDriver JSON wire protocol.

### Stubbing tools

* [OHHTTPStubs](https://github.com/AliSoftware/OHHTTPStubs)

> Stub your network requests easily! Test your apps with fake network data and custom response time, response code and headers!

* [Nocilla](https://github.com/luisobo/Nocilla)

> Testing HTTP requests has never been easier. Nocilla: Stunning HTTP
stubbing for iOS and Mac OS X.

* [objc-mocktail](https://github.com/square/objc-mocktail)

> A simple(r) way to stub out HTTP servers in your Objective-C app.

* [URLMock](https://github.com/twotoasters/URLMock)

> A Cocoa framework for mocking and stubbing URL requests and responses.

### VCR tools

* [VCRURLConnection](https://github.com/dstnbrkr/VCRURLConnection)

> VCRURLConnection is an iOS and OSX API to record and replay HTTP
interactions, inspired by VCR for ruby

* [CCLRequestReplay](https://github.com/cocodelabs/CCLRequestReplay)

> Powerful Objective-C library to replay HTTP responses

### Other

* [xctasks](https://github.com/layerhq/xctasks)

> Simple project automation for the sophisticated Xcode hacker

* [OCMockito](https://github.com/jonreid/OCMockito)

> Mockito for Objective-C: creation, verification and stubbing of mock objects

* [neilco/RedGreen](https://github.com/neilco/RedGreen)

> RedGreen is an extension library for SenTestKit that makes the test
output easier to parse by humans.

* [JPSimulatorHacks](https://github.com/plu/JPSimulatorHacks)

> Automatically grant access to addressbook/photos in your tests (Simulator only)

* [mneorr/XCPretty](https://github.com/mneorr/XCPretty)

> Flexible and fast xcodebuild formatter

* [TUDelorean](https://github.com/tuenti/TUDelorean)

> TUDelorean helps you test your time-dependent Objetive-C code allowing
you travel anywhere in time.

## Deployment

* [Air-Test](https://github.com/rjyo/Air-Test)

> A tool that will make a lot of iPhone/iPad developers' life easier. It
shares your app over-the-air in a WiFi network. Bonjour is used and no
configuration is needed.

* [iOStream](https://github.com/johnmoore/iOStream)

> Presenting mobile apps is a pain in the ass. So is collaborating
remotely with mobile developers. Don't let clunky hardware cameras and
unrealistic simulators get in your way. Introducing iOStream. Mobile
presentations made easy. Install the SDK and start streaming now.

## Beta testing

* [Ubertesters](http://ubertesters.com/)

> Complete mobile beta testing solution. One platform to orchestrate your entire mobile testing process. 

## Analytics

* [AnalyticsKit](https://github.com/twobitlabs/AnalyticsKit)

> Analytics framework for iOS

* [ARAnalytics](https://github.com/orta/ARAnalytics)

> Simplify your iOS analytics

### Providers

* [Flurry](http://www.flurry.com)

> INDUSTRY-LEADING APP ANALYTICS FOR FREE

* [mixpanel/mixpanel-iphone](https://github.com/mixpanel/mixpanel-iphone)

> iPhone tracking library for Mixpanel Analytics. http://mixpanel.com

* [bitstadium/HockeySDK-iOS](https://github.com/bitstadium/HockeySDK-iOS)

> The official iOS SDK for the HockeyApp service (Releases are in the master branch, current development in the default develop branch) http://hockeyapp.net/releases

* [Countly/countly-sdk-ios](https://github.com/Countly/countly-sdk-ios)

> Countly Mobile Analytics - iOS SDK http://count.ly

* [ZeoInsight](http://zeoinsight.com/)

> Intelligent Analytics for your Mac, Windows, Android, iOS, Unity, Action Script apps 

### Crash reporting tools

* [Crashlytics](https://github.com/crashlytics)

> ...the most powerful, yet lightest weight crash reporting solution.

* [bugsnag-cocoa](https://github.com/bugsnag/bugsnag-cocoa)

> Bugsnag notifier for iOS and OSX apps, https://bugsnag.com/

* [KSCrash](https://github.com/kstenerud/KSCrash)

> The Ultimate iOS Crash Reporter

## Command-line tools

* [xctool](https://github.com/facebook/xctool)

> xctool is a replacement for Apple's xcodebuild that makes it easier to build and test iOS and Mac projects.

* [nomad-cli](http://nomad-cli.com/)
> world-class command line utilities for iOS development
  * [Cupertino](https://github.com/nomad/cupertino)
  
    > Automate administrative tasks that you would normally have to do
through the Apple Dev Center website. Life's too short to manage device
identifiers by hand!
  
  * [Houston](https://github.com/nomad/houston)
  
    > Send push notifications from the command line. Simply provide your
credentials, construct your message, and 3...2...1... blastoff.

  * [Dubai](https://github.com/nomad/dubai)

    > Generate Passbook .pkpass files with ease. Rapidly iterate on the
design and content of your passes, or generate one-offs on the fly.

  * [Venice](https://github.com/nomad/venice)

    > Secure your In-App-Purchases by verifying App Store purchase
receipts, and retrieving the information associated with receipt data.

  * [Shenzhen](https://github.com/nomad/shenzhen)

    > Create development builds and then distribute their .ipa files over
TestFlight, HockeyApp, Amazon S3, or FTP. Get new builds out to testers
and enterprises in seconds.

* [phonegap/ios-sim](https://github.com/phonegap/ios-sim)

> Command Line Launcher for the iOS Simulator.

* [Sim-Launcher](https://github.com/moredip/Sim-Launcher)

> tiny little sinatra app to allow launching an iOS app in the simulator via HTTP

* [fruitstrap](https://github.com/ghughes/fruitstrap/)

> Install and debug iPhone apps from the command line, without using Xcode

## Device information

* [RSEnvironment](https://github.com/rabovik/RSEnvironment)

> Most common environment checks in one place: system version, retina support, UI flat mode, device models and so on.

* [GBDeviceInfo](https://github.com/lmirosevic/GBDeviceInfo)

> Detects the hardware, software and display of the current iOS or Mac OS X device at runtime.

## Documentation

* [jazzy](https://github.com/realm/jazzy)

> Soulful docs for Swift & Objective-C

## Xcode. Tools and Plugins

* [Alcatraz](https://github.com/supermarin/Alcatraz)

> Package manager for Xcode http://alcatraz.io/

### Plugins

* [ClangFormat-Xcode](https://github.com/travisjeffery/ClangFormat-Xcode)
  
> Xcode plug-in to to use clang-format from in Xcode and consistently format your code with Clang

* [https://github.com/questbeat/Lin-Xcode5](https://github.com/questbeat/Lin-Xcode5)

> A Localization Manager for Xcode 5

* [XcodeColors](https://github.com/robbiehanson/XcodeColors)

> XcodeColors allows you to use colors in the Xcode debugging console.
It's designed to aid in the debugging process.


## UI

* [MMDrawerController](https://github.com/mutualmobile/MMDrawerController)

> A lightweight, easy to use, Side Drawer Navigation Controller

* [pkluz/PKRevealController](https://github.com/pkluz/PKRevealController)

> PKRevealController (ex. ZUUIRevealController) is a delightful view controller container for iOS, enabling you to present multiple controllers on top of one another.

* [nicklockwood/FXImageView](https://github.com/nicklockwood/FXImageView)

> FXImageView is a class designed to simplify the application of common visual effects such as reflections and drop-shadows to images, and also to help the performance of image loading by handling it on a background thread.

* [steipete/PSPDFTextView](https://github.com/steipete/PSPDFTextView)

> A subclass of UITextView that fixes the most glaring problems from iOS 7 and 7.1.

* [TOMSMorphingLabel](https://github.com/TomKnig/TOMSMorphingLabel)

> Configurable morphing transitions between text values of a label.

* [BFWindow](https://github.com/beefon/BFWindow)

> NSWindow subclass that allows you to apply Core Animation effects.

### Storyboards

* [rob-brown/RBStoryboardLink](https://github.com/rob-brown/RBStoryboardLink)

> Makes transitioning between storyboards possible. [Using Multiple Storyboards in iOS Development](http://spin.atomicobject.com/2014/02/18/ios-storyboards-xcode5/)

### Stylesheets

* [UISS](https://github.com/robertwijas/UISS)

> UIAppearance Stylesheets

* [nui](https://github.com/tombenner/nui)

> Style iOS apps with a stylesheet, similar to CSS

### Transitions 

* [ADTransitionController](https://github.com/applidium/ADTransitionController)

> UINavigationController with custom transitions

* [travisjeffery/TRVSNavigationControllerTransition](https://github.com/travisjeffery/TRVSNavigationControllerTransition)

> Push/Pop transition for entire UINavigationController views.

### Auto Layout

* [PureLayout](https://github.com/smileyborg/PureLayout)

> The ultimate API for iOS & OS X Auto Layout — impressively simple,
immensely powerful.

### UIKit extensions

* [hfossli/AGGeometryKit](https://github.com/hfossli/AGGeometryKit)

> A bundle of small classes which enriches your possibilities with UIKit
and CoreAnimation.

* [UIImage-Categories](https://github.com/mbcharbonneau/UIImage-Categories)
   
> An fork of Trevor Harmon's UIImage category methods, updated for the
latest versions of iOS.


## Social

* [calebd/SimpleAuth](https://github.com/calebd/SimpleAuth)

> Simple social authentication for iOS. http://simpleauth.io

* [overshare-kit](https://github.com/overshare/overshare-kit)

> A soup-to-nuts sharing library for iOS.

## Maps

* [calloutview](https://github.com/nfarina/calloutview)

> A lightweight callout view class for iOS mimicking UICalloutView.

### Geometry

* [Archimedes](https://github.com/github/Archimedes)

> Geometry functions for Cocoa and Cocoa Touch


### Clustering

* [kingpin](https://github.com/itsbonczek/kingpin)

> A drop-in MapKit/MKAnnotation pin clustering library for MKMapView on iOS

* [thoughtbot/TBAnnotationClustering](https://github.com/thoughtbot/TBAnnotationClustering)

> Example App: How To Efficiently Display Large Amounts of Data on iOS Maps, http://robots.thoughtbot.com/how-to-handle-large-amounts-of-data-on-maps/

* [QTree-objc](https://github.com/blackm00n/QTree-objc)

> Library for location-based clustering of data using Quadtree written
in Objective-C

* [ADClusterMapView](https://github.com/applidium/ADClusterMapView)

> MKMapView with clustering

* [OCMapView](https://github.com/yinkou/OCMapView)

> Simple and easy to use clustering mapView for iOS

* [MarcoSero/MSMapClustering](https://github.com/MarcoSero/MSMapClustering)

> A subclass of MKMapView to cluster annotations.

* [map_index](https://github.com/poteryaysya/map_index)

> Fast map clusterization build on top of Region QuadTree.

## Graphics

### SVG

* [SVGKit](https://github.com/SVGKit/SVGKit)

> Display and interact with SVG Images on iOS / OS X, using native
rendering (CoreAnimation)

* [PocketSVG](https://github.com/arielelkin/PocketSVG)

> Easily convert your SVG files into CGPaths, CAShapeLayers, and UIBezierCurves.

## Audio

* [EZAudio](https://github.com/syedhali/EZAudio)

> An iOS and OSX audio visualization framework built upon Core Audio useful for anyone doing real-time, low-latency audio processing and visualizations.

* [novocaine](https://github.com/alexbw/novocaine)

> Painless high-performance audio on iOS and Mac OS X. http://alexbw.github.com/novocaine/

* [AudioModem](https://github.com/applidium/AudioModem)

> Transfer data using microphone/speaker on iOS devices

* [FreeStreamer](https://github.com/muhku/FreeStreamer)

> A low-memory footprint audio streamer for iOS and OS X

* [AudioKit](https://github.com/audiokit/AudioKit) 

> Open-source audio synthesis, processing, & analysis platform. http://audiokit.io/

* [ObjectAL-for-iPhone](https://github.com/kstenerud/ObjectAL-for-iPhone)

> Mac and iOS Audio development, minus the headache. ObjectAL is the easy Objective-C interface to OpenAL, AVAudioPlayer, and audio session management. http://kstenerud.github.com/ObjectAL-for-iPhone

## Video

[XCDYouTubeVideoPlayerViewController](https://github.com/0xced/XCDYouTubeVideoPlayerViewController)

> YouTube video player for iPhone and iPad

## Games

* [FlappyBlock](https://github.com/joeblau/FlappyBlock)

> This is an iOS verion of the "smash hit" Flappy Bird built using
iOS7's physics engine.

* [FlapFlap](https://github.com/nathanborror/FlapFlap)

> Flappy Bird Clone for learning purposes—feel free to play along.

* [ScaryFlight](https://github.com/EvgenyKarkan/ScaryFlight)

> Just another yet FlappyBird-style game.

## Applications

* [artsy/eigen](https://github.com/artsy/eigen)

> The Art World in Your Pocket

* [mbus](https://github.com/jonahgrant/mbus)

> iOS implementation of the University of Michigan's bus dispatch system

* [mtigas/iOS-OnionBrowser](https://github.com/mtigas/iOS-OnionBrowser)

> An open-source, privacy-enhancing web browser for iOS, utilizing the
Tor anonymity network

* [irccloud/ios](https://github.com/irccloud/ios)

> IRCCloud iOS App

* [telegram](https://github.com/overtake/telegram)

> Source code of Telegram for OSX  http://telegram.org

### Browsers

* [mozilla/firefox-ios](https://github.com/mozilla/firefox-ios)

> Firefox for iOS

### Graphics

* [Inkpad](https://github.com/sprang/Inkpad)

> Vector illustration app for the iPad.

* [Brushes](https://github.com/sprang/Brushes)

> Painting app for the iPhone and iPad.

## Code Examples

* [kharrison/CodeExamples](https://github.com/kharrison/CodeExamples)

> Code Examples http://useyourloaf.com

* [shu223/iOS7-Sampler](https://github.com/shu223/iOS7-Sampler)

> Code examples for the new functions of iOS 7.

* [ShinobiControls/iOS7-day-by-day](https://github.com/ShinobiControls/iOS7-day-by-day)

> Repo containing the sample projects associated with the iOS7 Day-by-Day blog series

* [CustomSegue](https://github.com/Phillipus/CustomSegue)

> iOS Custom Segue and Unwind Segue with animation

* [iOSUnwindSegueProgramatically](https://github.com/bradley/iOSUnwindSegueProgramatically)

> Basic example of calling and unwinding a segue programatically.

* [TableViewCellWithAutoLayoutiOS8](https://github.com/smileyborg/TableViewCellWithAutoLayoutiOS8)

> Sample project demonstrating self-sizing table view cells in iOS 8
using Swift and Objective-C.

* [UITableViewController-Containment-Demo](https://github.com/rnystrom/UITableViewController-Containment-Demo)

> This is a sample project showing how to contain a
UITableViewController in another VC with a Search Bar + Display
Controller working as if it were all in a UITableViewController.

* [intentions](https://github.com/chriseidhof/intentions)

> From "Intentions: An experiment in Ultralight View Controllers" http://chris.eidhof.nl/posts/intentions.html

### Low-level

* [richardjrossiii/iOSAppInAssembly](https://github.com/richardjrossiii/iOSAppInAssembly)

> An iOS app in assembly

* [richardjrossiii/CBasediOSApp](https://github.com/richardjrossiii/CBasediOSApp)

> Creating an iOS app in pure C

## Compilers

* [8cc](https://github.com/rui314/8cc)

A Small C Compiler
