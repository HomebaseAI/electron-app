# electron-app
## For Homebase

This app is a meant as a standalone app for admins. It is simply a webview thrown into an electron app. 

To run this: ```npm install && npm start``` 

To package for Mac: ```npm run package-mac```  
To package for Windows: ```npm run package-win```  
To package for Linux: ```npm run package-linux```

You need to export a GitHub access token to the repo first: ```export GH_TOKE="<TOKEN>"```
If you are signing the application and have more than one Developer ID Cert on your system, follow the instructions found: https://www.electron.build/code-signing  
To publish ```npm run publish```

