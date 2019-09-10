# Phase Mobile

## Developer Environment

A react-native environment is required.
Please follow the [offcial instructions](https://facebook.github.io/react-native/docs/getting-started) to get it ready.

```sh
# Install dependencies.
yarn install
```

For Android:

```sh
# If you don't have a debug.keystore, you need to generate one.
cd android/app && keytool -genkey -v -keystore "debug.keystore" -storepass "android" -alias "androiddebugkey" -keypass "android" -keyalg "RSA" -keysize 2048 -validity 100000
```
