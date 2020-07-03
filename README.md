# reactjs_ionic-capacitor_mobilapp
If you have a reactJs web application, you can get output as a cross-platform mobile app with use this method(ionic  capacitor).
It is faster and more dynamic rather than Apache Cordova(PhoneGap).

There a lot of way to using ionic capacitor in your current react project. Thi is just one of all :).


After your installation about ReactJS project; you have to do install ionic and android platform.


## Differences Adding Files:

1: You should create two json files for configuration, as you can see this project in the home folder.(capacitor.config.json and ionic.config.json)


2: And You have to write as written this files but also you can change "AppName" that what do you want.


3: Finally you can pass the installation steps.

## Installation about ionic and their platforms

1 : You have to build you project with npm                     :     npm run build 


2 : Installation of Ionic  for this project and global         :     npm install -g @ionic/cli


3:  Instalation Capacitor is that cross-platform app runtime   :     npm install @capacitor/core --save


4: Add android platform in your project with all dependencies  :     ionic capacitor add android


5: Finally, Your android app is ready and code to run app      :     npx cap open android

## References :

https://ionicframework.com/

https://capacitorjs.com/
