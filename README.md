# Syncboard - sync your clipboards between your Android and Windows PC

You can find more at: https://syncy.herokuapp.com

```Android``` contains source code for the Syncboard Android App. Open it with Android Studio and Build the APK file yourself.


```PC``` contains source code for the system tray app for Windows, to use this, install all the requirements using ```pip install -r requirements.txt``` and run the following command ```python syncboard.py```.


You can hide the console window by renaming ```syncboard.py``` to ```syncboard.pyw```.


```Server``` contains the source code for the NodeJS, to use this, use these commands ```cd Server``` then ```npm start```



## Usage:

First register on https://syncy.herokuapp.com/register, it will give an ```API key``` for your account.


Now, install the Syncboard Android App, paste your API key and hit the save button. You don't have to do it again, unless you want to change your API key. Instructions are available on the Android App. You can download the app from [Releases](https://github.com/jaychandra6/syncboard/releases/tag/0.1)


Install Python 3.8 on your PC and run the following command ```pip install -r requirements.txt``` then add your ```API key``` to ```key.json``` file and run ```python syncboard.py```. It will start a system tray app on your Windows PC, Linux port is coming soon. You can right click and get the synced clipboard data or sync new data.


Copy something and hit ```UPDATE``` button on Android or PC to sync data on to Database. Hit the ```GET``` button and it will automatically copies the synced data on to your device's clipboard. It will only do it, when you tell it to.


## Screenshots

#### Website

![img file](https://github.com/jaychandra6/syncboard/blob/main/screenshot.PNG)

#### Android App

![img file](https://github.com/jaychandra6/syncboard/blob/main/android_screenshot.jpg)

#### PC System Tray Icon
![img file](https://github.com/jaychandra6/syncboard/blob/main/pc_screenshot.PNG)
