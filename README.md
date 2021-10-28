# Introduction

Hello there! This project was created to assist us in the recruitment process by allowing you to showcase how you work in typical day to day scenario. It consists of the toy project and a set of quests we would like you to solve.

We've used [Jetpack Compose](https://developer.android.com/jetpack/compose) to build UI layer in this project because it's our framework of choise for the future projects.

# Setup
You would need [Android Studio](https://developer.android.com/studio) and [Github](https://github.com/signup) account. 

Click on [Use this template](https://docs.github.com/en/repositories/creating-and-managing-repositories/creating-a-repository-from-a-template) button for create repository copy (please do not fork it :ghost:)

# :boat: Quests
## 1. Fit the Locals
Compose provides special mechanism to propagate objects across composable functions called `CompositionLocal`. Main screen uses `SystemUiController` which is not currently provided. This triggers application crash in runtime. Your task is to find most appropriate place to provide this object.
