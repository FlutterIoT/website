---
layout: post
title:  "What's new in Flutter 3.7?"
author: dantino
categories: [Flutter, Flutter 3.7, Flutter Updates]
image: assets/images/posts/what new in flutter 3_7.jpeg
tags: [featured]
---
# Flutter 3.7 Released- What are New Features, Enhancements & Modifications

The start of 2023 is fabulous for developers using Flutter, as Google has just released Flutter 3.7. Developers can further enhance the ease of the coding process with great new features. Additionally, Flutter has revamped and optimized the existing features. However, the Dart 3 stable release is still not announced but it will bring productivity and portability in future.

So, let us go through Flutter 3.7!

>## Table of Contents:
>  	
> 1. What are the New features in Flutter 3.7?
> 
> - Menu Bars & Cascading menus
>
> - Impeller preview
> 
> - iOS release validation
> 
> -  Custom context menus
> 
> 2. What improvements Flutter 3.7 brings?
> 
> 3. What modifications Flutter 3.7 brings?
> 
> 4. What’s Next for the Flutter community?

## What are the New features in Flutter 3.7?
Here are the new features announced in Flutter 3.7.

### **Menu Bars & Cascading menus** 
Developers can create menu bars and cascading menus by using Flutter. In macOS, the native menu bars are rendered by macOS itself and not by Flutter. You just have to use PlatformMenuBar to create a menu bar.

For platforms other than macOS, you can use MenuBar for cascading menu bars or standalone menus by MenuAnchor.

You are free to customize the complete menu bar according to yourself.

Menu Bars & Cascading menus

### **Impeller preview** 
The impeller rendering engine is ready for preview on iOS. Although there are still a few gaps in the API coverage, it will meet the rendering requirements of the majority of the apps.

In case of any issues, you can file issues here.

Impeller is not yet ready on Android, but team flutter will soon announce the same.

### **iOS release validation** 
iOS app rejections are common, which is why a large number of apps are rejected on the iOS app store. With iOS release validation, the Flutter build ipa command validates the release validations.

iOS release validation image

### **Custom context menus** 
You can create custom menus anywhere you want in your app.

For example, developers can visually present to users what they have selected through a hover-type menu.

contextMenuBuilder parameter can return the TextField.

Custom context menus image

## What improvements Flutter 3.7 brings?
1. In Flutter 3.7, Google has enhanced the material 3 support and migrated a bunch of widgets. To use the material 3 enhancements, you must specify useMaterial3 in the applications ThemeData widget. Flutter will generate a color scheme for you on its own. Here is how the complete code works.
What improvements Flutter 3.7 brings 1
2. DevTools are updated with the new Flutter 3.7 giving a great experience to the developers, especially while debugging.
3. Scrolling improvements are delivered with this release giving a better polish and refinement for the trackpad interactions. New widgets like ScrollBars and DraggableScrollableSheet will ensure the same.
4. Internationalization support is completely modified by the Flutter team. They now represent Descriptive syntax errors to let developers perform debugging in detail.
5. SelectionArea allows extended selection through the keyboard. For example, the Shift+right keyboard shortcut will work in Flutter apps. Also, the text magnifier glass appears during text selection.SelectionArea allows extended selection through the keyboard
6. iOS platformView BackdropFilter blurs the elements underneath the main element. It delivers the aim of delivering the best UIs to the users.iOS platformView BackdropFilter blurs the elements underneath the main element
7. Memory management is better with Flutter 3.7. It reduces junk after garbage collection, offering a better CPU utilization in the apps. The memory footprints are reduced from the previous version.
## What modifications Flutter 3.7 brings? 
The quick_actions plugin is migrated from Objective C to Swift, delivering updated and best development practices to the developers.
In Xcode 14, bitcode is no longer important while building apps for watchOS and tvOS. The app store does not accept bitcoder anymore during submissions.
## What’s Next for the Flutter community? 
Flutter seems all set to break through and highly enhance the graphics performance with Impeller.

The improvements and removal of unnecessary widgets are another major track where Flutter seems to be working. Further, the community is highly efficient in bringing appealing features and functionalities to make the UI experience fluid for the end users.

However, we are still waiting for the Dart 3 stable release.

