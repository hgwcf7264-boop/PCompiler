## About Patch
Patch is supported in APK Editor Pro since version 1.6.0. In general, it is a zip file, which contains patch.txt and other necessary files. Patch.txt inside the zip file specifies patch rules, and other files provide patch resources.
It is not mature yet, please be careful when combining with other modifications.

**Patch Format**
A patch is mainly composed of patch rules. Currently, it supports 8 patch rules:
 - `ADD_FILES`
 - `REMOVE_FILES`
 - `MATCH_REPLACE`
 - `MATCH_ASSIGN`
 - `MATCH_GOTO`
 - `GOTO`
 - `MERGE`
 - `EXECUTE_DEX`
 - `DUMMY`

Inside a rule, each line starts with ‘#’ means that is a comment line. And, each configuration starts in a new line.

## Building
This project uses:

 1. JDK 11
 2. Kotlin 1.7.
 3. AndroidX Jetpack libs 1.6
 4. Gradle 7.2.2
 
 Use Android Studio Arctic Fox (or newer). Build this with `Build -> Build APK`
 ## About
 

> Copyright (c) 2017-2022 Snow Volf (Artem Zhiganov)
> Licenced under the Apache Licence, version 2.0

