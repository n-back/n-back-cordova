# N-back-Cordova
## before

Configure [cordova environment](http://cordova.apache.org/docs/en/latest/)  
Set your [android environment](http://cordova.apache.org/docs/en/latest/guide/platforms/android/index.html) and [ios environment](http://cordova.apache.org/docs/en/latest/guide/platforms/ios/index.html)  
install  [yarn](https://yarnpkg.com/)

## build

```
git submodule update --init --recursive
yarn
yarn build
cordova platform add android ios
yarn assets
cordova run android
cordova run ios
```
