# OneSignal SDK Web

This repo is to test the OneSignal SDK Web in a local environment.

1. Install [http-server](https://www.npmjs.com/package/http-server).
2. Check the latest guide from [OneSignal](https://documentation.onesignal.com/docs/web-sdk-setup).
3. Signup and create a new app. Copy the `App ID`, duplicate `config.example.js` to `config.js`, and set `APP_CONFIG.ONESIGNAL_APP_ID` there. `config.js` is gitignored.
4. Run `http-server` to serve the files.
5. Open the browser and navigate to `http://localhost:8080`.
6. Allow the notification permission.
7. Go back to the dashboard of OneSignal and check the subscribers.
