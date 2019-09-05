
# react-native-wx-nopay

## Getting started

`$ npm install react-native-wx-nopay --save`

### Mostly automatic installation

`$ react-native link react-native-wx-nopay`

### Manual installation


#### iOS

1. In XCode, in the project navigator, right click `Libraries` ➜ `Add Files to [your project's name]`
2. Go to `node_modules` ➜ `react-native-wx-nopay` and add `RNWxNopay.xcodeproj`
3. In XCode, in the project navigator, select your project. Add `libRNWxNopay.a` to your project's `Build Phases` ➜ `Link Binary With Libraries`
4. Run your project (`Cmd+R`)<

#### Android

1. Open up `android/app/src/main/java/[...]/MainActivity.java`
  - Add `import com.wx.nopay.RNWxNopayPackage;` to the imports at the top of the file
  - Add `new RNWxNopayPackage()` to the list returned by the `getPackages()` method
2. Append the following lines to `android/settings.gradle`:
  	```
  	include ':react-native-wx-nopay'
  	project(':react-native-wx-nopay').projectDir = new File(rootProject.projectDir, 	'../node_modules/react-native-wx-nopay/android')
  	```
3. Insert the following lines inside the dependencies block in `android/app/build.gradle`:
  	```
      compile project(':react-native-wx-nopay')
  	```


## Usage
```javascript
import RNWxNopay from 'react-native-wx-nopay';

// TODO: What to do with the module?
RNWxNopay;
```
  