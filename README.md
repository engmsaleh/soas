soas (Sample Of All Samples) - [Play Store][0]
----

With your help we can build a sample app that touches most components of the Android framework, helpful for beginners and experienced. Your pull-requested are appreciated.

[![Build Status](https://travis-ci.org/MostafaGazar/soas.svg)](https://travis-ci.org/MostafaGazar/soas)

**Here's what the project touches so far:**
- Toolbar
- Drawer (following the updated Material Design Guidelines)
- Volley (with forced caching option, it caches regardless of server response headers, Memory and Disk)
- Download images using volley (with Memory and Disk caching)
- Json (using Gson)
- ListView with a custom Adapter (based on BaseAdapter)
- SwipeToReferesh (using SwipeRefreshLayout)
- Endless Adapter (using a custom OnScrollListener)
- Fragment (ListFragment and Fragment)
- Headless Fragment (maintain data on config changed)
- Landscape, 7'' and 10'' tablets specific layouts
- Custom Views
- Palette
- Themes
- Styles
- Gradle
- Gradle product flavors
- Espresso tests
- Travis CI, Continuous Deployment

**You can help with:**
- List filter
- RTL
- More tests
- Receiver (Check [Emailer - ConnectivityReceiver.java][1])
- Service
- Loader
- CursorAdapter
- C2DM
- JNI
- HMAC
- SSL
- Bluetooth (check [iRacerController - Deployer.java][2])
- Scheduling tasks (Check [Emailer - Scheduler.java][3])
- Material Dialog (like a rate me dialog, https://github.com/afollestad/material-dialogs)
- Different buttons (http://www.google.com/design/spec/components/buttons.html)
- _Anything else you think worth adding_
- _Or email me with what you think should be added_

**Credits:**
- Your name!

###Screenshots:###
![p1](https://raw.githubusercontent.com/MostafaGazar/soas/master/screens/1.png)
![p2](https://raw.githubusercontent.com/MostafaGazar/soas/master/screens/2.png)
![p3](https://raw.githubusercontent.com/MostafaGazar/soas/master/screens/3.png)
![p4](https://raw.githubusercontent.com/MostafaGazar/soas/master/screens/4.png)
![p5](https://raw.githubusercontent.com/MostafaGazar/soas/master/screens/5.png)

**Useful materials (To start developing for native Android or update your knowledge):**
- https://developer.android.com/guide/index.html
- http://www.google.com/design/spec/material-design/introduction.html
- http://www.vogella.com/tutorials/android.html
- https://github.com/codepath/android_guides/wiki


###Notes:###
![pFragment](https://dl.dropboxusercontent.com/u/31123652/Android/android_fragment.jpg)
![pService](https://dl.dropboxusercontent.com/u/31123652/Android/android_service.jpg)
![pConcurrency](https://dl.dropboxusercontent.com/u/31123652/Android/android_concurrency.jpg)

**Developed by:**
Mostafa Gazar - eng.mostafa.gazar@gmail.com

[0]: https://play.google.com/store/apps/details?id=com.meg7.soas
[1]: https://github.com/MostafaGazar/Emailer/blob/master/src/com/meg7/emailer/receiver/ConnectivityReceiver.java
[2]: https://github.com/MostafaGazar/iRacerController/blob/master/source/src/main/java/com/meg7/controller/Deployer.java
[3]: https://github.com/MostafaGazar/Emailer/blob/master/src/com/meg7/emailer/util/Scheduler.java
