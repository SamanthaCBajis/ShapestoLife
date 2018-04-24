# ShapestoLife
An example video of this application built and running on device can be found on my [YouTube Channel.](https://www.youtube.com/watch?v=V_CQ3XSHMOA&t=4s "YouTube")
<br />
<br /> This repository contains a Unity mobile application for iOS and Android devices called **_ShapestoLife_**. The application is an interactive experience where users are able to engage with a real photo image that will bring its message to life while looking at the image through their mobile device.
<br />
<br /> ![img-2127](https://user-images.githubusercontent.com/35173600/39190608-ec363f42-47a2-11e8-88e0-ebaca417c21e.JPG)
<br />
<br /> Please print this image (best would be paste it to a Word document and cut out to size. Size does not matter)
<br />[Print this image!](https://www.google.com/search?biw=1440&bih=724&tbm=isch&sa=1&ei=Ci7fWpjHI6OkjwTG-bDQCA&q=square+circle+triangle&oq=square+circle+&gs_l=psy-ab.3.0.0l10.29772.33141.0.33968.14.10.0.4.4.0.107.747.9j1.10.0....0...1c.1.64.psy-ab..0.14.768...0i67k1.0.A1OsWIK7YbQ#imgrc=Y9-DNLz8V8QK0M: "iLoveDesign")

## Getting Started

### Prerequisites
The software you will need to download in order to build and run the game on a mobile device:
<br /> 
<br /> • The cross-platform engine [Unity](https://unity3d.com/unity/qa/patch-releases/2017.1.0p4 "Unity 3D download") Version 2017.2.0f3.
<br />
- For iOS builds, the latest version of [Xcode.](https://developer.apple.com/download/ "Xcode 9.3 Beta")
- NOTE! You will need to have an [Apple ID](https://appleid.apple.com/account#!&page=create "Developer Account") in order to download Xcode and build for iOS.
- NOTE! Make sure to have the latest software version; 11 and up.
- For Android builds, you need [Android Studio](https://developer.android.com/studio/index.html "Android Studio download") and the [Java JDK 8.](http://www.oracle.com/technetwork/java/javase/downloads/jdk8-downloads-2133151.html "JDK download")

### Installing
To build and run a copy of this application to your mobile device:
<br />
<br /> • On the **_ShapestoLife_** repository, go to the green "Clone or download" button and click "Download Zip".
<br />
<br /> • Once the zip file has loaded onto your desktop, double click the zip file to open. Navigate to the folder Assets > ILoveDesign.unity and double click the scene to open it in Unity.
<br />
<br /> -NOTE! The scene may not be located at the top of the folder. If not, you will have to scroll through the folder to find it. It will be titled exactly ILoveDesign.unity with the Unity logo-
<br />
<br /> After opening the scene in Unity choose to build to either an iOS or Android mobile device:
<br />
1. For iOS builds:
   - Go to File > Build Settings and switch the platform to iOS (this can take a while) then click the Player Settings button below that and with this open you can change the name of the application and bundle identifier, if you would like to change them, before pressing Build and Run to then be prompted to name the build and save it. (I usually save the build to my desktop so I can delete it later) 
     - The build will open in Xcode. Make sure to check your Apple ID is correct, the bundle identifier and the name of the application is what you would like it to be then press the play button in the upper left corner and the application will build and run directly to your iOS device.
2. For Android builds:
   - First, go to the top left corner and click Unity > Preferences. Then, select External Tools in the list and add the locations of Android Studio and Java JDK 8 in the correct section.
     - Afterwards, go to File > Build Settings and switch platform to Android (this can take a while to do) then click the Player Settings button below that and you can change the name of the application and bundle identifier, if you would like to change them, before pressing Build and Run to then be prompted to name the build and save it. The application will be built right to your Android device from Unity. 

### Deployment
When building the application to your phone an important note:
<br />
<br /> • In Player Settings, you are able to not only change the name of the application and bundle identifier to whatever you would like you can also add a photo to be the icon for the application on your phone! It will be one of the first things you can do in Player Settings. Right under renaming the application.

## How to play
To play the application **_ShapestoLife_** is very simple and fun!
![img-2128](https://user-images.githubusercontent.com/35173600/39190702-21658434-47a3-11e8-8a9e-7cf6f843e4a2.png)
<br />
<br /> • After printing the image above and opening the application on your mobile device, hold the devices camera towards the printed photo. 
<br />
<br /> • The triangle, square and circle objects on the photo should become 3D objects! The triangle will rotate as the circle bounces to give them more of a fun effect for the user to be more engaged in the new look of the image.
<br />
<br /> • NOTE! The tracking only works with the image and with the shapes in the line of the camera. Please don't shake the device or get too close to the image if the images to not appear right away. Simply look for a better angle to get them to appear on your device.

# Authors
• Samantha Cayla Bajis - _Initial work_ - SamBajis

# Acknowledgments
To make **_ShapestoLife_** possible:
<br /> 
<br /> • Google Images - Provided the image used to create application objects
<br /> 
<br /> • Vuforia - AR development kit used to make the objects come to life when played on device.
<br /> 
<br /> • Blender- Created triangle, square, circle and materials using the 3D computer graphics software Blender
