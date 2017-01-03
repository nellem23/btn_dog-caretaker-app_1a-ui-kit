<a href="https://tldrlegal.com/license/mit-license" target="_blank"><img src="https://img.shields.io/apm/l/vim-mode.svg?maxAge=2592000"></a>
<a href="http://www.animaapp.com" target="_blank"><img src="https://animaapp.s3.amazonaws.com/github/ExportCode/code_byanima.png" height="20"></a>
<img src="https://img.shields.io/badge/language-Swift-orange.svg">
[![Carthage compatible](https://img.shields.io/badge/Carthage-compatible-4BC51D.svg?style=flat)](https://github.com/Carthage/Carthage)

# btndogcaretakerappa UI Kit

btndogcaretakerappa UI Kit was designed by nelle@usebutton.com.


## CocoaPods installation

1. In your podfile add

   ``` pod 'btndogcaretakerappaUIKit', :git => 'https://github.com/nellem23/btn_dog-caretaker-app_1a-ui-kit.git'```
2. On the terminal, in your project folder, run ```pod install```



## Usage

`APbtndogcaretakerappaManager` Gives you an easy access to the storyboard.
Here's an easy way to start:

On `application:didFinishLaunchingWithOptions:` use this to start with btndogcaretakerappa UI Kit:

<img src="https://img.shields.io/badge/language-Swift-orange.svg">
```
import btndogcaretakerappaUIKit
```
```
   APbtndogcaretakerappaManager.shared().theme?.apply();
   self.window?.rootViewController = APbtndogcaretakerappaManager.shared().initialVC();
```
<img src="https://img.shields.io/badge/language-Obj--C-blue.svg">
```
#import <btndogcaretakerappaUIKit/APbtndogcaretakerappaManager.h>
```
```
   [[APbtndogcaretakerappaManager shared].theme apply];
   [self.window setRootViewController:[[APbtndogcaretakerappaManager shared] initialVC]];
```