# AngularNativescript

## In order to use the application, ensure that you have the following dependencies met:

1) Angular CLI v6+
2) NativeScript CLI v6+
3) NativeScript Schematics
4) Node.JS v10+
5) xCode or Android Studio (for emulator and building)
6) Optional - Genymotion

Additional Nativescript Instructions can be found [here](https://docs.nativescript.org/angular/code-sharing/migrating-a-web-project)

## Run the App

1) In the command line, open the directory `AngularNativeScript`, and run `npm install`.
2) After the dependencies are installed, run `tns run ios --bundle` for iOS or `tns run android --bundle` for Android
3) To run the web app version, run `ng serve -o` to launch the app. It will be running on `localhost:4200`.

Note - The apps do not share data. They are two separate instances of the same application.