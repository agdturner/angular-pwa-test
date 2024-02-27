# angular-pwa-test
Angular Service Worker Progressive Web App Test based on:
https://angular.io/guide/service-worker-getting-started

The PWA is to be available via:
https://agdturner.github.com/angular-pwa-test/

Steps taken
1. Initialised repository with code from:
https://angular.io/guide/service-worker-getting-started
3. Install node packages
`npm install`
4. Setup to use service worker
`ng add @angular/pwa`
5. Edit angular.json to change the lines:
```
            "serviceWorker": true,
            "ngswConfigPath": "ngsw-config.json"
```
To:
```
            "serviceWorker": "ngsw-config.json"
```
5. Build the app for production; code is in the /dist folder:
`ng build`
6. Serve application in production mode:
`ng serve --configuration production`
