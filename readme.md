# Setup for a HTML scratch pad environment as an alternative for CodePen

Write quick code in `SASS`, `PUG` and `TYPESCRIPT`, see the Live Server immediately interpreting the changes and enjoy all the benefits of VSCode.

## Installtion

Just run `npm install` in root folder.

### Recommended/required extensions for VSCode:

-   Debuger for Chrome
-   Prettier
-   Live Server
-   ngrok for VSCode

## How to work with

1. Run `watch-sass`, `watch-pug` and `watch-ts` from npm-scripts
1. Run `Live Server` from VSCode (Live Server extension required)
1. Write some code to the files located in `src` folder or create your own files (but leave em in `src`)
1. If you need to debug your \*.ts files, launch `Launch Chrome against localhost` from VSCode (Debbuger for Chrome extension required)
1. Test on mobile devices through `ngrok`
1. If you ready to move on for production or something, grab your files from dist (\*.js.map not necessary)
