# capapprouter - App
> Business Application
> CAP Node.js with standalone approuter

Tasks:
1. assign role collection to user
2. enable approuter logging
```
cf set-env capprouter-app XS_APP_LOG_LEVEL debug
cf restart capprouter-app
cf logs capprouter-app
```