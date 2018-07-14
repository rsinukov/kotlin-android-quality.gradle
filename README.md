# kotlin-android-quality.gradle
Copy-paste gradle file with tasks for checking quality of android+kotlin projects

## Uses inside
* ktLint
* detekt
* lint

## Usage
I am to lazy to create plugin for it. 
1. copy this file to root folder of you project
2. add `apply from: '../quality.gradle` to your `build.gradle` 
3. run `./gradlew check`