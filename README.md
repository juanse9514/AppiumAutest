# Introduction

(here goes the introducction)

## Requirements

- First you would require to install nodejs and NPM, if you don't have it please go to the following installation guide [Guide](https://phoenixnap.com/kb/install-node-js-npm-on-windows) 

## Installation

Having installed NPM and Noje.js run the following command in your terminal:

```bash
npm install -g appium
```
Please add ANDROID_HOME to your path directory

- ANDROID_HOME = C:\Users\TuNombreDeUsuario\AppData\Local\Android\Sdk

- %ANDROID_HOME%\tools

- %ANDROID_HOME%\platform-tools


After completing this step, pleaso visit the following forum so you can properly setup the android config: https://smartpossdk.gitbook.io/cloudpossdk/faq/other-development/setup-android-home
Then, please install Appium doctor which is a tool to check the configuration on the android/IOS setup

```bash
npm install -g @appium/doctor
appium-doctor --android
```
Doenload and install the following tool https://github.com/appium/appium-inspector/releases

## Initialization


