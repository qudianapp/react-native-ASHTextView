
# react-native-fix-text-vie-w

## Getting started

`$ npm install react-native-fix-text-vie-w --save`

### Mostly automatic installation

`$ react-native link react-native-fix-text-vie-w`

### Manual installation


#### iOS

1. In XCode, in the project navigator, right click `Libraries` ➜ `Add Files to [your project's name]`
2. Go to `node_modules` ➜ `react-native-fix-text-vie-w` and add `RNFixTextVieW.xcodeproj`
3. In XCode, in the project navigator, select your project. Add `libRNFixTextVieW.a` to your project's `Build Phases` ➜ `Link Binary With Libraries`
4. Run your project (`Cmd+R`)<

#### Android

1. Open up `android/app/src/main/java/[...]/MainActivity.java`
  - Add `import com.qudian.FixTextView.RNFixTextVieWPackage;` to the imports at the top of the file
  - Add `new RNFixTextVieWPackage()` to the list returned by the `getPackages()` method
2. Append the following lines to `android/settings.gradle`:
  	```
  	include ':react-native-fix-text-vie-w'
  	project(':react-native-fix-text-vie-w').projectDir = new File(rootProject.projectDir, 	'../node_modules/react-native-fix-text-vie-w/android')
  	```
3. Insert the following lines inside the dependencies block in `android/app/build.gradle`:
  	```
      compile project(':react-native-fix-text-vie-w')
  	```


## Usage
```javascript
import RNFixTextVieW from 'react-native-fix-text-vie-w';

// TODO: What to do with the module?
RNFixTextVieW;
```
  