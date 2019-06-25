# react-native-unity-demo

This is a demo project for [react-native-unity](https://github.com/f111fei/react-native-unity-view)

## How to Build

**1. Clone repo & install npm modules**
```
git clone https://github.com/kimballfrank/react-native-unity-demo.git

cd react-native-unity-demo

npm install

```

**2. Download correct version of Unity**
[Unity version 2018.2.17f1](hunityhub://2018.2.17f1/88933597c842)

**3. Open unity project `unity/Cube/Assets/test.unity`**

**4. Click `Build` => `Export IOS` or `Export Android`**

**5. Edit node_models/@types/react-native/index.d.ts**
Comment out line 8537: export type Geolocation = GeolocationStatic;

**6. Compile Typescript**
```
npm run watch
```

**6. React-native cli run-ios**
```
npm run ios
```
