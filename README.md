# IoT for Insurance Mobile Application

## Overview
IoT4I establishes a link between internet-of-things devices, insurance companies and insurance holders. The IBM IoT4I Mobile application is a reference 
implementation for a mobile client of the IoT4I Solution. The application allows registering new devices in the system and receiving alerts for these devices

## Prerequisites
 Required:
  - An [IBM Bluemix account](https://console.ng.bluemix.net/). A 30 day trial account is free.
  - The IoT for Insurance service deployed in Bluemix.
  - Apple XCode 7.3 or higher integrated development environment.
  - An iOS 9.0 or higher iPhone mobile device.
  - CocoaPods installed on your computer. See the [CocoaPods website](https://guides.cocoapods.org/using/getting-started.html).

## Try it
To try the mobile app, perform the following tasks:

1. Download the source code for the mobile app onto a computer on which Xcode 7.3 or above is installed.
2. Run a CocoaPods pod install on your project.
3. Connect your iPhone to a computer on which Xcode installed.
4. Double click on the `IoT4I.xcworkspace` file to open the project in Xcode.
5. If you have not already done so, on the Xcode menu, select **Preferences** and sign in with your Apple ID.
6. Select your mobile device as a build destination.
7. Select the 'IoT4I' file in the list of files to display the Identity dialog.
8. In the Identity dialog
  - Change the **Bundle Identifier** to a unique identifier. For example, "myIoT4Ibundle".
  - Set **Team** to your personal team name and then click **Fix Issue**.
9. Click the arrow to "build and run the current scheme". An error is displayed that says "Could not launch "IoT4I" because you have not yet verified that your Developer App certificate is trusted on your device.
10. On your mobile device, select yourself as a Trusted Developer, as follows:  
    1. On your phone, go to **Settings > General > Device Management > yourDeveloperID**.
    2. Trust your own developer ID.
    3. When prompted, confirm **Trust**.
11. On your computer, click the arrow to build and run the current scheme. The mobile application is installed on your phone. For more information, see the [Apple developer instructions for running Apps on devices from Xcode](https://developer.apple.com/library/mac/documentation/IDEs/Conceptual/AppDistributionGuide/LaunchingYourApponDevices/LaunchingYourApponDevices.html).


## Related links
- [IBM Watson IoT](https://internetofthings.ibmcloud.com)
