# electron-disclosure

This is a sample application with [github Electron](http://electron.atom.io/).

It captures your desktop by 5 minutes and posts tweet with the captured images.
(Don't worry, post tweets requires your authentication)

![capture](./capt_disclosure.png)

## Run

```sh
npm install -g electron-prebuilt bower gulp
cd electron-disclosure
npm install
npm start
```

## Watch

```sh
gulp serve
```

## Enable develop menu

Execute the following command, so you can use develop menu(Reload and Toggle dev tools) in the reneder process.

```sh
export NODE_ENV=develop
```

## Packaging

```sh
gulp package
```
