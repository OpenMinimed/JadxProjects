# jadx projects

This is a brief overview of Java apps reversed using [jadx](https://github.com/skylot/jadx), a decompiler for Android DEX and APK.

This repository does not contain the actual apps, only the jadx project files. You can download the APKs either from your Android phone (if you already installed the app) or from sites such as [APKpure](https://apkpure.com/). Use the information below to get the correct version. Download the CareLink Uploader from Medtronic through their CareLink website.

Before loading the projects in jadx, open the .jadx file in a text editor and fix the path in the `files` entry to point to the .apk or .jar file on your disk.


Unless noted otherwise, the .jadx project files were created using jadx 1.5.3.


## CareLink Uploader

A Windows desktop app that lets you upload pump data to CareLink. It is usually used together with a _Blue Adapter_ that handles the local Blueooth LE connection to the pump.

### uploader.jar.jadx

- CareLinkUploader-ACC-7350-3.13.0-windows-installer.exe
- sha256sum of the .jar: fc82272146e165b52a54c2bd51758a01d3478da4278f48a2d63e4b8a17deffe8


## Guardian mobile app

This app connects to a **Guardian 4** transmitter, displays and stores the glucose data, also supporting alerts. It can upload the data to CareLink.

### Guardian_134.jadx

- v1.3.4
- sha256sum of the .apk: ae9013f8ab22daca81dfc95eb2c44e93a7f8696e2ad3141fe2b359048ee511f8


## MiniMed Mobile app

This app connects to a 700-series pump (e.g. 780G) and can act as its secondary display. It can upload the data to CareLink. The app is released as separate versions for US and EU.

### MiniMed_Mobile_220_original.apk.jadx

- v2.2.0 (EU version)
- sha256sum of the .apk: 437556f9e562073293ace335468cc35a1a9c0e1cae79be58de5a3bf716511e2d

### mmm_250.apk.jadx

- v2.5.0 (EU version)
- sha256sum of the .apk: 7192079be349ef50a07803133b0ad1bf5b1f37f83f97e4a1926d594a20dfeb69
