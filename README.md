# WingBuddy Parse Dashboard

This dashboard dis available at https://wingbuddy-dashboard.herokuapp.com.

If you want to request access, please contact Julian Vogels via julian@music-tech.de.

## Running the dashboard locally

The Dashboard can also be launched locally using `heroku local` (See https://devcenter.heroku.com/articles/heroku-local). The application will however not succeed launching without having set up environment variables correcty.

In a local `.env` file, add the following secrets:

PARSE_DASHBOARD_CONFIG='{"apps":[{"serverURL":"https://wingbuddy.herokuapp.com/parse","graphQLServerURL":"https://wingbuddy.herokuapp.com/parse","appId":"myAppId","masterKey":"myMasterKey","appName":"WingBuddy","iconName":"icon.png","production":false,"primaryBackgroundColor":"#00c2a3","secondaryBackgroundColor":"#1a1a1a"}],"iconsFolder":"icons","users":[{"user":"yourUserName","pass":"yourBCryptHash"}],"useEncryptedPasswords":true}'