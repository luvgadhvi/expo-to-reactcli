# Expo to React CLI.
This project will show how to migrate an existing expo tool in React CLI project.

 ## Steps
Following are the steps involved for migrate the project.
* **Step 1**<br/>
Run following command to create react native cli project ```react-native init <project-name>```
* **Step 2**<br/>
Copy following files src, App.js and package.json from expo and paste it in react native project and run following command  ```npm i```.
* **Step 3**<br/>
After npm installation run following commoand to run the application ```react-native run-android ``` or ```react-native run-ios``` .

## Android Setup 
Following are the steps involved for setting up the android projject.
* **Step 1**<br/>
In andriod/build.gradle file add following line ``` apply from: "../../node_modules/react-native-vector-icons/fonts.gradle" ```.This is to setup reurired if react-native-vector-icons is being used. 
* **Step 2**<br/>
Create local.properties file in android Folder and put following line
```sdk.dir = /Users/<userDir>/Library/Android/sdk```.
