# Trackr Chrome Extension
Trackr is a Chrome extension that allows a user to keep track of all of their time spent across the web and view statistics aesthetically.

## Technologies
### Frontend
* React.js
* Chart.js
* jQuery
* Chrome API

### Backend
* NodeJS
* MongoDB
* Express

## Using the extension
1. Clone the repo and navigate to the client folder via `cd client`
2. `npm install` the dependencies
3. Build the extension with `npm run build`
4. Go into your Chrome browser and go to chrome://extensions
5. Toggle on developer mode, and press Load Unpacked
6. When prompted for a file, upload the *build* folder in the client folder
7. Open a new tab and click on the dog extension icon and choose a username in the popup
8. After connecting, begin browsing chrome and every time you open a new tab, you'll be able to see your statistics!

## Feature Overview
- View top 10 daily, weekly, and all time site browsing times on the Dashboard tab
![dashboard1](https://user-images.githubusercontent.com/29217753/70882076-6d1cc400-1f83-11ea-8584-54d42f13c999.png)
![dashboard2](https://user-images.githubusercontent.com/29217753/70882075-6d1cc400-1f83-11ea-8665-b4e392a0859a.png)
![dashboard3](https://user-images.githubusercontent.com/29217753/70882074-6d1cc400-1f83-11ea-9cac-9d0d3658f16d.png)
  - Allows user to past days usage by scrolling through day by day, or week by week depending on the current tab
  ![scroll](https://user-images.githubusercontent.com/29217753/70882263-eb796600-1f83-11ea-9682-f08d9fc0cab6.png)
- View complete history of browsing times in History tab sorted by day
![history](https://user-images.githubusercontent.com/29217753/70881963-1b743980-1f83-11ea-9b32-748e376172e7.png)
- View daily usage comparison in Insights tab
