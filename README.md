# newsApp Mobile

newsApp Mobile is built using TypeScript, Redux, LinguiJS, and React/React Native.
It uses Metro, the JavaScript bundler for React Native to join the code and all its dependencies together.


## Setup

This project uses React Native. For first time set up, inside the `/newsApp` folder, run:

 ```bash
 npm install && npm start
 ```

To start project run the below. You will additionally need a device (real or virtual), and run either the Android or iOS commands below to view the app. Note you will also need an Apple device to do iOS testing and deployment.

To generate and run Android:

```bash
npm run android
```

To generate and run iOS:

```bash
npm run ios
```

## Translations

We are using linguiJS for translation <https://lingui.js.org/>

Follow documentation on how to wrap strings so they get picked up then run:

```bash
# update catalog
npm run extract
# update translations
npm run compile # then refresh environment

To extract the strings into a PO file under /locales.
```




