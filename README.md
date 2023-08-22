# react-native-zendesk
React Native bridge to Zendesk Support SDK v2 on iOS and Android. 

## Installation
1. Add the package via yarn or npm
```
yarn add react-native-zendesk
npm install --save react-native-zendesk
```

2. Link the modules to your native projects (VERSION < RN 0.60)
```
react-native link react-native-zendesk
```

## Getting Started
API is very small and can be seen [here](https://github.com/dcvz/react-native-zendesk/blob/master/src/index.ts)


## EXTRA STEP ANDROID
You need to add `<style name="ZendeskHelpCenterTheme" parent="ZendeskSdkTheme.Light"></style>` in your `res/values/styles.xml`