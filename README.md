# Electron iframe resize example

This project is an example project that we can toggle the width of an iframe in an electron container.
This also proves that the content of the iframe can be designed in a responsive way. 

## Get started 

```bash 
# clone the repo 
git clone https://github.com/samvloeberghs/electron-iframe-resize-example.git
 
# change directory to our repo 
cd electron-iframe-resize-example
 
# install the repo with npm 
npm install
 
# start the app
electron .
```

## Packaging the app

To package the app and run it as an exe you first need to install the packager globally.

```bash 
# install packager
npm install electron-packager -g
 
# start packaging
npm run package
```