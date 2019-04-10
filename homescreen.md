---
layout: default
title: Homescreen
---
# Find a new homescreen for Ubuntu Touch
Hey guys. I would like to share some thoughts about this topic in this blog post. This is only my opinion and I hope that this could help to find a good solution.

### As UniSuperBox has written, we assume that "home" is this:
+ It is used to start other interactions with the environment (applications, for example)
+ It is "returnable," a user should always know how to get to it. Now that operating environments are used for multitasking, this shouldn't be by destroying all running activities.
+ It is "safe," a user should always know what to do once they get there
+ It should be a little bit customizable (We are not Gnome 3 :P)

### What is **home** on other systems? I have done some screenshots:

#### Android

![Screenshot_2019-04-10-07-31-49.png](/assets/images/android.png) 

A customizable *start*screen and non-customizable app drawer.

#### iOS

![ima_d939465.png](/assets/images/ios.png) 

Horizontal scrollable pages where all apps are present. Customizable with app folders.


#### Firefox OS

![737a843c39be00cad22d7a68939f865b.png](/assets/images/firefoxos.png) 

Vertical scrollable app drawer with possible appfolder customizations. (Still alife on kaiOS)

#### Sailfish OS

![serveimage.jpeg](/assets/images/sailfishos.jpeg) 

Vertical scrollable app drawer.

#### Windows Phone

Similar to android with strange tiles...

#### Conclusion

+ On all other mobile operating systems are "Homescreens".
+ From the homescreen you start your apps.
+ Sometimes homescreens are divided into a customizable widget part with the most apps and a non-customizable app drawer.
+ It is easy to reach the homescreen from anywhere in the system.
+ Home feels like something that is *below* all open apps. (The app drawer of Unity 8 would be *over* the apps) On the most desktop environments this is different. When you open the start menu it would be *over* all visible apps.
+ Homescreen is customizable.

#### How are other systems solving this?

On **Windows 10** there is a desktop and a tablet mode. On the desktop mode the start menu will be *over* the other apps. On tablet mode that start menu will always be visible so it feels like it is *below* the apps.

On **Gnome 3** the app drawer is hiding all apps and only showing the wallpaper in the background. This is interesting because you can not say weither the app drawer is *over* or *below* the open windows.

![serveimage.jpeg](/assets/images/gnome3.png) 

**Endless OS** is a desktop system which is using the mobile solution for the start menu. The *homescreen* of Endless OS is always *below* the open windows and the *minimize all windows* button is in fact the start menu button.

![serveimage.jpeg](/assets/images/endlessos.png) 

This leads to three different solution:

#### 1. Use the unity 8 app drawer in the same way Gnome 3 does

This would mean:
+ The launch animation of the app drawer would change. It will not slide in from the left but just appear. The current apps will just disappear without any 3D effects.
+ The app drawer will autostart when there are no apps open OR:
+ The homescreen gets some customizable features like widgets or app shortcuts

#### 2. Use a always *below* homescreen like on Endless OS

+ Same way like using the sprint app from Brian.

#### 3. Switch the 3D position of the homescreen like on Windows 10

+ On desktop mode everything stays the same like it is at the moment
+ On staged mode the app drawer will be always visible and you can't hide it. Tab on the circle of friends button will just minimize or hide all apps
