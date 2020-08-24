
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

