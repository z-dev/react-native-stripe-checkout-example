###Note
Follow step to solve "No bundle url present" error when run example on ios simulator:
* `rm -rf node-modules`
* `rm -rf ios/build` 
* `npm i`
* `rnpm link`
* `npm run build:ios`
* `react-native run-ios`