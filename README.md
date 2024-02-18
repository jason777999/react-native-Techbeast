Tech Beast
If you've arrived at this page through an external link, I want to express my gratitude first! The project actually started a while ago, mainly as a simple record of my learning journey with React Native, integrating Redux and MobX. As you can see, the project hasn't been updated for a while, and there aren't many external reasons for it. One might understand it as me shifting my focus slightly towards other aspects of life. So, as the versions update, it's uncertain whether the project can run perfectly. If you're interested, feel free to check out the source code as needed. Once again, thank you all for your support! Thanks for open source!

Note: RNProjectPlayground is a newly opened repository, mainly related to MobX and MST, also including some mixed compilation parts, focusing on navigation. The interface data is consistent with this repository. If you're interested, you can take a look. The demos directory contains some of my own practical attempts, generally unrelated to the project.

Techbeast is a display-oriented food-related app implemented based on React Native. This branch is developed for the latest native version of FoodiePie, with data sourced from Boohee. It mainly focuses on MobX practice and is not for commercial purposes. Currently, it has been adapted for both iOS and Android platforms, suitable for friends who are just starting to learn React Native. Enjoy it! 🎉🎉🎉

Screenshots
Food Encyclopedia
Explore Food
Information Detail
Food Categories
Profile

Current Features
UI construction for Food Encyclopedia, Food List, QR Code Scanning, Explore Food, Explore Food Details, My Profile, and Login screens.
Implementation of status bar color and data management based on MobX.
Adding a waiting prompt upon successful QR code scanning.
Basic usage of NetInfoDecorator, a higher-order component for network status detection.
Adding scale and color animations when switching top tab titles in Explore Food.
How to Run
shell
Copy code
$ git clone https://github.com/jason777999/react-native-Techbeast.git
$ cd react-native-Techbeast 
$ npm install
$ react-native run-ios/run-android
Related Third-Party Libraries
mobx
mobx-react
react-native-camera
react-native-easy-toast
react-native-scrollable-tab-view