# react-native-unity-demo

This is a demo project for [react-native-unity](https://github.com/f111fei/react-native-unity-view)

## How to Build

1. Clone repo & install npm modules
```
git clone https://github.com/kimballfrank/react-native-unity-demo.git

cd react-native-unity-demo

npm install

```

2. Edit node_models/@types/react-native/index.d.ts - comment out line 8537: export type Geolocation = GeolocationStatic;

3. Open unity project `unity/Cube/Assets/test.unity` (make sure to use Unity version 2018.2.17f1)

4. Click `Build` => `Export IOS` or `Export Android`

5. Compile Typescript
```
npm run watch
```

6. React-native cli run-ios
```
npm run ios
```

## Preview

![gif](https://user-images.githubusercontent.com/7069719/37143096-12be6810-22f5-11e8-89d8-562e9213072e.gif)
