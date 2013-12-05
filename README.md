iOS-Projects-Catalogue
======================

This is my collection of iOS/Objective-C Open Source projects. I prefer keeping it in a separate repository to have a fast access to any projects I recently Github-starred or explored.

It will grow as fast as it is possible with my ability to add new projects I am already aware of and my ability to explore new projects around the net, Github, etc.

If you liked it, feel free to suggest any new projects that are not present in the current list.

Also I keep another catalogue of projects: it contains [the list of candidates for this catalogue](https://github.com/stanislaw/iOS-Projects-Catalogue/blob/master/CANDIDATES.md). After I am sure enough that a particular candidate-project deserves its place here, I move it here from the list of Candidates.

----

## Objective-C and Cocoa

### Frameworks

* [GNUstep](https://github.com/gnustep/gnustep-base)

> GNUstep is a mature Framework, suited both for advanced GUI desktop applications as well as server applications. The framework closely follows Apple's Cocoa (formerly NeXT's OpenStep) APIs but is portable to a variety of platforms and architectures.

* [AFNetworking](http://afnetworking.com/)

> A delightful networking framework for iOS and OSX

* [RestKit](https://github.com/RestKit/RestKit)

> RestKit is a framework for consuming and modeling RESTful web resources
on iOS and OS X 

* [ReactiveCocoa](https://github.com/ReactiveCocoa/ReactiveCocoa)

> A framework for composing and transforming streams of values

* [NimbusKit](http://nimbuskit.info/)

> Nimbus is a toolkit for experienced iOS software designers. It provides well-documented, modular components that solve a number of common iOS software requirements. This includes: a rich text label with hyperlinks; a web view controller; a simple approach to table models, radio groups, and table actions; standardized interapp communication, and powerful debugging tools, amongst many other features.

### Extensions for Objective-C and Cocoa frameworks

* [libextobjc](https://github.com/jspahrsummers/libextobjc)

> A Cocoa library to extend the Objective-C programming language.

* [ObjectiveSugar](https://github.com/mneorr/ObjectiveSugar)

> ObjectiveC additions for humans. Ruby style.

### Libraries implementing Promises pattern

* [RXPromise](https://github.com/couchdeveloper/RXPromise)

> An Objective-C Class which implements the Promises/A+ specification.

### Macros utilities

* [JREnum](https://github.com/rentzsch/JREnum)

> macros that automate vending an NSString given an enum value (f.x.
MyEnumToString(value))

### Conventions / Style guides

* [github/objective-c-conventions](https://github.com/github/objective-c-conventions)

> Coding conventions for Objective-C projects.

* [NYTimes/objective-c-style-guide](https://github.com/NYTimes/objective-c-style-guide)

> The New York Times Mobile Team’s Objective-C Style Guide.

----

## Networking

### HTTP servers

* [CocoaHTTPServer](https://github.com/robbiehanson/CocoaHTTPServer)

> A small, lightweight, embeddable HTTP server for Mac OS X or iOS
applications

### Socket libraries

* [CocoaAsyncSocket](https://github.com/robbiehanson/CocoaAsyncSocket)

> Asynchronous socket networking library for Mac and iOS

* [SocketRocket](https://github.com/square/SocketRocket)
  
> A conforming Objective-C WebSocket client library.

* [fast-socket](https://github.com/dreese/fast-socket)

> A fast, synchronous Objective-C wrapper around BSD sockets for iOS and
OS X.

* [CocoaPort](https://github.com/chrisdevereux/CocoaPort)

> An asynchronous, futures-based distributed objects library for Objective-C

### Network logging

* [AFHTTPRequestOperationLogger](https://github.com/AFNetworking/AFHTTPRequestOperationLogger)

> AFNetworking Extension for HTTP Request Logging

----

## Data layer

* [github/Mantle](https://github.com/github/Mantle)

> Model framework for Cocoa and Cocoa Touch

### SQLite-based projects / Alternatives to CoreData

* [FMDB](https://github.com/ccgus/fmdb)

> A Cocoa / Objective-C wrapper around SQLite

* [FCModel](https://github.com/marcoarment/FCModel)

> An alternative to Core Data for people who like having direct SQL access.

* [ObjectiveRecord](https://github.com/mneorr/ObjectiveRecord)

> A lightweight Active Record - style of managing CoreData objects.

* [iActiveRecord](https://github.com/AlexDenisov/iActiveRecord)

> ActiveRecord for iOS without CoreData, only SQLite.

### Key-value store

* [YapDatabase](https://github.com/yaptv/YapDatabase)
 
> YapDatabase is a "key/value store and MORE" built atop sqlite for iOS & Mac.

* [NyaruDB](https://github.com/kelp404/NyaruDB)

> A simple NoSQL database(key-value pair) in Objective-C. It runs on iOS and OS X.

* [NULevelDB](https://github.com/nulayer/NULevelDB)

> Objective-C interface to Google's LevelDB key/value embedded database

* [kvdb](https://github.com/colinyoung/kvdb)

> a key-value object store backed by sqlite3 for ios

----

## Debugging tools

* [VMInstrumenter](https://github.com/vittoriom/VMInstrumenter)

> A simple Objective-C singleton to instrument, protect, trace, and
suppress selectors at runtime

### Logging

* [NSLogger](https://github.com/fpillet/NSLogger)

> A modern, flexible logging tool

* [CocoaLumberjack](https://github.com/robbiehanson/CocoaLumberjack)

> A fast & simple, yet powerful & flexible logging framework for Mac and iOS

* [JRLog](https://github.com/rentzsch/JRLog)

> Simple but flexible Log4J-like logging system for Objective-C

* [UrbanApps/UALogger](https://github.com/UrbanApps/UALogger)

> A powerful and flexible logging utility for Mac/iOS apps

----

## Testing

### Testing frameworks

* [Kiwi](https://github.com/allending/Kiwi)

> BDD for iOS

* [Cedar](https://github.com/pivotal/cedar)

> BDD-style testing using Objective-C

### Test Automation

* [Frank](https://github.com/moredip/Frank)

> Automated acceptance tests for native iOS apps.

* [KIF](https://github.com/kif-framework/KIF)

> Keep It Functional - An iOS Functional Testing Framework

* [calabash-ios](https://github.com/calabash/calabash-ios)

> Calabash is an automated testing technology for Android and iOS native
and hybrid applications.

### Stubbing tools

* [OHHTTPStubs](https://github.com/AliSoftware/OHHTTPStubs)

> Stub your network requests easily! Test your apps with fake network data and custom response time, response code and headers!

* [Nocilla](https://github.com/luisobo/Nocilla)

> Testing HTTP requests has never been easier. Nocilla: Stunning HTTP
stubbing for iOS and Mac OS X.

### VCR tools

* [VCRURLConnection](https://github.com/dstnbrkr/VCRURLConnection)

> VCRURLConnection is an iOS and OSX API to record and replay HTTP
interactions, inspired by VCR for ruby

----

## Deployment

* [Air-Test](https://github.com/rjyo/Air-Test)

> A tool that will make a lot of iPhone/iPad developers' life easier. It
shares your app over-the-air in a WiFi network. Bonjour is used and no
configuration is needed.

----

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

> Install and debug iPhone apps from the command line, without using
Xcode

----

## Analytics

[AnalyticsKit](https://github.com/twobitlabs/AnalyticsKit)

> Analytics framework for iOS

[ARAnalytics](https://github.com/orta/ARAnalytics)

> Simplify your iOS analytics

----

## UI

* [ADTransitionController](https://github.com/applidium/ADTransitionController)

> UINavigationController with custom transitions

### UIKit extensions

* [UIImage-Categories](https://github.com/mbcharbonneau/UIImage-Categories)
   
> An fork of Trevor Harmon's UIImage category methods, updated for the
latest versions of iOS.

### Maps

#### Clustering

* [kingpin](https://github.com/itsbonczek/kingpin)

> A drop-in MapKit/MKAnnotation pin clustering library for MKMapView on iOS

* [ADClusterMapView](https://github.com/applidium/ADClusterMapView)

> MKMapView with clustering

* [OCMapView](https://github.com/yinkou/OCMapView)

> Simple and easy to use clustering mapView for iOS

---- 

## Graphics

* [SVGKit](https://github.com/SVGKit/SVGKit)

> Display and interact with SVG Images on iOS / OS X, using native
rendering (CoreAnimation)

----

## Applications

* [Inkpad](https://github.com/sprang/Inkpad)

> Vector illustration app for the iPad.

* [Brushes](https://github.com/sprang/Brushes)

> Painting app for the iPhone and iPad.


