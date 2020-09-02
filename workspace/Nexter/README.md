
For Production build -
1. Comment out below code from index.html because this is already present in the compressed style.css file for production build.
   <link rel="stylesheet" href="css/icon-font.css"> 
2. Run this command. 
   npm run build:css



For Development workflow - 
1. Add below code in index.html <head> element.
   <link rel="stylesheet" href="css/icon-font.css">
2. Run below command and start working, your changes should automatically be reflected on the browser.
   npm run start

   For 'start' script, we don't have to write 'run', we can simply run as 
   npm start

   Please Note - For live-server we have added option as --browser=firefox, so that it will always open our webpage in Firefox (default is Chrome). That is because Firefox has pretty good DevTools options for CSS Grid.

