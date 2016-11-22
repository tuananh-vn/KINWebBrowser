Overview
------------------------
**`GCVETVHelpManager`** - a `Singleton` that support a float button.

**Init Singleton:**
```objective-c
GCVETVHelpManager *floatManager = [GCVETVHelpManager sharedManager];
```

**Init Singleton with frame:**
```objective-c
GCVETVHelpManager *floatManager = [GCVETVHelpManager sharedManagerWithFrame:CGRectMake(100, 100, 50, 50)];
```
**Set appid, access_token, serverurl, :**
```objective-c
    floatManager.appid = @"";
    floatManager.tokenID = @"";
    floatManager.serverURL = @"";
    floatManager.extraData = [[NSDictionary alloc] init];
```
**Set float button image:**
```objective-c
    [floatManager setHelpImage:[UIImage imageNamed:@""]];
```


**Show/Hide Float Button:**
```objective-c
    [floatManager showHelp];
    
    [floatManager hideHelp];
```

Installation
------------------------

#### CocoaPods
[CocoaPods](http://cocoapods.org) is a dependency manager for Objective-C, which automates and simplifies the process of using 3rd-party libraries in your projects. See the ["Getting Started" for more information](http://guides.cocoapods.org/using/getting-started.html).

###### Podfile

```ruby
platform :ios, '7.0'
pod 'KINWebBrowser', :git => 'https://github.com/tuananh-vn/KINWebBrowser.git'
```

Dependencies
------------------------
These dependency projects should be also installed with KINWebBrowser. They are installed automatically when installing KINWebBrowser with CocoaPods.

* [TUSafariActivity](https://github.com/davbeck/TUSafariActivity) -  a UIActivity subclass that provides an "Open In Safari" action to a UIActivityViewController
* [ARChromeActivity](https://github.com/alextrob/ARChromeActivity) - a UIActivity subclass that provides an "Open In Google Chrome" action to a UIActivityViewController

