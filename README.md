 <p align="center">
    <img width="230" src="./src/logo.png"/>
</p>
#electron-react-antdesign
Elecktron with react js

## Install 
> npm install
## Run 
> npm run dev
## Build 
>npm run build
# Package 
## For use in npm scripts
>npm install electron-packager --save-dev
## For use from cli
>npm install electron-packager -g
## MacOS
>electron-packager . --overwrite --platform=darwin --arch=x64 >--icon=assets/icons/mac/icon.icns --prune=true --out=release-builds
## Windows
>electron-packager . electron-tutorial-app --overwrite --asar=true --platform=win32 --arch=ia32 --icon=assets/icons/win/icon.ico --prune=true --out=release-builds --version-string.CompanyName=CE --version-string.FileDescription=CE --version-string.ProductName="Electron Tutorial App"
## Linux
>electron-packager . electron-tutorial-app --overwrite --asar=true --platform=linux --arch=x64 --icon=assets/icons/png/1024x1024.png --prune=true --out=release-builds