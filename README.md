# QR and Bar code reader with ZXing ("Zebra Crossing")

barcodereader-melvincabatuan created by Classroom for GitHub

This project illustrates QR and Bar code reading in your Android project.

## Keypoint:

* Add ZXing dependency in 'build.gradle'

```gradle
  compile 'com.journeyapps:zxing-android-embedded:3.0.3@aar'
  compile 'com.google.zxing:core:3.2.0'
```

Ex. My 'build.gradle':

```gradle
apply plugin: 'com.android.application'

android {
    compileSdkVersion 22
    buildToolsVersion "22.0.1"

    defaultConfig {
        applicationId "ph.edu.dlsu.barcodescandemo"
        minSdkVersion 15
        targetSdkVersion 22
        versionCode 1
        versionName "1.0"
    }
    buildTypes {
        release {
            minifyEnabled false
            proguardFiles getDefaultProguardFile('proguard-android.txt'), 'proguard-rules.pro'
        }
    }
}

dependencies {
    compile fileTree(dir: 'libs', include: ['*.jar'])
    testCompile 'junit:junit:4.12'
    compile 'com.android.support:appcompat-v7:22.2.1'

  // added by mkc for ZXing
    compile 'com.journeyapps:zxing-android-embedded:3.0.3@aar'
    compile 'com.google.zxing:core:3.2.0'
}
```

Refer to the following project for more information:

* https://github.com/journeyapps/zxing-android-embedded 
 

## Accept

To accept the assignment, click the following URL:

https://classroom.github.com/assignment-invitations/18e4985f71a1fe826ca9fb05b958a7f8

## Sample Solution:

https://github.com/DeLaSalleUniversity-Manila/barcodereader-melvincabatuan

## Submission Procedure with Git: 

```shell
$ cd /path/to/your/android/app/
$ git init
$ git add –all
$ git commit -m "your message, e.x. Assignment 1 submission"
$ git remote add origin <Assignment link copied from assignment github, e.x. https://github.com/DeLaSalleUniversity-Manila/secondactivityassignment-melvincabatuan.git>
$ git push -u origin master
<then Enter Username and Password>
```


## Screenshots:


![alt tag](https://github.com/DeLaSalleUniversity-Manila/barcodereader-melvincabatuan/blob/master/device-2015-11-08-043120.png)

![alt tag](https://github.com/DeLaSalleUniversity-Manila/barcodereader-melvincabatuan/blob/master/device-2015-11-08-043330.png)

![alt tag](https://github.com/DeLaSalleUniversity-Manila/barcodereader-melvincabatuan/blob/master/device-2015-11-08-043540.png)

![alt tag](https://github.com/DeLaSalleUniversity-Manila/barcodereader-melvincabatuan/blob/master/device-2015-11-08-043842.png)

![alt tag](https://github.com/DeLaSalleUniversity-Manila/barcodereader-melvincabatuan/blob/master/device-2015-11-08-044347.png)

![alt tag](https://github.com/DeLaSalleUniversity-Manila/barcodereader-melvincabatuan/blob/master/device-2015-11-08-044431.png)

![alt tag](https://github.com/DeLaSalleUniversity-Manila/barcodereader-melvincabatuan/blob/master/device-2015-11-08-044455.png)

![alt tag](https://github.com/DeLaSalleUniversity-Manila/barcodereader-melvincabatuan/blob/master/device-2015-11-08-044600.png)

![alt tag](https://github.com/DeLaSalleUniversity-Manila/barcodereader-melvincabatuan/blob/master/device-2015-11-08-045439.png)

![alt tag](https://github.com/DeLaSalleUniversity-Manila/barcodereader-melvincabatuan/blob/master/device-2015-11-08-045525.png)

![alt tag](https://github.com/DeLaSalleUniversity-Manila/barcodereader-melvincabatuan/blob/master/device-2015-11-08-045634.png)

![alt tag](https://github.com/DeLaSalleUniversity-Manila/barcodereader-melvincabatuan/blob/master/device-2015-11-08-045719.png) 


"*Most software today is very much like an Egyptian pyramid with millions of bricks piled on top of each other, with no structural integrity, but just done by brute force and thousands of slaves.*" - Alan Curtis Kay (American computer scientist)
