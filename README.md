# NativeScript Crypto

## Dependencies
```
 "dependencies": {
    "@types/pako": "^1.0.0",
    "nativescript-crypto": "../src",
    "nativescript-theme-core": "^1.0.4",
    "nativescript-unit-test-runner": "^0.3.4",
    "pako": "^1.0.5",
    "tns-core-modules": "^3.1.0"
  },
  "devDependencies": {
    "babel-traverse": "6.12.0",
    "babel-types": "6.11.1",
    "babylon": "6.8.4",
    "filewalker": "0.1.2",
    "jasmine-core": "^2.5.2",
    "karma": "^1.3.0",
    "karma-jasmine": "^1.0.2",
    "karma-nativescript-launcher": "^0.4.0",
    "lazy": "1.0.11",
    "nativescript-dev-typescript": "^0.5.0",
    "typescript": "^2.2.2"
  }
  ```
## Installation

Describe your plugin installation steps. Ideally it would be something like:

```javascript
tns plugin add nativescript-crypto
```

## Usage

Add `xmlns:tools="http://schemas.android.com/tools"` inside <manifest> after in AndroidManifest.xml:
```
<manifest xmlns:android="http://schemas.android.com/apk/res/android" xmlns:tools="http://schemas.android.com/tools"
	package="__PACKAGE__"
	android:versionCode="1"
	android:versionName="1.0">
```
Add `android:allowBackup="true"` and `tools:replace="android:allowBackup">` inside <application>
```
<application
		android:name="com.tns.NativeScriptApplication"
		android:allowBackup="true"
		android:icon="@drawable/icon"
		android:label="@string/app_name"
		android:theme="@style/AppTheme"
		tools:replace="android:allowBackup">
```


Fork: https://github.com/tomvardasca/nativescript-crypto
