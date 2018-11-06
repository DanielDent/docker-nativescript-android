# nativescript-android

This repository includes the NativeScript CLI along with the Android SDK with the following toolchain versions:

* NodeJS 10
* Java 8
* NativeScript 4.2
* Android SDK tools for API Level 27 (build tools 27.0.3)

# Running

`docker run -it --rm -v $(pwd):/app tiagomelo/nativescript-android bash -C "cd /app && tns build android"`
