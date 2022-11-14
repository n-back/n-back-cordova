# N-back-Cordova
## before

Configure [cordova environment](http://cordova.apache.org/docs/en/latest/)  
Set your [android environment](http://cordova.apache.org/docs/en/latest/guide/platforms/android/index.html) and [ios environment](http://cordova.apache.org/docs/en/latest/guide/platforms/ios/index.html)  
install  [yarn](https://yarnpkg.com/)

## build

```
git submodule update --init --recursive
yarn
cd n-back && yarn build && cd -
npx cordova platform add android ios
yarn assets
npx cordova run android
npx cordova run ios
yarn global add cordova-hot-code-push-cli # chcp.json chcp.manifest
```
