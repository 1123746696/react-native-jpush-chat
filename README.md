
# react-native-jpush-chat

## Getting started

`$ npm install react-native-jpush-chat --save`

### Mostly automatic installation

`$ react-native link react-native-jpush-chat`

### Manual installation


#### iOS

1. In XCode, in the project navigator, right click `Libraries` ➜ `Add Files to [your project's name]`
2. Go to `node_modules` ➜ `react-native-jpush-chat` and add `RNJpushChat.xcodeproj`
3. In XCode, in the project navigator, select your project. Add `libRNJpushChat.a` to your project's `Build Phases` ➜ `Link Binary With Libraries`
4. Run your project (`Cmd+R`)<

#### Android

1. Open up `android/app/src/main/java/[...]/MainActivity.java`
  - Add `import com.reactlibrary.RNJpushChatPackage;` to the imports at the top of the file
  - Add `new RNJpushChatPackage()` to the list returned by the `getPackages()` method
2. Append the following lines to `android/settings.gradle`:
  	```
  	include ':react-native-jpush-chat'
  	project(':react-native-jpush-chat').projectDir = new File(rootProject.projectDir, 	'../node_modules/react-native-jpush-chat/android')
  	```
3. Insert the following lines inside the dependencies block in `android/app/build.gradle`:
  	```
      compile project(':react-native-jpush-chat')
  	```

#### Windows
[Read it! :D](https://github.com/ReactWindows/react-native)

1. In Visual Studio add the `RNJpushChat.sln` in `node_modules/react-native-jpush-chat/windows/RNJpushChat.sln` folder to their solution, reference from their app.
2. Open up your `MainPage.cs` app
  - Add `using Com.Reactlibrary.RNJpushChat;` to the usings at the top of the file
  - Add `new RNJpushChatPackage()` to the `List<IReactPackage>` returned by the `Packages` method


## Usage
```javascript
import RNJpushChat from 'react-native-jpush-chat';

// TODO: What to do with the module?
RNJpushChat;
```
  