GBA4iOS (forked)
===========

![GBA4iOS](http://gba4iosapp.com/images/download/gba4ios2_devices.png)

This is a fork of the famous Game Boy Advance emulator for iOS.
Since the original developer @rileytestut does not maintain the project at the moment, I forked the project and manually fixed some bugs and features from the pull-requests (!).

I'm not an Objective-C programmer, I have just copy'n'pasted things together.
Credit goes out to the other folks. (pull-requests sources at the bottom)

### New Features ###

• Completely new emulator core based on VBA-M  
• iPad Support (broken at the moment?)
• Full GBC game compatibility
• Cheat Codes
• Dropbox Sync (buggy, can crash the app while setup)
• Customizable Skins
• Sustain Button
• Event Distribution
• Wario Ware: Twisted Support
• iOS 7 Controller support
• iCade Controller support (tested and mapped for '8BitDo NES30')
• URL Scheme support (gba4ios://ROM%20Name%20Here)

### Classic Features ###

• Save States  
• Portrait + Landscape layouts  
• Frameskip  
• iTunes File Sharing Support  
• Fast Forward  

Getting Started
=============

GBA4iOS can be opened in Xcode and deployed to an iOS device just like an other app, but there are a few steps that need to be completed first:

• Download and install [Cocoapods](http://cocoapods.org/)  
• From the root directory, run the following command in terminal:
`pod install`  
• Open up the .xcworkspace file, and deploy to your device!
• (Ignore the 150 errors for using deprecated functions 😰)

Requirements
=============

• GBA4iOS 2.0 requires Xcode 5 or later, targeting iOS 7.0 and above.  
• For deployment to iOS 6 devices, use the project in the 1.x branch.

Contact
========

GBA4iOS was created by developer [Riley Testut](http://twitter.com/rileytestut) and graphic designer [Paul Thorsen](http://twitter.com/pau1thor).

Used commits
=============

• iCade Bluetooth Support - [Mike Bignell](https://bitbucket.org/mikezs/gba4ios/commits/a1bfba5c1e939b0681a927a6c704bc88c5751edc?at=master)
• General Bugfixing – [Saagar Jha](https://bitbucket.org/saagarjha/gba4ios/commits/e30bebc8f3385498f167290ded608993db0d4714?at=master)
• 128k save support pulled from gambatte - [r.kuraev](https://bitbucket.org/naorunaoru/gba4ios/commits/c0ac55903afdb8d681e8331fa6ca12e5caacdb14?at=master)
