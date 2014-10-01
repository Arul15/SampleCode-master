#Sample Code#

Study sample code for implementation examples of iOS features. Each sample code project is build-able and executable source example of how to accomplish a task for a specific technology. They show the correct sequence of calls and parameter data types to provide a generalized method for API use that developers can modify for their specific needs.

##PrintWebView##

PrintWebView demonstrates how to print the content displayed by a UIWebView object using the UIViewPrintFormatter class. This sample application is a primitive web browser with printing capability.

[URL](https://developer.apple.com/library/ios/samplecode/PrintWebView/Introduction/Intro.html#//apple_ref/doc/uid/DTS40010311) 

Updated: 2012-06-04

##CoreBluetooth Temperature Sensor##

A simple iOS iPhone application that demonstrates how to use the CoreBluetooth Framework to connect to a Bluetooth LE peripheral and read, write and be notified of changes to the characteristics of the peripheral.

The sample follows setting up the Central Manager, scanning for peripherals that show particular services, connecting to found peripherals, reading values from characteristics, registering for notifications from characteristics and writing to characteristics.

The service presented is a Temperature sensor that sends alert notifications when the temperature crosses a high or low threshold that can be set by the user.

[URL](https://developer.apple.com/library/ios/samplecode/TemperatureSensor/Introduction/Intro.html#//apple_ref/doc/uid/DTS40012194)

Updated: 2012-04-11

##ViewTransitions##

The ViewTransitions sample application demonstrates how to perform transitions between two views using UIView's transitionFromView API.

[URL](https://developer.apple.com/library/ios/samplecode/ViewTransitions/Introduction/Intro.html#//apple_ref/doc/uid/DTS40007411)

Updated: 2012-03-27

##UICatalog##
This sample is a catalog exhibiting many views and controls in the UIKit framework, along with their various properties and styles.

If you need code to create specific UI controls or views, refer to this sample and it should give you a good head start in building your user interface. In most cases you can simply copy and paste the code snippets you need.

When images or custom views are used, accessibility code has been added. Using the iPhone Accessibility API enhances the user experience of VoiceOver users.

[URL](https://developer.apple.com/library/ios/#samplecode/UICatalog/Introduction/Intro.html#//apple_ref/doc/uid/DTS40007710)

Updated: 2011-10-12

##SimpleDrillDown##

This application shows how to create a basic drill down interface.

The first scene shows a list of plays. When the user selects a play, the application displays a second scene that shows a list of the main characters and other data about the play. Both screens use a table view. The first list is in the "plain" style to show a standard list; the second is in the grouped style that you can use to lay out detail information.

The transition from the first scene to the second is defined by a segue associated with the prototype table view cell in the table view controller's table view. In the storyboard, the segue is named, "ShowSelectedPlay". The name is used as the idetifier in RootViewController's prepareForSegue:sender: method.

[URL](https://developer.apple.com/library/ios/#samplecode/SimpleDrillDown/Introduction/Intro.html#//apple_ref/doc/uid/DTS40007416)

Updated: 2012-02-28

##Tabster##

An eclectic-style application designed to show how to build a tab-bar based iPhone application.

An iPhone sample app that takes the "Tab Bar Application" Xcode template a few steps further by going over useful topics in implementing a UITabBarController in your application.

[URL](https://developer.apple.com/library/ios/#samplecode/Tabster/Introduction/Intro.html#//apple_ref/doc/uid/DTS40011213)

Updated: 2012-03-09

##SimpleTextInput##

SimpleTextInput is a simple text-editing application that demonstrates customized text display and text input handling using Core Text and UIKit Text Input protocols.

[URL](https://developer.apple.com/library/ios/#samplecode/SimpleTextInput/Introduction/Intro.html#//apple_ref/doc/uid/DTS40010633)

Updated: 2011-01-19

##DocInteraction##

Demonstrates how to use UIDocumentInteractionController to obtain information about documents and how to preview them. There are two ways to preview documents: one is to use UIDocumentInteractionController's preview API, the other is directly use QLPreviewController. This sample also demonstrates the use of UIFileSharingEnabled feature so you can upload documents to the application using iTunes and then to preview them. With the help of "kqueue" kernel event notifications, the sample monitors the contents of the Documents folder.

[URL](https://developer.apple.com/library/ios/#samplecode/DocInteraction/Introduction/Intro.html#//apple_ref/doc/uid/DTS40010052)

Updated: 2012-02-13

##International Mountains##

Drawing from the existing Cocoa Internationalization Mountains sample, this sample shows how to integrate, design and programmatically access localized resources and data in an iPhone application. This sample uses multiple localized views, localized formatted strings, localized application data, localized info.plist strings, and a localized application preferences settings bundle. The sample is localized in three languages: English, French, and Traditional Chinese.

[URL](https://developer.apple.com/library/ios/#samplecode/InternationalMountains/Introduction/Intro.html#//apple_ref/doc/uid/DTS40008756)

Updated: 2010-06-17

##CoreDataBooks##

This sample illustrates a number of aspects of working with the Core Data framework with an iPhone application:

* Use of an instance of NSFetchedResultsController object to manage a collection of objects to be displayed in a table view. 
* Undo and redo.
* Database initialization. 
* Use of a second (child) managed object context to isolate changes during an add operation.

[URL](http://developer.apple.com/library/prerelease/ios/#samplecode/CoreDataBooks/Introduction/Intro.html#//apple_ref/doc/uid/DTS40008405)

Updated: 2012-04-04

##Core Data Utility##

This sample contains the complete source code to the Core Data Utility Tutorial.

The sample illustrates how you can create a command-line utility that uses Core Data. It shows how to perform basic tasks required in a Core Data application: 

* Creation of a Core Data stack -- a persistent store, a persistent store coordinator (including the managed object model), and a managed object context. 
* Creation and initialization of a managed object. 
* Committing changes to the store by saving a context. 
* Creating a fetch request and retrieving managed objects.

[URL](http://developer.apple.com/library/prerelease/ios/#samplecode/CoreDataUtility/Introduction/Intro.html#//apple_ref/doc/uid/DTS40012164)

Updated: 2012-04-04

#PhotosByLocation#

Demonstrates how to use the AssetsLibrary APIs to provide a custom image picking UI. The user experience is centered around the idea of using the assets location and time metadata as a basis for certain features.

[URL](https://developer.apple.com/library/ios/#samplecode/PhotosByLocation/Introduction/Intro.html#//apple_ref/doc/uid/DTS40010136)

Updated: 2012-07-10

#QuickContacts#

QuickContacts demonstrates how to use the Address Book UI controllers and various properties such as displayedProperties, allowsAddingToAddressBook, and displayPerson. It shows how to browse a list of Address Book contacts, display and edit a contact record, create a new contact record, and update a partial contact record.

[URL](https://developer.apple.com/library/ios/#samplecode/QuickContacts/Introduction/Intro.html#//apple_ref/doc/uid/DTS40009475)

Updated: 2010-06-25

#ABUIGroups#

ABUIGroups demonstrates how to retrieve, add, and remove group records from the address book database using AddressBook APIs. It displays groups organized by their source in the address book.

[URL](https://developer.apple.com/library/ios/#samplecode/ABUIGroups/Introduction/Intro.html#//apple_ref/doc/uid/DTS40011307)

Updated: 2011-10-11

#CurrentAddress#

Demonstrates basic use of MapKit, displaying a map view and setting its region to current location.

It makes use of the MKReverseGeocoder class that provides services for converting your map coordinate (specified as a latitude/longitude pair) into information about that coordinate, such as the country, city, or street. A reverse geocoder object is a single-shot object that works with a network-based map service to look up placemark information for its specified coordinate value. To use placemark information is leverages the MKPlacemark class to store this information.

[URL](https://developer.apple.com/library/ios/#samplecode/CurrentAddress/Introduction/Intro.html#//apple_ref/doc/uid/DTS40009469)

Updated: 2010-12-01

#pARk#

pARk is an application project that demonstrates a how to use Core Motion's true north-referenced attitude API. It contains a UIView subclass, ARView, that displays a live camera feed with places-of-interest overlaid at the appropriate coordinates. The places-of-interest used are some famous parks around the world.

Important Note: If you run the compiled application on a device that does not have a gyroscope, you cannot use device motion data. You cannot effectively run the application on the simulator. You have to test and debug applications on a device.

The project has the following classes and protocol, which (except where noted) have corresponding .h and .m file:

ARView —A UIView subclass that provides an augmented reality view of the specified places-of-interest. It uses AVFoundation to provide a live camera feed. It also uses Core Location to determine the user's location and Core Motion to determine where the user is facing (i.e. the user's attitude). When provided with an NSArray containing objects of type PlaceOfInterest, it computes the location of each place-of-interest relative to the user, and on every frame, it projects this onto the user's screen using the attitude provided by Core Motion. It then renders the UIView contained in each PlaceOfInterest at the projected location.

PlaceOfInterest —A class containing the data necessary to locate and render each place-of-interest (i.e. a UIView and a location).

pARkViewController —A view controller that feeds hard-coded places-of-interest to its ARView in viewDidLoad, starts the ARView in viewWillAppear, and stops the ARView in viewWillDisappear.

pARkAppDelegate —A standard implementation of the UIApplicationDelegate protocol.

See "Motion Events" in Event Handling Guide for iPhone OS explains how to use the Core Motion API. The document also includes links to related Core Motion reference documentation.

[URL](https://developer.apple.com/library/ios/#samplecode/pARk/Introduction/Intro.html#//apple_ref/doc/uid/DTS40011083)

Updated: 2012-06-26

#ZoomingPDFViewer#

This project demonstrates how to use UIScrollView and CATileLayer to create a PDF viewer that supports supports zooming in or out at any level.

[URL](https://developer.apple.com/library/ios/#samplecode/ZoomingPDFViewer/Introduction/Intro.html#//apple_ref/doc/uid/DTS40010281)

Updated: 2012-05-14

#SimpleNetworkStreams#

Shows how to do simple networking using the NSStream API. The goal of this sample is very limited: it does not demonstrate everything you need to implement a fully fledged networking product, rather, it focuses on using the NSStream API to move a realistic amount of data across the network.

[URL](https://developer.apple.com/library/ios/#samplecode/SimpleNetworkStreams/Introduction/Intro.html#//apple_ref/doc/uid/DTS40008979)

Updated: 2012-05-09

#SimpleURLConnections#

SimpleURLConnections shows how to do simple networking using the NSURLConnection API. The goal of this sample is very limited: it does not demonstrate everything you need to implement a fully fledged networking product, rather, its goal is to demonstrate simple HTTP GET, PUT and POST using the NSURLConnection API.

[URL](https://developer.apple.com/library/ios/#samplecode/SimpleURLConnections/Introduction/Intro.html#//apple_ref/doc/uid/DTS40009245)

Updated: 2012-04-11

#UnitTests#

Shows how to build a static library for an iOS app and a Mac app, how to implement and run logic unit tests on the librarary source code on each platform, and how to implement and run application unit tests for the apps.

[URL](https://developer.apple.com/library/ios/#samplecode/UnitTests/Introduction/Intro.html#//apple_ref/doc/uid/DTS40011742)

Updated: 2012-04-09

#URLCache#

URLCache is a sample iPhone application that demonstrates how to download a resource off the web, store it in the application's data directory, and use the local copy of the resource. URLCache also demonstrates how to implement a couple of caching policies:

- The local copy of a web resource should remain valid for a period of time (for example, one day) during which the web is not re-checked.

- The HTTP header's Last-Modified date should be used to determine the last time a web resource changed before re-downloading it.

The audience for this sample is iPhone developers using resources such as images that are retrieved or updated from the web.

[URL](https://developer.apple.com/library/ios/#samplecode/URLCache/Introduction/Intro.html#//apple_ref/doc/uid/DTS40008061)

Updated: 2010-06-25

#HelloWorld#

HelloWorld demonstrates how to use a keyboard to enter text into a text field and how to display the text in a label.

[URL](https://developer.apple.com/library/ios/#samplecode/HelloWorld_iPhone/Introduction/Intro.html#//apple_ref/doc/uid/DTS40007709)

Updated: 2010-06-24

#HeadsUpUI#

Demonstrates how to implement a headsUp or HUD-like user interface over the app's primary view controller. This essentially mimics the behavior of the MPMoviePlayerController's hovering controls for controlling movie playback. Developers can refer to this sample for best practices in how to implement this translucent kind of interface complete with animation and timer support.

[URL](https://developer.apple.com/library/ios/#samplecode/HeadsUpUI/Introduction/Intro.html#//apple_ref/doc/uid/DTS40007998)

Updated: 2010-06-24

#CopyPasteTile#

CopyPasteTile demonstrates how to implement the copy-cut-paste feature introduced in iPhone OS 3.0. The sample:

* Shows how to use the UIMenuController class to position and display the editing menu (the menu with the Copy, Cut, Paste, and other commands).

* Illustrates how you might implement the canPerformAction:withSender: method of UIResponder to validate the menu commands for the current context.

* Shows how to respond when the user taps a menu command by reading and writing data to a pasteboard, (an instance of the UIPasteboard class).

[URL](https://developer.apple.com/library/ios/#samplecode/CopyPasteTile/Introduction/Intro.html#//apple_ref/doc/uid/DTS40009040)

Updated: 2010-06-28

#CoreTelephonyDemo#

This sample shows how to use Core Telephony framework to access the user's current calls, call center and carrier information.

The application uses a grouped table view with 3 sections, each section displaying one Core Telephony object.

The techniques shown in this sample are: * correct way of instantiating Core Telephony framework objects * using a block-based event handler to receive call events * access Core Telephony object properties

[URL](https://developer.apple.com/library/ios/#samplecode/CoreTelephonyDemo/Introduction/Intro.html#//apple_ref/doc/uid/DTS40010746)

Updated: 2011-03-08

#ExternalDisplay#

How to detect the presence of an external display, determine the available display resolutions, select a resolution, and show content on the display.

[URL](https://developer.apple.com/library/ios/#samplecode/ExternalDisplay/Introduction/Intro.html#//apple_ref/doc/uid/DTS40010724)

Updated: 2011-03-01

#PhotoPicker#

This sample demonstrates how to choose images from the photo library, take a picture with the device's camera, and how to customize the look of the camera's user interface. This is done by using UIImagePickerController. The chosen image or camera photo is displayed in a UIImageView.  To customize the camera's interface, this sample shows how to use an overlay view. With this overlay view it gives you the ability to customize the UI as you take a picture.

[URL](https://developer.apple.com/library/ios/#samplecode/PhotoPicker/Introduction/Intro.html#//apple_ref/doc/uid/DTS40010196)

Updated: 2012-08-17

#GeocoderDemo#

This sample application demonstrates using a CLGeocoder instance to perform forward and reverse geocoding on strings and dictionaries. The application also includes an example distance calculator that will display the distance between two placemarks.

[URL](https://developer.apple.com/library/ios/#samplecode/GeocoderDemo/Introduction/Intro.html#//apple_ref/doc/uid/DTS40011097)

Last Revision: Version 1.2, 2012-08-06

#Core Audio Utility Classes#

The "CoreAudio" folder contains the Public Utility sources (PublicUtility folder) as well as base classes required for codec and audio unit development and so on. These utility classes are used by Core Audio sample code and extend or wrap Core Audio API's.

The "CoreAudio" utility classes require OS X 10.7 or later and Xcode 4.3 or later and should be placed in the '/Library/Developer/' for general use with Apple Core Audio Sample Code.

[URL](https://developer.apple.com/library/ios/#samplecode/CoreAudioUtilityClasses/Introduction/Intro.html)

Last Revision:	Version 1.01, 2012-06-26

#PVRTextureLoader#

This application illustrates how to load PVR texture files using the included PVRTexture class and then display them using OpenGL.

The sample image, encoded as an xcode project build phase, is rendered on a rotatable and scalable quad. Controls are provided for experimenting with various texture compression and filter settings.

[URL](https://developer.apple.com/library/ios/#samplecode/PVRTextureLoader/Introduction/Intro.html#//apple_ref/doc/uid/DTS40008121)

Last Revision:	Version 1.5, 2010-06-25

#SimpleFTPSample#

SimpleFTPSample shows how to do simple FTP operations using the NSURLConnection and CFFTPStream APIs. It can download a file using both NSURLConnection and CFFTPStream. Also, it can upload a file, list a directory, and create a directory using CFFTPStream.

[URL](https://developer.apple.com/library/ios/#samplecode/SimpleFTPSample/Introduction/Intro.html#//apple_ref/doc/uid/DTS40009243)

Last Revision:	Version 1.3, 2012-08-19

#LazyTableImages#

This sample demonstrates a multi-stage approach to loading and displaying a UITableView. It begins by loading the relevant text from an RSS feed so the table can load as quickly as possible, and then downloads the images for each row asynchronously so the UI is more responsive.

[URL](https://developer.apple.com/library/ios/#samplecode/LazyTableImages/Introduction/Intro.html#//apple_ref/doc/uid/DTS40009394)

Last Revision:	Version 1.3, 2012-08-22

#CoreTextPageViewer#

This sample shows how to use Core Text to display large bodies of text, text with mixed styles, and text with special style or layout requirements, such as use of custom fonts. A version of this sample was used in the "Advanced Text Handling for iPhone OS" WWDC 2010 Session.

[URL](https://developer.apple.com/library/ios/#samplecode/CoreTextPageViewer/Introduction/Intro.html#//apple_ref/doc/uid/DTS40010699)

Last Revision:	Version 1.0, 2011-02-08

#Reflection#

This sample shows how to implement a "reflection" special effect on a given UIImageView most commonly seen in iTunes and iPod player apps.

It allows the rendering effect with "dynamic" input values for 1) reflection height and 2) translucency level. These values can be plugged into the factory methods provided by this sample to achieve a desired affect.

[URL](https://developer.apple.com/library/ios/#samplecode/Reflection/Introduction/Intro.html#//apple_ref/doc/uid/DTS40008063)

Last Revision:	Version 1.6, 2012-09-26

#MultipleDetailViews#

This sample shows how you can use UISplitViewController to manage the presentation of multiple detail views in conjunction with a navigation hierarchy.

The application uses a split view controller with a custom object as its delegate. When you make a selection in the table view, a new view controller is set as the split view controller's second view controller.

The custom split view delegate defines a protocol (SubstitutableDetailViewController) that detail view controllers must adopt. The protocol specifies a property to hide and show the bar button item controlling the popover.

[URL](https://developer.apple.com/library/ios/#samplecode/MultipleDetailViews/Introduction/Intro.html#//apple_ref/doc/uid/DTS40009775)

Last Revision:	Version 1.2, 2012-09-18

#CollectionView-Simple#

Demonstrates how to use UICollectionView, a way to present ordered data to users in a grid-like fashion. With a collection view object, you are able to define the presentation and arrangement of embedded views. The collection view class works closely with an accompanying layout object to define the placement of individual data items. In this example UIKit provides a standard flow-based layout object that you can use to implement multi-column grids containing items of a standard size.

[URL](https://developer.apple.com/library/ios/#samplecode/CollectionView-Simple/Introduction/Intro.html#//apple_ref/doc/uid/DTS40012860)

Last Revision:	Version 1.0, 2012-09-24

#SpeakHere#

SpeakHere demonstrates basic use of Audio Queue Services, Audio File Services, and Audio Session Services on the iPhone for recording and playing back audio.

The code in SpeakHere uses Audio File Services to create, record into, and read from a CAF (Core Audio Format) audio file containing uncompressed (PCM) audio data. The application uses Audio Queue Services to manage recording and playback. The application also uses Audio Session Services to manage interruptions (as described in Core Audio Overview).

[URL](https://developer.apple.com/library/ios/#samplecode/SpeakHere/Introduction/Intro.html#//apple_ref/doc/uid/DTS40007802)

Last Revision:	Version 2.5, 2012-09-10

#PhotoScroller#

"PhotoScroller" demonstrates the use of embedded UIScrollViews and CATiledLayer to create a rich user experience for displaying and paginating photos that can be individually panned and zoomed. CATiledLayer is used to increase the performance of paging, panning, and zooming with high-resolution images or large sets of photos.

[URL](https://developer.apple.com/library/ios/#samplecode/PhotoScroller/Introduction/Intro.html#//apple_ref/doc/uid/DTS40010080)

Last Revision:	Version 1.2, 2012-08-01

#AVSimpleEditoriOS#

AVSimpleEditor is a simple AVFoundation based movie editing application which exercises the APIs of AVVideoComposition, AVAudioMix and demonstrates how they can be used for simple video editing tasks. It also demonstrates how they interact with playback (AVPlayerItem) and export (AVAssetExportSession). The application performs trim, rotate, crop, add music, add watermark and export. This sample is ARC-enabled.

[URL](https://developer.apple.com/library/ios/#samplecode/AVSimpleEditoriOS/Introduction/Intro.html#//apple_ref/doc/uid/DTS40012797)

Last Revision:	Version 1.0, 2012-09-10

#AVCaptureAudioDataOutput To AudioUnit iOS#

AVCaptureToAudioUnit for iOS demonstrates how to use the CMSampleBufferRefs vended by AVFoundation's capture AVCaptureAudioDataOutput object with various CoreAudio APIs. The application uses a AVCaptureSession with a AVCaptureAudioDataOutput to capture audio from the default input, applies an effect to that audio using a simple delay effect AudioUnit and writes the modified audio to a file using the CoreAudio ExtAudioFile API. It also demonstrates using and AUGraph containing an AUConverter to convert the AVCaptureAudioDataOutput provided data format into a suitable format for the delay effect.

The CaptureSessionController class is responsible for setting up and running the AVCaptureSession and for passing the captured audio buffers to the CoreAudio AudioUnit and ExtAudioFile. The setupCaptureSession method is responsible for setting up the AVCaptureSession, while the captureOutput:didOutputSampleBuffer:fromConnection: passes the captured audio data through the AudioUnit via AudioUnitRender into the file using ExtAudioFileWriteAsync when recording.

CoreMedia provides two convenience methods to easily use the captured audio data with CoreAudio APIs. The CMSampleBufferGetAudioBufferListWithRetainedBlockBuffer API fills in an AudioBufferList with the data from the CMSampleBuffer, and returns a CMBlockBuffer which references (and manages the lifetime of) the data in that AudioBufferList. This AudioBufferList can be used directly by AudioUnits and other CoreAudio objects. The CMSampleBufferGetNumSamples API returns the number of frames of audio contained within the sample buffer, a value that can also be passed directly to CoreAudio APIs.

Because CoreAudio AudioUnits process audio data using a "pull" model, but the AVCaptureAudioDataOutput object "pushes" audio sample buffers onto a client in real time, the captured buffers must be sent though the AudioUnit via an AudioUnit render callback which requests input audio data each time AudioUnitRender is called to retrieve output audio data. Every time captureOutput:didOutputSampleBuffer:fromConnection: receives a new sample buffer, it gets and stores the buffer as the Input AudioBufferList (so that the render callback can access it), and then immediately calls AudioUnitRender which synchronously pulls the stored input buffer list through the AudioUnit via the render callback. The output data is available in the output AudioBufferList passed to AudioUnitRender. This output buffer list may be passed to ExtAudioFile for final format conversion and writing to the file.

[URL](https://developer.apple.com/library/ios/#samplecode/AVCaptureToAudioUnit/Introduction/Intro.html#//apple_ref/doc/uid/DTS40012880)

Last Revision:	Version 1.0, 2012-10-08

#Touches#

The Touches sample application demonstrates how to handle touches, including multiple touches that move multiple objects. After the application launches, three colored pieces appear onscreen that the user can move independently.

"Touches_Classic" demonstrates how to handle touches using UIResponder's: touches began, touches moved, and touches ended.

"Touches_GestureRecognizers" demonstrates how to use UIGestureRecognizers to handle touch events.

[URL](https://developer.apple.com/library/ios/#samplecode/Touches/Introduction/Intro.html#//apple_ref/doc/uid/DTS40007435)

Last Revision:	Version 1.14, 2012-07-17

#iAdInterstitialSuite#

iAdInterstitialSuite contains two applications that demonstrate the usage of the ADInterstitialAd introduced in iOS 4.3.

ADGame – a simple game that displays an interstitial ad between games.

ADMagazine - a simple picture magazine that displays an interstitial ad as you page through.

[URL](https://developer.apple.com/library/ios/#samplecode/iAdInterstitialSuite/Introduction/Intro.html#//apple_ref/doc/uid/DTS40010627)

Last Revision:	Version 1.2, 2012-01-19

#iAdSuite#

iAdSuite is a set of samples demonstrating how to manage an ADBannerView in many common scenarios, each scenario demonstrated in a particular sample application.

In many of the samples the content is represented by a simple TextViewController view controller that displays some text in a read-only UITextView and runs a timer. The UITextView represents your application's content and the timer represents ongoing activity in your application that you will want to pause when the advertisement takes over the user interface. The MediumRectBanner sample uses a UICollectionView with image content instead, adding the banners as additional cells.

The traditional banner (represented with the ADAdTypeBanner constant) is expected to be placed at or near the bottom of the screen and placed to consume the full width of the screen. New in iOS 6 is the Medium Rect sized banner (represented with the ADAdTypeMediumRectangle constant) which is intended to be placed inline with other content from your application. It is highly recommended that you create only a single instance of each type of banner that you use (so if you use both a banner and medium rect type, you would have at most 1 instance of each) and that you share these instances among the places in your UI that they are used.

[URL](https://developer.apple.com/library/ios/#samplecode/iAdSuite/Introduction/Intro.html#//apple_ref/doc/uid/DTS40010198)

Last Revision:	Version 2.1, 2012-10-22

#SimpleStocks#

The SimpleStocks sample application demonstrates how to use UIKit classes and the Core Graphics framework to draw content for iOS. From this example you will learn about UIKit's UIBezierPath class. In the sample path objects are used to both draw content and clip content. In addition you will see examples of using patterns to fill paths as well as using a path to clip images.

This example shows how to use various drawing API's in UIKit. - UIBezierPath for building simple and complex paths - UIBezierPath for clipping - Gradients - How the drawing system works in UIKit - Performance Optimizations for drawing

[URL](https://developer.apple.com/library/ios/#samplecode/SimpleStocks/Introduction/Intro.html#//apple_ref/doc/uid/DTS40011103)

Last Revision:	Version 1.1, 2011-07-27

#PrintPhoto#

PrintPhoto demonstrates how to print photos. The application allows a user to view and print any photo from the user's photo library. It initially presents a photo that is built into the application's bundle but by touching the photo picker icon you can choose any photo in the library.

PrintPhoto demonstrates two different strategies for printing photos. The simplest way to print a photo is to set the printingItem property of the shared UIPrintInteractionController instance to the NSURL, NSData, UIImage, or ALAsset object referencing or containing the photo. If you have multiple photos to print, you can create an array containing the types of objects cited above and assign that array to the printingItems property.

PrintPhoto also demonstrates how to print by using a custom UIPrintPageRenderer object to render the content for printing. This object must be assigned to the printPageRenderer property of the shared UIPrintInteractionController instance. For this example, the subclass of UIPrintPageRenderer overrides the numberOfPages method as well as a "draw" method that draws the image upon request.

PrintPhoto also shows how to:

* Pick a photo from the user's photo library for display and print. * Utilize the ALAssetsLibrary to obtain a screen size image for display. * Obtain and configure the shared UIPrintInteractionController instance. * Use the printingItem property of the UIPrintInteractionController object for direct data submission. * Alternatively, use a UIPrintPageRenderer object to draw printable content instead of submitting it directly.

[URL](https://developer.apple.com/library/ios/#samplecode/PrintPhoto/Introduction/Intro.html#//apple_ref/doc/uid/DTS40010366)

Last Revision:	Version 1.1, 2011-10-12

#PocketCoreImage#

This sample demonstrates applying Core Image filters to a still image. The filter configuration is done automatically (using random numbers) and multiple filters may be applied at the same time. While this sample uses a preset list of filters that the user may select from, code is provided in the next section which demonstrates asking the system for a list of filters.

[URL](https://developer.apple.com/library/ios/#samplecode/PocketCoreImage/Introduction/Intro.html#//apple_ref/doc/uid/DTS40011220)

Last Revision:	Version 1.0, 2011-10-12

#PhotoLocations#

This sample illustrates a Core Data application that uses more than one entity and uses transformable attributes. It also shows inferred migration of the persistent store.

The application extends the completed project from the Core Data Tutorial for iPhone OS. The first screen displays a table view of events, which encapsulate a time stamp, a geographical location expressed in latitude and longitude, and the thumbnail of a picture for the event. The user can add and remove events using the first screen.

Event has an optional to-one relationship to Photo (which has an inverse to-one relationship back to Event) that contains the data for a full-sized image. By selecting a row on the first screen, the user displays a detail view that shows the photo (or allows the user to choose a photo for the event).

The photo data is not stored with the event object itself because it's not always needed. When the list of events is first displayed, only the thumbnails are shown. The events' photos are initially represented by faults. The full picture is required only if the user inspects the detail of an event. At the point at which the application asks for a given event's photo object, the fault fires and the photo object is retrieved automatically. This "lazy loading" of data means your application's memory consumption is kept as low as possible.

Although the application's data model is different from the original application's, the original data store is opened by specifying that inferred migration should be used in the application delegate's persistentStoreCoordinator method. (You must ensure that the applications' bundle identifiers are the same.)

[URL](https://developer.apple.com/library/ios/#samplecode/PhotoLocations/Introduction/Intro.html#//apple_ref/doc/uid/DTS40008909)

Last Revision:	Version 1.1, 2010-07-23

#MusicCube#

MusicCube demonstrates basic use of OpenGL ES, OpenAL, and Audio File Services on the iPhone for manipulating sound in a 3D environment. The four modes in the application illustrate how the sound volume and balance will change based on the position of the omnidirectional sound source and the position and rotation of the listener.

[URL](https://developer.apple.com/library/ios/#samplecode/MusicCube/Introduction/Intro.html#//apple_ref/doc/uid/DTS40008978)

Last Revision:	Version 1.2, 2010-06-23

#Locations#

This sample represents the completed project from the Your First iPhone Application With Core Data tutorial. The application displays a list of events, which encapsulate a time stamp and a geographical location expressed in latitude and longitude, and allows the user to add and remove events.

[URL](https://developer.apple.com/library/ios/#samplecode/Locations/Introduction/Intro.html#//apple_ref/doc/uid/DTS40008406)

Last Revision:	Version 1.3, 2010-06-29

#Large Image Downsizing#

This code sample demonstrates a way to support displaying very large images in limited memory environments by turning a large image on disk into a smaller image in memory. This is useful in situations where the original image is too large to fit into memory as required for it to be displayed.

Having useful implications in supporting user defined documents, it should be noted that the photo roll or document sharing drop are the locations that a large image would exist. For simplicity this sample reads a large image from the bundle.

Supported formats are: PNG, TIFF, JPEG. Unsupported formats: GIF, BMP, interlaced images.

[URL](https://developer.apple.com/library/ios/#samplecode/LargeImageDownsizing/Introduction/Intro.html#//apple_ref/doc/uid/DTS40011173)

Last Revision:	Version 1.0, 2011-08-05

#iPhoneCoreDataRecipes#

This sample shows how you can use view controllers, table views, and Core Data in an iPhone application.

The application uses the domain of organizing and presenting recipes to show how you can use the view controller as the organizing unit to manage screenfuls of information, and how you can leverage table views to display and edit data in an elegant fashion.

Amongst the techniques shown are how to:

* Combine tab bar and navigation controllers to create a complex navigation flow. * Customize a navigation bar. * Implement custom table view cells that reformat themselves in response to editing, removing unnecessary information to ensure that the display remains uncluttered. * Customize a table header view. * Present modal views. * Use multiple entities in a Core Data application. * Provide a default Core Data persistent store.

[URL](https://developer.apple.com/library/ios/#samplecode/iPhoneCoreDataRecipes/Introduction/Intro.html#//apple_ref/doc/uid/DTS40008913)

Last Revision:	Version 1.4, 2010-06-25

#KMLViewer#

Demonstrates how to display KML files on top of a MKMapView. It shows how to use MapKit's Annotations and Overlays to display KML files on top of an MKMapView.

KML is an open standard, so you can learn more about it at the Open Geospatial Consortium website: http://www.opengeospatial.org/standards/kml

The Google documentation for KML is at this website: http://code.google.com/apis/kml/

[URL](https://developer.apple.com/library/ios/#samplecode/KMLViewer/Introduction/Intro.html#//apple_ref/doc/uid/DTS40010046)

Last Revision:	Version 1.3, 2012-02-22

#GLCameraRipple#

This sample demonstrates how to use the AVFoundation framework to capture YUV frames from the camera and process them using shaders in OpenGL ES 2.0. CVOpenGLESTextureCache, which is new to iOS 5.0, is used to provide optimal performance when using the AVCaptureOutput as an OpenGL texture. In addition, a ripple effect is applied by modifying the texture coordinates of a densely tessellated quad.

[URL](https://developer.apple.com/library/ios/#samplecode/GLCameraRipple/Introduction/Intro.html#//apple_ref/doc/uid/DTS40011222)

Last Revision:	Version 1.1, 2012-02-22

#StreetScroller#

Demonstrates how a UIScrollView subclass can scroll infinitely in the horizontal direction.

[URL](https://developer.apple.com/library/ios/#samplecode/StreetScroller/Introduction/Intro.html#//apple_ref/doc/uid/DTS40011102)

Last Revision:	Version 1.1, 2011-08-10

#WhichWayIsUp#

The WhichWayIsUp sample application demonstrates how to use a UIViewController to track the orientation of the device. The application draws a small wooden crate that maintains the correct orientation as the user rotates the device.

[URL](https://developer.apple.com/library/ios/#samplecode/WhichWayIsUp/Introduction/Intro.html#//apple_ref/doc/uid/DTS40007330)

Last Revision:	Version 1.8, 2010-06-24

#ScrollViewSuite#

A series of examples that illustrate how to use UIScrollView.

1_TapToZoom demonstrates:

* Fitting the image to the screen on launch

* Detecting single, double, and two-finger taps using UIGestureRecognizers

* Zooming in response to taps

2_Autoscroll adds a thumbnail scroll view, and demonstrates:

* Use of the canCancelContentTouches property to track moving touches in a subview of a scroll view

* How to implement autoscrolling in response to a subview being dragged

3_Tiling demonstrates:

* How to subclass UIScrollView to add content tiling

* Reusing tiles to optimize performance and memory use

* Changing the resolution of the content in response to zooming

[URL](https://developer.apple.com/library/ios/#samplecode/ScrollViewSuite/Introduction/Intro.html#//apple_ref/doc/uid/DTS40008904)

Last Revision:	Version 1.3, 2010-10-20

#NavBar#

Demonstrates how to use UINavigationController and UIViewController classes together as building blocks to your application's user interface. Use it as a launching pad in starting the development of your new application. The various pages in this sample exhibit different ways in how to modify the navigation bar by modifying the navigation controller's UINavigationItem. This class represents the navigation bar at the top of the screen. Among the levels of customization are varying appearance styles known as UIBarStyle, and applying custom left and right buttons known as UIButtonTypeNavigation.

[URL](https://developer.apple.com/library/ios/#samplecode/NavBar/Introduction/Intro.html#//apple_ref/doc/uid/DTS40007418)

Last Revision:	Version 1.11, 2012-02-07

#GLEssentials#

This sample provides examples of some essential techniques for using the OpenGL and OpenGL ES API. It includes usages of Vertex Buffer Objects (VBOs), Vertex Array Objects (VAOs), Framebuffer Objects (FBO), and GLSL Program Objects. It creates a VAO and VBOs from model data loaded in. It then creates a texture for the model from image data and GLSL shaders from source also loaded in. Finally, it creates an FBO and texture to render a reflection of the model. It uses an environment mapping GLSL program to apply the reflection texture to a plane.

This sample also demonstrates sharing of OSX OpenGL with iOS OpenGL ES source code. Additionally, it demonstrates how to obtain and use an OpenGL 3.2 rendering context on OSX 10.7 or later.

Many of these techniques were described in the "OpenGL Essential Design Practices" session from WWDC 2010.

[URL](https://developer.apple.com/library/ios/#samplecode/GLEssentials/Introduction/Intro.html#//apple_ref/doc/uid/DTS40010104)

Last Revision:	Version 1.5, 2012-01-25

#KeyboardAccessory#

Shows how to use a keyboard accessory view. The application uses a single view controller. The view controller's view is covered by a text view. When you tap the text view, the view controller loads a nib file containing an accessory view that it assigns to the text view's inputAccessoryView property. The accessory view contains a button. When you tap the button, the text "You tapped me." is added to the text view. The sample also shows how you can use the keyboard-will-show and keyboard-will-hide notifications to animate resizing a view that is obscured by the keyboard.

[URL](https://developer.apple.com/library/ios/#samplecode/KeyboardAccessory/Introduction/Intro.html#//apple_ref/doc/uid/DTS40009462)
 Last Revision:	Version 1.3, 2010-04-19

#CryptoExercise#

This sample demonstrates the use of the two main Cryptographic API sets on the iPhone OS SDK. Asymmetric Key Encryption and random nonce generation is handled through the Security framework API set, whereas, Symmetric Key Encryption and Digest generation is handled by the CommonCrypto API set. The CryptoExercise sample brings both of these APIs together through a network service, discoverable via Bonjour, that performs a "dummy" cryptographic protocol between devices found on the same subnet.

[URL](https://developer.apple.com/library/ios/#samplecode/CryptoExercise/Introduction/Intro.html#//apple_ref/doc/uid/DTS40008019)

Last Revision:	Version 1.2, 2009-05-13

#AlternateViews#

Demonstrates how to implement alternate or distinguishing view controllers for each particular device orientation. Through the help of the following UIViewController properties, this can be easily achieved -

	@property(nonatomic,assign) UIModalTransitionStyle modalTransitionStyle;	// for a transition fade

	@property(nonatomic,assign) BOOL wantsFullScreenLayout; // for any view controller to appear over another

This sample implements a two different view controllers one for portrait and one for landscape. The portrait view controller listens for device orientations in order to properly swap in and out the landscape view controller. It uses the above two properties to achieve the visual cross-fade effect.

[URL](https://developer.apple.com/library/ios/#samplecode/AlternateViews/Introduction/Intro.html#//apple_ref/doc/uid/DTS40008755)

Last Revision:	Version 1.1, 2010-06-23

#DrillDownSave#

Demonstrates how to restore the user's current location in a drill-down list style user interface and restore that location when the app is relaunched. The drill-down or content hierarchy is generated from a plist file called 'outline.plist'. The sample stores the user's location in its preferences file using NSUserDefaults.

[URL](https://developer.apple.com/library/ios/#samplecode/DrillDownSave/Introduction/Intro.html#//apple_ref/doc/uid/DTS40007800)

Last Revision:	Version 1.3, 2010-06-24

#Tweeting#

By using the Twitter framework, Accounts framework, and the NSJSONSerialization class, this sample demonstrates using the built-in Twitter composition sheet, creating a custom POST request, and downloading the public timeline from Twitter.

The "Send Easy Tweet" button checks if a Twitter account is present on the device and creates a pre-populated TWTweetComposeViewController. This also handles the "cancel" and "send" actions from the TWTweetComposeViewController.

The "Send Custom Tweet" button utilizes the Accounts framework to create an instance of the account store on the device and then find all Twitter accounts present. In this example, the first Twitter ACAccount object found is used to pre-populate a tweet and uses a TWRequest to post the tweet using the Twitter API. This example also handles the returned response data and http response.

The "Get Public Timeline" button creates a TWRequest to get the current public timeline using the Twitter API. The response data is then converted from JSON data to an NSDictionary, using the NSJSONSerialization class.

[URL](https://developer.apple.com/library/ios/#samplecode/Tweeting/Introduction/Intro.html#//apple_ref/doc/uid/DTS40011191)

Last Revision:	Version 1.0, 2011-10-12

#iPhoneUnitTests#

iPhoneUnitTests illustrates the use of unit tests on an iPhone application project to ensure that application functionality does not degrade as its source code undergoes changes to improve the application or to fix bugs. The project showcases the two types of unit test: logic and application. Logic unit tests allow for stress-testing source code. Application unit tests help ensure the correct linkage between user-interface controls, controller objects, and model objects.

[URL](https://developer.apple.com/library/ios/#samplecode/iPhoneUnitTests/Introduction/Intro.html#//apple_ref/doc/uid/DTS40008868)

Last Revision:	Version 2.0, 2011-08-17

#AVLoupe#

This sample demonstrates how to use multiple synchronized AVPlayerLayer instances, associated with a single AVPlayer, to efficiently produce non-trivial presentation of timed visual media. Using just one AVPlayer this sample demonstrates how you can display the same video in multiple AVPlayerLayers simultaneously. With minimal code you can create very customized and creative forms of video display. As an example, this sample demonstrates an interactive loupe, or magnifying glass, for video playback. This is similar to features that you might have used in iPhoto and Aperture.

This sample was explored in the WWDC 2012 session 517: Real-Time Media Effects and Processing during Playback.

[URL](https://developer.apple.com/library/ios/#samplecode/AVLoupe/Introduction/Intro.html#//apple_ref/doc/uid/DTS40012894)

Last Revision:	Version 1.0, 2012-10-16

#TableMultiSelect#

Demonstrates the use of multiple selection of table cells in UITableView; in particular, using it to delete one or more items.

[URL](https://developer.apple.com/library/ios/#samplecode/TableMultiSelect/Introduction/Intro.html#//apple_ref/doc/uid/DTS40011189)

Last Revision:	Version 1.1, 2012-10-16

#ToolbarSearch#

This sample shows how to use a search field in a toolbar. When you start a search, a table view displaying recent searches matching the current search string is displayed in a popover.

The main view controller adds to a toolbar a bar button item with a search field as a custom view. If you tap the search field, the view controller presents a popover containing a list of recent searches. The list is stored in user defaults so that it persists between launches of the application, and is managed by the list's table view controller. The recents list is filtered by the current search term. If you select an item from the recents list, the item is copied to the search field and a search executed.

[URL](https://developer.apple.com/library/ios/#samplecode/ToolbarSearch/Introduction/Intro.html#//apple_ref/doc/uid/DTS40009461)

Last Revision:	Version 1.4, 2011-10-24

#SquareCam#

SquareCam demonstrates improvements to the AVCaptureStillImageOutput class in iOS 5, highlighting the following features:

- KVO observation of the @"capturingStillImage" property to know when to perform an animation - Use of setVideoScaleAndCropFactor: to achieve a "digital zoom" effect on captured images - Switching between front and back cameras while showing a real-time preview - Integrating with CoreImage's new CIFaceDetector to find faces in a real-time VideoDataOutput, as well as in a captured still image. Found faces are indicated with a red square. - Overlaid square is rotated appropriately for the 4 supported device rotations.

Note: This sample will not deliver any camera output on the iOS simulator.

[URL](https://developer.apple.com/library/ios/#samplecode/SquareCam/Introduction/Intro.html#//apple_ref/doc/uid/DTS40011190)

Last Revision:	Version 1.0, 2011-10-12

#SimpleGestureRecognizers#

This sample shows how to use standard gesture recognizers.

A view has four gesture recognizers to recognize a tap, a right swipe, a left swipe, and a rotation gesture. When they recognize a gesture, the recognizers send a suitable message to the view controller, which in turn displays an appropriate image at the location of the gesture.

The sample illustrates some additional features of gesture recognizers.

In general, there's no need to maintain a reference to a recognizer once you've added it to a view. You can simply implement the appropriate callback method for the recognizer and wait for messages. This is shown in the cases of the right swipe and rotation recognizers. In some situations, however, it may be appropriate to maintain a reference to the recognizer, so that you can for example determine which recognizer sent a delegate message. This is shown in the cases of the left swipe and tap recognizers.

For the purpose of illustration, the left swipe recognizer can be enabled and disabled by toggling a segmented control. The view controller maintains a reference to the recognizer so that it can be added to and removed from the view as appropriate.

The view controller acts as a delegate for the tap recognizer so that it can disallow recognition of a tap within the segmented control. Recognizers ignore the exclusive touch setting for views. This is so that they can consistently recognize gestures even if they cross other views. For example, suppose you had two buttons, each marked exclusive touch, and you added a pinch gesture recognizer to their superview. That a finger came down in one the of the buttons shouldn't prevent you from pinching in the general case. If you do want to selectively disallow recognition of a gesture, you can use the recognizer's delegate methods. In this example, the view controller uses gestureRecognizer:shouldReceiveTouch: to test whether the tap recognizer will try to recognize a touch in the segmented control. If it is, it is disallowed.

A view controller creates four gesture recognizers to recognize a tap, a right swipe, a left swipe, and a rotation gesture. When they recognize a gesture, the recognizers send a suitable message to the view controller, which in turn displays an appropriate image at the location of the gesture.

[URL](https://developer.apple.com/library/ios/#samplecode/SimpleGestureRecognizers/Introduction/Intro.html#//apple_ref/doc/uid/DTS40009460)

Last Revision:	Version 2.0, 2011-10-12

#StopNGo for iOS#

StopNGo is a simple stop-motion animation QuickTime movie recorder that uses AVFoundation.

It creates a AVCaptureSession, AVCaptureDevice, AVCaptureVideoPreviewLayer, and AVCaptureStillImageOutput to preview and capture still images from a video capture device, then re-times each sample buffer to a frame rate of 5 fps and writes frames to disk using AVAssetWriter.

A frame rate of 5 fps means that 5 still images will result in a 1 second long movie. This value is hard coded in the sample but may be changed as required.

[URL](https://developer.apple.com/library/ios/#samplecode/StopNGo/Introduction/Intro.html#//apple_ref/doc/uid/DTS40011123)

Last Revision:	Version 1.0.1, 2011-10-12

#Sampler Unit Presets (LoadPresetDemo)#

This sample code project shows how to create an an iOS audio processing graph containing a Sampler audio unit and how to configure the sampler by loading an AUPreset file that was created in Mac OS X. The project also shows how to start the graph and trigger note-on and note-off events to audition the presets.

[URL](https://developer.apple.com/library/ios/#samplecode/LoadPresetDemo/Introduction/Intro.html#//apple_ref/doc/uid/DTS40011214)

Last Revision:	Version 1.1, 2011-10-12

#Breadcrumb#

Demonstrates how to draw a path using the Map Kit overlay, MKOverlayView, that follows and tracks the user's current location. The included CrumbPath and CrumbPathView overlay and overlay view classes can be used for any path of points that are expected to change over time. It also demonstrates what is needed to track the user's location as a background process.

[URL](https://developer.apple.com/library/ios/#samplecode/Breadcrumb/Introduction/Intro.html#//apple_ref/doc/uid/DTS40010048)

Last Revision:	Version 1.5, 2011-10-12

#RosyWriter#

This sample demonstrates the use of the AV Foundation framework to capture, process, preview, and save video on iOS devices.

When RosyWriter launches, it creates an AVCaptureSession with audio and video device inputs, and outputs for audio and video data. These outputs continuously supply frames of audio and video to the app, via the captureOutput:didOutputSampleBuffer:fromConnection: delegate method.

The app applies a very simple processing step to each video frame. Specifically, it sets the green element of each pixel to zero, which gives the entire frame a purple tint. Audio frames are not processed.

After a frame of video is processed, RosyWriter uses OpenGL ES 2 to display it on the screen. This step uses the CVOpenGLESTextureCache API, new in iOS 5, for enhanced performance.

When the user chooses to record a movie, an AVAssetWriter is used to write the processed video and un-processed audio to a QuickTime movie file.

[URL](https://developer.apple.com/library/ios/#samplecode/RosyWriter/Introduction/Intro.html#//apple_ref/doc/uid/DTS40011110)

Last Revision:	Version 1.2, 2011-10-06

#MoviePlayer#

Demonstrates how to use the Media Player framework to play a movie from a file or network stream, and configure the movie background color, playback controls, background color and image, scaling and repeat modes. It also shows how to draw custom overlay controls on top of the movie during playback.

[URL](https://developer.apple.com/library/ios/#samplecode/MoviePlayer_iPhone/Introduction/Intro.html#//apple_ref/doc/uid/DTS40007798)

Last Revision:	Version 1.4, 2011-08-25

#Recipes and Printing#

The Recipes sample app lets you browse recipes. This sample adds the ability to print the recipes.

It demonstrates formatting data presented by the application UI in a completely custom way for the printed page.

By subclassing UIPrintPageRenderer, this sample illustrates intermixing custom drawn page content with content drawn by architecture-provided UIPrintFormatters.

In addition to custom page content, it also draws custom page headers, page footers, and page breaks.

[URL](https://developer.apple.com/library/ios/#samplecode/Recipes_+_Printing/Introduction/Intro.html#//apple_ref/doc/uid/DTS40011098)

Last Revision:	Version 1.1, 2011-08-24

#StitchedStreamPlayer#

A simple AVFoundation demonstration of how timed metadata can be used to identify different content in a stream, supporting a custom seek UI.

[URL](https://developer.apple.com/library/ios/#samplecode/StitchedStreamPlayer/Introduction/Intro.html#//apple_ref/doc/uid/DTS40010092)

Last Revision:	Version 1.4, 2011-06-27

#AVPlayerDemo#

Uses AVPlayer to play videos from the iPod Library, Camera Roll, or via iTunes File Sharing. Also displays metadata.

[URL](https://developer.apple.com/library/ios/#samplecode/AVPlayerDemo/Introduction/Intro.html#//apple_ref/doc/uid/DTS40010101)

Last Revision:	Version 1.1, 2011-06-10

#GKAuthentication#

An example of how to successfully authenticate using GameKit.

[URL](https://developer.apple.com/library/ios/#samplecode/GKAuthentication/Introduction/Intro.html#//apple_ref/doc/uid/DTS40010933)

Last Revision:	Version 1.0, 2011-04-27

#Regions#

This sample demonstrates proper use of region monitoring, significant location changes, and handling location events in the background on iOS. The sample uses an MKMapView that allows the user to add and remove regions to monitor, as well as a UITableView to display the region enter/exit/fail events that occur. When the application goes into the background, location updates are stopped and significant location changes are started. Likewise, when the application enters the foreground, location updates are started again and significant location changes are stopped. When location updates occur in the background, a badge is added to the homescreen icon displaying the number of region enter/exit/fail events logged.

[URL](https://developer.apple.com/library/ios/#samplecode/Regions/Introduction/Intro.html#//apple_ref/doc/uid/DTS40010726)

Last Revision:	Version 1.1, 2011-03-23

#GKRocket#

The GKRocket sample application demonstrates the major features of GameKit. It uses GKSession and GKVoiceChatService to create a two player networked voice enabled game.

[URL](https://developer.apple.com/library/ios/#samplecode/GKRocket/Introduction/Intro.html#//apple_ref/doc/uid/DTS40009747)

Last Revision:	Version 1.1, 2011-03-15

#ThreadedCoreData#

Demonstrates how to use Core Data in a multi-threaded environment, following the first recommended pattern mentioned in the Core Data Programming Guide.

Based on the SeismicXML sample, it downloads and parses an RSS feed from the United States Geological Survey (USGS) that provides data on recent earthquakes around the world. What makes this sample different is that it persistently stores earthquakes using Core Data. Each time you launch the app, it downloads new earthquake data, parses it in an NSOperation which checks for duplicates and stores newly founded earthquakes as managed objects.

For those new to Core Data, it can be helpful to compare SeismicXML sample with this sample and notice the necessary ingredients to introduce Core Data in your application.

[URL](https://developer.apple.com/library/ios/#samplecode/ThreadedCoreData/Introduction/Intro.html#//apple_ref/doc/uid/DTS40010723)

Last Revision:	Version 1.0, 2011-03-01

#AVCam#

AVCam demonstrates how to use the AV Foundation capture APIs for recording movies and taking still images. There is a record button for recording movies, a camera button for switching between front and back cameras (on supported devices), and a still button for taking still images.

[URL](https://developer.apple.com/library/ios/#samplecode/AVCam/Introduction/Intro.html#//apple_ref/doc/uid/DTS40010112)

Last Revision:	Version 1.2, 2011-03-01

#avTouch#

The avTouch sample demonstrates use of the AVAudioPlayer class for basic audio playback.

The code in avTouch uses the AV Foundation framework to play a file containing AAC audio data. The application uses Core Graphics and OpenGL to display sound volume meters during playback.

This application shows how to:

* Create an AVAudioPlayer object from an input audio file.

* Use OpenGL and Core Graphics to display metering levels.

* Use Audio Session Services to set an appropriate audio session category for playback.

* Use the AVAudioPlayer interruption delegate methods to pause playback upon receiving an interruption, and to then resume playback if the interruption ends.

* Demonstrates a technique to perform Fast Forward and Rewind

avTouch does not demonstrate how to play multiple files, nor does it demonstrate more advanced use of AV Foundation.

[URL](https://developer.apple.com/library/ios/#samplecode/avTouch/Introduction/Intro.html#//apple_ref/doc/uid/DTS40008636)

Last Revision:	Version 1.4.2, 2011-02-08

#AdvancedURLConnections#

This sample demonstrates various advanced networking techniques with NSURLConnection. Specifically, it demonstrates how to respond to authentication challenges, how to modify the default server trust evaluation (for example, to support a server with a self-signed certificate), and how to provide client identities.

[URL](https://developer.apple.com/library/ios/#samplecode/AdvancedURLConnections/Introduction/Intro.html#//apple_ref/doc/uid/DTS40009558)

Last Revision:	Version 1.2, 2011-01-26

#AdvancedTableViewCells#

AdvancedTableViewCells includes three different cells that all display content in the same form as the App Store application. One uses individual subviews (image views, labels, etc.) to display the content. Another uses a single view that draws all of the content. A third uses a single view to draw most of the content and separate views for the remainder.

[URL](https://developer.apple.com/library/ios/#samplecode/AdvancedTableViewCells/Introduction/Intro.html#//apple_ref/doc/uid/DTS40009111)

Last Revision:	Version 1.5, 2011-01-11

#MoveMe#

This application illustrates simple drawing, touch handling, and animation using UIKit and Core Animation.

A touch inside a placard animates it in two ways: Its transform is changed such that it appears to pulse, and it is moved such that its center is directly under the touch.

A drag moves the placard so that it remains centered under the touch. When the touch ends, the placard is animated back to the center of the screen, and its original (identity) transform restored.

[URL](https://developer.apple.com/library/ios/#samplecode/MoveMe/Introduction/Intro.html#//apple_ref/doc/uid/DTS40007315)

Last Revision:	Version 2.10, 2010-12-23

#MessageComposer#

This application shows how to target older OS versions while building with newly released APIs. It also illustrates how to use the MessageUI framework to compose and send email and SMS messages from within your application.

[URL](https://developer.apple.com/library/ios/#samplecode/MessageComposer/Introduction/Intro.html#//apple_ref/doc/uid/DTS40010161)

Last Revision:	Version 1.1, 2010-11-08

#Icons#

This sample demonstrates the proper use of application icons on iOS. This is a universal binary that supports iPhone/iPod touch/iPad and includes support for high resolution displays.

Each icon has one dimension of the pixel dimensions on it to display which icon is being used by various areas of iOS. The various icons display when using the Homescreen, Spotlight, the Settings app, different devices, and when creating an Ad Hoc build and adding it to iTunes.

[URL](https://developer.apple.com/library/ios/#samplecode/Icons/Introduction/Intro.html#//apple_ref/doc/uid/DTS40010442)

Last Revision:	Version 1.0, 2010-10-22

#WiTap#

The WiTap sample application demonstrates how to achieve network communication between applications. Using Bonjour, the application both advertises itself on the local network and displays a list of other instances of this application on the network.

[URL](https://developer.apple.com/library/ios/#samplecode/WiTap/Introduction/Intro.html#//apple_ref/doc/uid/DTS40007321)

Last Revision:	Version 1.8, 2010-10-22

#MVCNetworking#

MVCNetworking is a sample that shows how to create a network application using the Model-View-Controller design pattern. Specifically, it displays a photo gallery by getting the gallery's XML description, thumbnails and photos from a web server, and uses Core Data to cache this information locally.

[URL](https://developer.apple.com/library/ios/#samplecode/MVCNetworking/Introduction/Intro.html#//apple_ref/doc/uid/DTS40010443-Intro-DontLinkElementID_2)

Last Revision:	Version 1.0, 2010-10-22

#GKTapper#

GKTapper is a sample application that shows how to support GameCenter Leaderboards and Achievements. It also demonstrates using GKLeaderboardViewController and GKAchievementViewController to display this data.

[URL](https://developer.apple.com/library/ios/#samplecode/GKTapper/Introduction/Intro.html#//apple_ref/doc/uid/DTS40010283)

Last Revision:	Version 1.1, 2010-12-10

#iPhoneACFileConvertTest#

Demonstrates using the Audio Converter APIs to convert from a PCM audio format to a compressed format.

Four encoding formats may be chosen in the UI along with different sample rates for the produced output.caf file. AAC encoding using Audio Converter requires 4.1 or later and a hardware capable device such as the iPhone 3GS. If run on a device which does not support hardware assisted AAC encoding, the AAC encoding choice will be dimmed.

Interruption handling during processing is also demonstrated. Hardware assisted encoding requires specific interruption handling since the codec state may change due to the interruption.

All the relevant audio specific code is in the file AudioConverterFileConvert.cpp.

Also see the companion to this sample - iPhoneExtAudioFileConvertTest.

[URL](https://developer.apple.com/library/ios/#samplecode/iPhoneACFileConvertTest/Introduction/Intro.html#//apple_ref/doc/uid/DTS40010581)

Last Revision:	Version 1.0, 2010-12-10

#Popovers#

This sample demonstrates proper use of UIPopoverController in iOS. UIPopoverController presentation, dismissing, and rotation handling are covered. The sample is provided using a UISplitViewController in order to show proper handling of UIPopoverControllers being presented from UIBarButtonItems. Additional handling ensures that multiple UIPopoverControllers are never presented at the same time.

[URL](https://developer.apple.com/library/ios/#samplecode/Popovers/Introduction/Intro.html#//apple_ref/doc/uid/DTS40010436)

Last Revision:	Version 1.0, 2010-10-20

#aurioTouch#

aurioTouch demonstrates use of the remote i/o audio unit for handling audio input and output. The application can display the input audio in one of the forms, a regular time domain waveform, a frequency domain waveform (computed by performing a fast fourier transform on the incoming signal), and a sonogram view (a view displaying the frequency content of a signal over time, with the color signaling relative power, the y axis being frequency and the x as time).

The code in auriouTouch uses the remote i/o audio unit (AURemoteIO) for input and output of audio, and OpenGL for display of the input waveform. The application also uses Audio Session Services to manage route changes (as described in Core Audio Overview).

[URL](https://developer.apple.com/library/ios/#samplecode/aurioTouch/Introduction/Intro.html#//apple_ref/doc/uid/DTS40007770)

Last Revision:	Version 1.21, 2010-10-20

#PageControl#

This application primarily demonstrates use of UIScrollView's paging functionality to use horizontal scrolling as a mechanism for navigating between different pages of content. With the iPad, this type of user interface is not really necessary since the screen is larger allowing for more content and detailed information.

Designed as a universal application for both iPhone and iPad, this sample shows how to use two different sets of content, depending on which device the sample is running. The idea is that the iPhone uses a "smaller" set of images, while the iPad uses a "larger" set of images plus more detailed information.  As a universal app this sample shows how to factor out these two types of UI and data based on the device.

For the iPhone - The app uses UIScrollView and UIPageControl to move between pages. For the iPad - The app uses one large UIView with tiled pages, each page presenting a popover to display more detailed information.

Based on the UIDevice idiom type, the UIApplication delegate loads two different set of nib files, one for the iPhone and the other for the iPad.  To direct this kind of UI factoring, the sample uses a base class called "ContentController". Subclasses of ContentController are used to support each device. Hence, the app loads two different user interfaces (or xibs) as well as two different sets of data driven by the ContentController.

[URL](https://developer.apple.com/library/ios/#samplecode/PageControl/Introduction/Intro.html#//apple_ref/doc/uid/DTS40007795)

Last Revision:	Version 1.4, 2010-10-18

#ListAdder#

This sample demonstrates the technique of thread confinement using NSOperation. It was written to support TN2109 "Simple and Reliable Threading with NSOperation".

[URL](https://developer.apple.com/library/ios/#samplecode/ListAdder/Introduction/Intro.html#//apple_ref/doc/uid/DTS40010275)

Last Revision:	Version 1.0, 2010-08-27

#BatteryStatus#

Demonstrates the use of the battery status properties and notifications provided via the iOS SDK.

[URL](https://developer.apple.com/library/ios/#samplecode/BatteryStatus/Introduction/Intro.html#//apple_ref/doc/uid/DTS40008812)

Last Revision:	Version 1.1, 2010-07-22

#Reachability#

The Reachability sample application demonstrates how to use the SystemConfiguration framework to monitor the network state of an iPhone or iPod touch. In particular, it demonstrates how to know when IP can be routed and when traffic will be routed through a Wireless Wide Area Network (WWAN) interface such as EDGE or 3G.

[URL](https://developer.apple.com/library/ios/#samplecode/Reachability/Introduction/Intro.html#//apple_ref/doc/uid/DTS40007324)

Last Revision:	Version 2.2, 2010-07-20

#GLImageProcessing#

The GLImageProcessing sample application demonstrates how to implement simple image processing filters (Brightness, Contrast, Saturation, Hue rotation, Sharpness) using OpenGL ES1.1. The sample also shows how to create simple procedural button icons using CoreGraphics.

By looking at the code you'll see how to set up an OpenGL ES view and use it for applying a filter to a texture. The application creates a texture from an image loaded from disk. It pads the image to a power of two, if required by the GPU.

The Debug configuration in the Xcode project defines DEBUG and ASSERT preprocessor macros, to enable additional error checking.

To use this sample, open it in Xcode and click Build and Go. Use the slider to control the current filter. Only a single filter is applied at a time.

[URL](https://developer.apple.com/library/ios/#samplecode/GLImageProcessing/Introduction/Intro.html#//apple_ref/doc/uid/DTS40009053)

Last Revision:	Version 1.2, 2010-06-29

#TouchCells#

Demonstrates how to implement trackable-settable UIControls embedded in a UITableView. This approach is handy if an application already uses its accessory view to the right of the table cell, but still wants a check mark view that supports toggling states of individual row items. The green check mark on the left provides this need which is trackable (checked/unchecked) independent of table selection. This is a similar user interface to that of Mail's Inbox table where mail items can be individually checked and unchecked for deletion.

[URL](https://developer.apple.com/library/ios/#samplecode/TouchCells/Introduction/Intro.html#//apple_ref/doc/uid/DTS40008062)

Last Revision:	Version 1.4, 2010-06-29

#HazardMap#

Demonstrates how to create a custom Map Kit overlay to display USGS earthquake hazard data. It shows how to create a custom Map Kit overlay and corresponding view to display USGS earthquake hazard data on top of an MKMapView.

For more information on earthquake hazard data, see "http://earthquake.usgs.gov/hazards/products/conterminous/2008/data/".

[URL](https://developer.apple.com/library/ios/#samplecode/HazardMap/Introduction/Intro.html#//apple_ref/doc/uid/DTS40010049)

Last Revision:	Version 1.1, 2010-08-24

#SeismicXML#

The SeismicXML sample application demonstrates how to use NSXMLParser to parse XML data. When you launch the application it downloads and parses an RSS feed from the United States Geological Survey (USGS) that provides data on recent earthquakes around the world. It displays the location, date, and magnitude of each earthquake, along with a color-coded graphic that indicates the severity of the earthquake. The XML parsing occurs on a background thread using NSOperation and updates the earthquakes table view with batches of parsed objects.

[URL](https://developer.apple.com/library/ios/#samplecode/SeismicXML/Introduction/Intro.html#//apple_ref/doc/uid/DTS40007323)

Last Revision:	Version 2.3, 2010-08-18

#AppPrefs#

Demonstrates how to display your app's preferences or settings in the "Settings" system application. A settings bundle, included in your application’s bundle directory, contains the information needed by the Settings application to display your preferences and make it possible for the user to modify them. It then saves any configured values in the defaults database so that your application can retrieve them at runtime.

This sample also shows how to dynamically update it's UI when its settings are changed while the app is in the background via "NSUserDefaultsDidChangeNotification".

This sample offers an Xcode project already pre-configured to build your Settings bundle as a target. To customize your settings UI, change the Root.plist file.

[URL](https://developer.apple.com/library/ios/#samplecode/AppPrefs/Introduction/Intro.html#//apple_ref/doc/uid/DTS40007799)

Last Revision:	Version 1.5, 2010-06-29

#GLSprite#

The GLSprite sample application shows how to create a texture from an image. By looking at the code, you'll learn how to use Core Graphics to create a bitmap context and draw an image into the context. You'll then see how to use OpenGL ES to create a texture from the image data.

[URL](https://developer.apple.com/library/ios/#samplecode/GLSprite/Introduction/Intro.html#//apple_ref/doc/uid/DTS40007325)

Last Revision: Version 1.9, 2010-08-18

#GLPaint#

The GLPaint sample application demonstrates how to support single finger painting using OpenGL ES. This sample also shows how to detect a "shake" motion of the device. By looking at the code you'll see how to set up an OpenGL ES view and use it for rendering painting strokes. The application creates a brush texture from an image by first drawing the image into a Core Graphics bitmap context. It then uses the bitmap data for the texture. The image used for a texture must have dimensions that are a power of 2.

[URL](https://developer.apple.com/library/ios/#samplecode/GLPaint/Introduction/Intro.html#//apple_ref/doc/uid/DTS40007328)

Last Revision:	Version 1.11, 2010-08-04

#Audio Mixer (MixerHost)#

MixerHost demonstrates how to use the Multichannel Mixer audio unit in an iOS application. It also demonstrates how to use a render callback function to provide audio to an audio unit input bus. In this sample, the audio delivered by the callback comes from two short loops read from disk. You could use a similar callback, however, to synthesize sounds to feed into a mixer unit. This sample is described in Audio Unit Hosting Guide for iOS.

[URL](https://developer.apple.com/library/ios/#samplecode/MixerHost/Introduction/Intro.html#//apple_ref/doc/uid/DTS40010210)

Last Revision:	Version 1.0, 2010-07-27

#Audio UI Sounds (SysSound)#

Demonstrates use of System Sound Services (AudioToolbox/AudioServices.h) to play alerts and user-interface sound effects, and to invoke vibration.

[URL](https://developer.apple.com/library/ios/#samplecode/SysSound/Introduction/Intro.html#//apple_ref/doc/uid/DTS40008018)

Last Revision:	Version 1.1, 2010-07-27

#EADemo#

The sample can be used with any Made For iPod (MFI) device designed for use with the External Accessory Framework. The application will display an External Accessory attached device in the Accessories window, provide information registered by the MFI device, and provides methods to send and receive data to the device.

[URL](https://developer.apple.com/library/ios/#samplecode/EADemo/Introduction/Intro.html#//apple_ref/doc/uid/DTS40010079)

Last Revision:	Version 1.1, 2010-07-26

#iPhoneExtAudioFileConvertTest#

Demonstrates using ExtAudioFile API to convert from one audio format and file type to another.

Four encoding formats may be chosen in the UI along with different sample rates for the produced output.caf file. AAC encoding requires both iPhone OS 3.1 and a hardware capable device such as the iPhone 3GS. If run on a device which does not support hardware assisted AAC encoding, the AAC encoding choice will be dimmed.

Interruption handling during processing is also demonstrated. Hardware assisted encoding requires specific interruption handling since the codec state may change due to the interruption.

All the relevant audio specific code is in the file ExtAudioFileConvert.cpp.

[URL](https://developer.apple.com/library/ios/#samplecode/iPhoneExtAudioFileConvertTest/Introduction/Intro.html#//apple_ref/doc/uid/DTS40009222)

Last Revision:	Version 1.1, 2010-07-22

#GenericKeychain#

This sample shows how to add, query for, remove, and update a keychain item of generic class type. Also demonstrates the use of shared keychain items. All classes exhibit very similar behavior so the included examples will scale to the other classes of Keychain Item: Internet Password, Certificate, Key, and Identity.

[URL](https://developer.apple.com/library/ios/#samplecode/GenericKeychain/Introduction/Intro.html#//apple_ref/doc/uid/DTS40007797)

Last Revision:	Version 1.2, 2010-07-22

#LocateMe#

This demonstrates the two primary use cases for the Core Location Framework: getting the user's location and tracking changes to the user's location.

[URL](https://developer.apple.com/library/ios/#samplecode/LocateMe/Introduction/Intro.html#//apple_ref/doc/uid/DTS40007801)

Last Revision:	Version 2.2, 2010-07-09

#XMLPerformance#

This sample explores two approaches to parsing XML, focusing on performance with respect to speed, memory footprint, and user experience. The XML data used is the current "Top 300" songs from the iTunes store. The data itself is not particularly important to the sample - it was chosen because of its simplicity, availability, and because the size (approximately 850KB) is sufficient to demonstrate the performance issues central to the sample.

[URL](https://developer.apple.com/library/ios/#samplecode/XMLPerformance/Introduction/Intro.html#//apple_ref/doc/uid/DTS40008094)

Last Revision:	Version 1.3, 2010-07-08

#iPhoneMultichannelMixerTest#

Demonstrates how to build an Audio Unit Graph connecting a Multichannel Mixer instance to the RemoteIO unit. Two input busses are created each with input volume controls. An overall mixer output volume control is also provided and each bus may be enabled or disabled.

[URL](https://developer.apple.com/library/ios/#samplecode/iPhoneMultichannelMixerTest/Introduction/Intro.html#//apple_ref/doc/uid/DTS40009113)

Last Revision:	Version 1.1, 2010-07-07

#GLES2Sample#

PowerVR SGX platforms support both OpenGL ES 1.1 and 2.0. This sample demonstrates how to create an OpenGL ES 1.1 and 2.0 compatible project. When running on PowerVR MBX platforms (e.g.,1st and 2nd generation iPod touch, 1st generation iPhone, iPhone 3G), the sample draws using OpenGL ES 1.1; when running on PowerVR SGX platforms (e.g., iPhone 3GS and 3rd generation iPod touch), the sample draws using OpenGL ES 2.0.

[URL](https://developer.apple.com/library/ios/#samplecode/GLES2Sample/Introduction/Intro.html#//apple_ref/doc/uid/DTS40009188)

Last Revision:	Version 1.1, 2010-07-07

#GLGravity#

The GLGravity sample application demonstrates how to use the UIAccelerometer class in combination with OpenGL rendering. It shows how to extract the gravity vector from the accelerometer values using a basic low-pass filter, and how to build an OpenGL transformation matrix from it.

[URL](https://developer.apple.com/library/ios/#samplecode/GLGravity/Introduction/Intro.html#//apple_ref/doc/uid/DTS40007327)

Last Revision:	Version 2.2, 2010-07-06

#WeatherMap#

Demonstrates the use of the MapKit framework, displaying a map view with custom MKAnnotationViews.

An annotation object on a map is any object that conforms to the MKAnnotation protocol and is displayed on the screen as a MKAnnotationView. Through the use of the MKAnnotation protocol and MKAnnotationView, this application identifies four major cities in North America with fictitious weather information.

[URL](https://developer.apple.com/library/ios/#samplecode/WeatherMap/Introduction/Intro.html#//apple_ref/doc/uid/DTS40009491)

Last Revision:	Version 1.1, 2010-07-01

#Formulaic#

Formulaic is a sample iPhone app that illustrates how to effectively use the iPhone Accessibility API. Using the Accessibility API allows your app to work correctly with VoiceOver.

The app draws a graph of a formula and allows the user to change certain constants in the formula, however its main purpose is to illustrate the iPhone Accessibility API.

[URL](https://developer.apple.com/library/ios/#samplecode/Formulaic/Introduction/Intro.html#//apple_ref/doc/uid/DTS40008932)

Last Revision:	Version 1.2, 2010-07-01

#TaggedLocations#

This sample illustrates how to manipulate attributes and relationships in an iPhone application.

The application extends the the completed project from the Core Data Tutorial for iPhone OS. The first screen displays a table view of events, which encapsulate a time stamp, a geographical location expressed in latitude and longitude, and a name for the event. The user can add, remove, and edit events using the first screen.

Events have a to-many relationship to tags (which have an inverse to-many relationship to events). Tags have a name which describes a feature of an event. Tags are displayed in a second table view; when a tag is related to the selected event, a check mark is displayed in the corresponding row.

[URL](https://developer.apple.com/library/ios/#samplecode/TaggedLocations/Introduction/Intro.html#//apple_ref/doc/uid/DTS40008914)

Last Revision:	Version 1.3, 2010-06-29

#HeaderFooter#

Demonstrates how to implement and customize the 2 UIView properties of UITableView: header ('tableHeaderView') and footer ('tableFooterView'). It is designed to somewhat resemble the "Contacts" application, showing you ways to design your own header and footer content. It uses the UITableViewStyle: UITableViewStyleGrouped to achieve a more similar appearance as well.

[URL](https://developer.apple.com/library/ios/#samplecode/HeaderFooter/Introduction/Intro.html#//apple_ref/doc/uid/DTS40007989)

Last Revision:	Version 1.3, 2010-06-29

#oalTouch#

The code uses OpenAL to play a single audio source. Move source or listener position by dragging icons around on the grid. Turn accelerometer functionality on to set listener orientation by tilting the device.

[URL](https://developer.apple.com/library/ios/#samplecode/oalTouch/Introduction/Intro.html#//apple_ref/doc/uid/DTS40007769)

Last Revision:	Version 1.9, 2010-06-29

#AQOfflineRenderTest#

Demonstrates using Audio Queue offline render functionality and the AudioQueueOfflineRender API. The sample produces LPCM output buffers from an ALAC encoded source which are then written to a .caf file. The output.caf file is then played back confirming the offline functionality worked as expected. All the code demonstrating the Audio Queue is in a single file called aqofflinerender.cpp.

[URL](https://developer.apple.com/library/ios/#samplecode/AQOfflineRenderTest/Introduction/Intro.html#//apple_ref/doc/uid/DTS40008413)

Last Revision:	Version 1.2, 2010-06-28

#AccelerometerGraph#

AccelerometerGraph sample application graphs the motion of the device. It demonstrates how to use the UIAccelerometer class and how to use Quartz2D and Core Animation to provide a high performance graph view. It also demonstrates a low-pass filter that you can use to isolate the effects of gravity, and a high-pass filter that you can use to remove the effects of gravity.

[URL](https://developer.apple.com/library/ios/#samplecode/AccelerometerGraph/Introduction/Intro.html#//apple_ref/doc/uid/DTS40007410)

Last Revision:	Version 2.5, 2010-06-28

#Teslameter#

This application implements a Teslameter, a magnetic field detector. It displays the raw x, y, and z magnetometer values, a plotted history of those values, and a computed magnitude (size or strength) of the magnetic field.

The use of the Core Location API for getting "heading" data is contained in the TeslameterViewController class. It creates a CLLocationManager object and uses it to get heading by invoking -[CLLocationManager startUpdatingHeading]. It implements the CLLocationManagerDelegate APIs for receiving heading and updates its user interface accordingly.

[URL](https://developer.apple.com/library/ios/#samplecode/Teslameter/Introduction/Intro.html#//apple_ref/doc/uid/DTS40008931)

Last Revision:	Version 1.2, 2010-06-28

#SimpleEKDemo#

The application uses table views to display EKCalendar object and EKEvent objects retrieved from an EKEventStore object. It implements EKEventViewController for viewing and editing existing EKEvents, and uses EKEventEditViewController for creating new EKEvents.

[URL](https://developer.apple.com/library/ios/#samplecode/SimpleEKDemo/Introduction/Intro.html#//apple_ref/doc/uid/DTS40010160)

Last Revision:	Version 1.0, 2010-06-25

#SimpleEKDemo#

The application uses table views to display EKCalendar object and EKEvent objects retrieved from an EKEventStore object. It implements EKEventViewController for viewing and editing existing EKEvents, and uses EKEventEditViewController for creating new EKEvents.

[URL](https://developer.apple.com/library/ios/#samplecode/SimpleEKDemo/Introduction/Intro.html#//apple_ref/doc/uid/DTS40010160)

Last Revision:	Version 1.0, 2010-06-25

#MapCallouts#

Demonstrates the use of the MapKit framework, displaying a map view with custom MKAnnotations each with custom callouts. An annotation object on a map is any object that conforms to the MKAnnotation protocol and is displayed on the screen as a MKAnnotationView. Through the use of the MKAnnotation protocol and MKAnnotationView, this application shows how you can extend annotations with custom strings and left/right calloutAccessoryViews.

[URL](https://developer.apple.com/library/ios/#samplecode/MapCallouts/Introduction/Intro.html#//apple_ref/doc/uid/DTS40009746)

Last Revision:	Version 1.2, 2010-06-25

#DateSectionTitles#

This application shows how to create section information for NSFetchedResultsController using dates.

A single table view controller displays events sorted by date and grouped into sections by year and month. The Event entity has three attributes:

* timeStamp (persistent NSDate object).

The time stamp represents the time the event occurred.

* title (persistent NSString object).

The title of each event as it will be displayed on a row in the table view (this is not to be confused with section title). When the default data is created in the application delegate, the title is initialized to a string representation of the date.

* sectionIdentifier (transient NSString object).

The sectionIdentifier is used to divide the events into sections in the table view. It is a string value representing the number ((year * 1000) + month). Using this value, events can be correctly ordered chronologically regardless of the actual name of the month. It is calculated and cached on demand in the custom accessor method.

The sorting is all done at fetch time by the fetched results controller. The section name transformations are UI level and have no effect on the order of data.

[URL](https://developer.apple.com/library/ios/#samplecode/DateSectionTitles/Introduction/Intro.html#//apple_ref/doc/uid/DTS40009939)

Last Revision:	Version 1.2, 2010-06-25

#WorldCities#

Demonstrates basic use of MapKit, including displaying a map view and setting its region.

A list of cities are stored in a plist file loaded at launch time. Each city is represented by a "WorldCity" class which consists of a name, a latitude, and a longitude. The user can select from a pre-defined world cities. When a world cities is selected, the map view animates to a region with the coordinates of the world cities in the center of the view. The user can also choose between map types - Standard, Satellite, and Hybrid - using the segmented control in the toolbar of the main view.

[URL](https://developer.apple.com/library/ios/#samplecode/WorldCities/Introduction/Intro.html#//apple_ref/doc/uid/DTS40009466)

Last Revision:	Version 1.1, 2010-06-25

#QuartzDemo#

QuartzDemo is an iPhone OS application that demonstrates many of the Quartz2D APIs made available by the CoreGraphics framework. Quartz2D forms the foundation of all drawing on iPhone OS and provides facilities for drawing lines, polygons, curves, images, gradients, PDF and many other graphical facilities.

[URL](https://developer.apple.com/library/ios/#samplecode/QuartzDemo/Introduction/Intro.html#//apple_ref/doc/uid/DTS40007531)

Last Revision:	Version 2.5, 2010-06-25

#iPhoneMixerEQGraphTest#

iPhoneMixerEQGraphTest demonstrates how to build an Audio Unit Graph connecting a MultiChannel Mixer to the iPodEQ unit then to the RemoteIO unit.

Two input busses are created each with input volume controls. An overall mixer output volume control is also provided and each bus may be enabled or disabled. The iPodEQ may be enabled or disabled and a preset EQ curve may be chosen via a picker in the iPod Equalizer view. iPhoneMixerEQGraphTest uses 44.1kHz source and sets the hardware sample rate to 44.1kHz to avoid any extraneous sample rate conversions.

Touching the "Play Audio" button simply calls AUGraphStart while "Stop Audio" calls AUGraphStop. Changing AU volume is performed via AudioUnitSetParameter. The iPodEQ unit presets are returned by using AudioUnitGetProperty asking for the kAudioUnitProperty_FactoryPresets CFArrayRef. A current preset is then selected calling AudioUnitSetProperty using the kAudioUnitProperty_PresentPreset property and passing in the appropriate AUPreset. Note that the AU Host owns the returned CFArray and should release it when done.

Audio data is provided from two stereo audio files. The audio data is AAC compressed and ExtAudioFile is used to convert this data to the Core Audio Canonical uncompressed LPCM client format for input to the multichannel mixer.

All the relevant audio code is in the file AUGraphController.mm

[URL](https://developer.apple.com/library/ios/#samplecode/iPhoneMixerEQGraphTest/Introduction/Intro.html#//apple_ref/doc/uid/DTS40009555)

Last Revision:	Version 1.2, 2010-06-25

#GLTextureAtlas#

This sample demonstrates how to use a texture atlas to draw multiple objects with different textures simultaneously using OpenGL ES. The application uses a texture atlas in the PVR format. By adding in degenerated triangles, and compute 3D transformations ourselves using matrices, we are able to collapse all the draw calls into one.

[URL](https://developer.apple.com/library/ios/#samplecode/GLTextureAtlas/Introduction/Intro.html#//apple_ref/doc/uid/DTS40009014)

Last Revision:	Version 1.5, 2010-06-25

#TransWeb#

Demonstrates how to implement UIWebView with a transparent background.

To achieve this you need to make the HTML body's background color transparent by doing the following -

1) set the UIWebView's backgroundColor property to [UIColor clearColor]

2) use the UIWebView's content in the html: <body style="background-color: transparent">

3) the UIWebView's opaque property set to NO

[URL](https://developer.apple.com/library/ios/#samplecode/TransWeb/Introduction/Intro.html#//apple_ref/doc/uid/DTS40008614)

Last Revision:	Version 1.4, 2010-06-25

#LaunchMe#

The LaunchMe sample application demonstrates how to register a new URL type. Registering a new URL type allows other applications to interact with yours. This sample also shows how to handle an incoming openURL: message from another application. When servicing an openURL: message from another application, you must be very careful to validate the URL in the message before allowing your application to proceed. After you build and run LaunchMe, it displays a dialog with instructions on how to use the application.

[URL](https://developer.apple.com/library/ios/#samplecode/LaunchMe/Introduction/Intro.html#//apple_ref/doc/uid/DTS40007417)

Last Revision:	Version 1.6, 2010-06-24

#TableViewSuite#

This sample shows how to use UITableView through a progression of increasingly advanced applications that display information about time zones.

The first example shows a simple list of the time zone names. It shows how to display a simple data set in a table view.

The second example shows the time zones split into sections by region, with the region name as the section heading. It shows how to create an indexed table view.

The third example shows the time zones split into sections alphabetically, with the first letter of their locale name as the section heading. It shows how to set up a table view to display an index.

When implementing a table view cell, there's a tension between optimal scrolling performance and optimal edit/reordering performance. You should typically use subviews in the cell's content view.

When you have an edit or reordering control, using subviews makes the implementation easier, and the animations perform better because UIKit doesn't have to redraw during animations.

Subviews have two costs:

1) Initialization. This can be largely mitigated by reusing table cells. 2) Compositing. This can be largely mitigated by making the views opaque. Often, one translucent subview is fine, but more than one frequently causes frame drops while scrolling.

If the content is complex, however (more than about three subviews), scrolling performance may suffer. If this becomes a problem, you can instead draw directly in a subview of the table view cell's content view.

The fourth example displays more information about each time zone, such as the time and relative day in that time zone. Its main aim is to show how you can customize a table view cell using subviews. It also introduces custom classes to represent regions and time zones to help reduce the overhead of calculating the required information -- these are also used in the fifth example.

The fifth example is an extension of the fourth. It displays even more information about each time zone, such as the time and relative day in that time zone. Its shows how you can create a custom table view cell that contains a custom view that draws its content in -drawRect:.

[URL](https://developer.apple.com/library/ios/#samplecode/TableViewSuite/Introduction/Intro.html#//apple_ref/doc/uid/DTS40007318)

Last Revision:	Version 2.4, 2010-06-24

#Scrolling#

Demonstrates how to implement two different style UIScrollViews. The first scroller contains multiple images, showing how to layout large content with multiple chunks of data (in our case 5 separate UIImageViews).

The second scroller simply displays one image, matching its contentSize to the image size. The app's primary UIViewController manages both scrollers. Refer to this sample for best practices in how to implement content with a single image or with multiple images.

[URL](https://developer.apple.com/library/ios/#samplecode/Scrolling/Introduction/Intro.html#//apple_ref/doc/uid/DTS40008023)

Last Revision:	Version 1.1, 2010-06-23

#TheElements#

TheElements is a sample application that provides access to the data contained in the Periodic Table of the Elements. The Periodic Table of the Elements catalogs all the known atomic elements in the universe.

TheElements provides this data in multiple formats, allowing you to sort the data by name, atomic number, symbol name, and an element's physical state at room temperature.

TheElements is structured as a Model-View-Controller application. There is distinct separation of the model data, the views used to present that data, and the controllers which act as a liaison between the model and controller.

The application illustrates the following techniques: configuring and responding to selections in a tab bar, displaying information in a tableview using both plain and grouped style table views, using navigation controllers to navigate deeper into a data structure, subclassing UIView, providing a custom UITableViewCell consisting of multiple subviews, implementing the UITableViewDelegate protocol, implementing the UITableViewDataSource protocol, reacting to taps in views, open a URL to an external web site using Safari, flipping view content from front to back, and creating a reflection of a view in the interface.

[URL](https://developer.apple.com/library/ios/#samplecode/TheElements/Introduction/Intro.html#//apple_ref/doc/uid/DTS40007419)

Last Revision:	Version 1.11, 2010-06-23

#SimpleUndo#

The root view controller displays information (title, author, and copyright date) about a book. The user can edit this information by tapping Edit in the navigation bar. When editing starts, the root view controller creates an undo manager to record changes. The undo manager supports up to three levels of undo and redo. When the user taps Done, changes are considered to be committed and the undo manager is disposed of.

[URL](https://developer.apple.com/library/ios/#samplecode/SimpleUndo/Introduction/Intro.html#//apple_ref/doc/uid/DTS40008408)

Last Revision:	Version 1.1, 2010-06-23

#Accessory#

Demonstrates how to implement a custom accessory view for your UITableView in the form of a checkmark button. It shows you how to override the appearance or control of the accessory view, much like that of "UITableViewCellAccessoryDetailDisclosureButton". It implements the custom accessory view by setting the table's "accessoryView" property with a UIButton of type "UIButtonTypeCustom". It can be toggled by selecting the entire table row by implementing UITableView's "didSelectRowAtIndexPath". The green checkmark is trackable (checked/unchecked), and can be toggled independent of table selection.

[URL](https://developer.apple.com/library/ios/#samplecode/Accessory/Introduction/Intro.html#//apple_ref/doc/uid/DTS40008066)

Last Revision:	Version 1.2, 2010-06-23

#MailComposer#

See new sample code "MessageComposer" which includes both Mail and Messages features.

This application shows how to target older OS versions while building with newly released APIs. It also illustrates how to use the MessageUI framework to edit and send email messages from within your application.

Tap the "Compose Mail" button to display an email composition interface if your device is running iPhone OS 3.0 or launch the Mail application, otherwise.

[URL](https://developer.apple.com/library/ios/#samplecode/MailComposer/Introduction/Intro.html#//apple_ref/doc/uid/DTS40008865)

Last Revision:	Version 1.1, 2010-06-22

#DateCell#

Demonstrates formatted display of date objects in UITableViewCells and use of UIDatePicker to edit those values.

Using a grouped style UITableViewController, the sample has two UITableViewCells to draw the primary title and NSDate value. This is accomplished using the built-in cell type "UITableViewCellStyleValue1" which supports left and right text. In addition, this sample shows how to use NSDateFormatter class to achieve the custom cell's date-formatted appearance.

[URL](https://developer.apple.com/library/ios/#samplecode/DateCell/Introduction/Intro.html#//apple_ref/doc/uid/DTS40008866)

Last Revision:	Version 1.1, 2010-06-17

#TableSearch#

Demonstrates how to search the contents of a UITableView using UISearchBar and UISearchDisplayController, effectively filtering in and out the contents of that table. If an iPhone/iPod Touch application has large amounts of table data, this sample shows how to filter it down to a manageable amount if memory usage is a concern or you just want users to scroll through less table content.

[URL](https://developer.apple.com/library/ios/#samplecode/TableSearch/Introduction/Intro.html#//apple_ref/doc/uid/DTS40007848)

Last Revision:	Version 1.5, 2010-06-17

#BonjourWeb#

This application illustrates the fundamentals of browsing for network services using Bonjour. The BonjourBrowser hierarchically displays Bonjour domains and services as table views in a navigation controller. The contents of the table views are discovered and updated dynamically using NSNetServiceBrowser objects. Tapping an item in the services table causes the corresponding NSNetService object to be resolved asynchronously. When that resolution completes, a delegate method is called which constructs a URL and opens it in Safari.

[URL](https://developer.apple.com/library/ios/#samplecode/BonjourWeb/Introduction/Intro.html#//apple_ref/doc/uid/DTS40007415)

Last Revision:	Version 2.9, 2010-06-16

#AddMusic#

AddMusic demonstrates basic use of iPod library access, part of the Media Player framework. You use iPod library access to play songs, audio books, and audio podcasts that are synced from a user's desktop iTunes library. This sample uses the Media Player framework's built-in user interface for choosing music.  AddMusic also demonstrates how to mix application audio with iPod library audio. The sample includes code for configuring application audio behavior using the AVAudioSession class and Audio Session Services.
 
 [URL](https://developer.apple.com/library/ios/#samplecode/AddMusic/Introduction/Intro.html#//apple_ref/doc/uid/DTS40008845)
 
Last Revision:	Version 1.1.1, 2009-10-01

#GKTank#

GKTank is a sample application that shows how to use the GKSession and GKPeerPickerController classes in the GameKit framework to add Peer-to-Peer Connectivity to an application.

[URL](https://developer.apple.com/library/ios/#samplecode/GKTank/Introduction/Intro.html#//apple_ref/doc/uid/DTS40008918)

Last Revision:	Version 1.0.1, 2009-06-08

#Not Include#
[FastEnumerationSample](https://developer.apple.com/library/ios/samplecode/FastEnumerationSample/Introduction/Intro.html#//apple_ref/doc/uid/DTS40009411)

[Quartz Composer SQLiteQuery](https://developer.apple.com/library/ios/samplecode/SQLiteQuery/Introduction/Intro.html#//apple_ref/doc/uid/DTS40009327)

[Quartz Composer IMStatus](https://developer.apple.com/library/ios/samplecode/IMStatus/Introduction/Intro.html#//apple_ref/doc/uid/DTS40009321)

[Quartz Composer HistogramOperation](https://developer.apple.com/library/ios/samplecode/HistogramOperation/Introduction/Intro.html#//apple_ref/doc/uid/DTS40009319)

[Quartz Composer iPatch](https://developer.apple.com/library/ios/samplecode/iPatch/Introduction/Intro.html#//apple_ref/doc/uid/DTS40009322) 

[Quartz Composer Conceptual Compositions](https://developer.apple.com/library/ios/samplecode/Conceptual/Introduction/Intro.html#//apple_ref/doc/uid/DTS40009227)

[Birthdays](https://developer.apple.com/library/ios/samplecode/Birthdays/Introduction/Intro.html#//apple_ref/doc/uid/DTS10003982)