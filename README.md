# Android Apps Scraper

I did a research project on comparison of Official Play Store Apps and their 3rd Party App Stores counterparts to analyze what modifications are done to the 3rd Party versions of an app. For this purpose, I wrote this script to download pairs of an app from Google Play Store and Xiaomi App Store (a famous 3rd Party Chinese App Store). It downloads an app from Xiaomi and Google Play store only when that app is available on both stores. This way it creates a dataset of pairs of an app.

I am open-sourcing this tool so that it can be utilized by the research community for research in Android Security. 

Moroever, to compare two Android Apps I wrote another tool named [AndroCompare](https://github.com/harismuneer/AndroCompare). I have open-sourced it as well.

## Approach
The download URL of an app on Xiaomi App Store is like http://app.mi.com/download/23 
The number at the end of the URL can be incremented to download as many apps as you want. So, theoretically you can download each and every app on the Xiaomi App Store.

## Features
* download all apps from the famous Xiaomi App Store
* download pairs of an app from Play Store and Xiaomi App Store
* the record of all downloaded apps is maintained in a SQLite database
* if the code is interrupted using CTRL + Z then the current progress is saved so that next time the code resumes downloading from where it left previously
* incase the script is running and there occurs some internet connectivity issue then all current progress is saved and the script waits until the internet is connected again and resumes from where it left
