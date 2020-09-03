# WeeklyCharts
 Script to output a csv of your weekly last.fm charts

# Instructions
Download the git files (most can just click download as zip)
 1. You need to go here (https://www.last.fm/api/account/create) and get an api key.  Enter your email, Application name can be "Weekly Downloader", description can just match the description above, no callback url is needed, and you shouldn't need an Application Homepage but you can link this github if you really want to.  When you hit submit, you will be given an api key (as well as a few other things, feel free to copy them all but defintely save your api key somewhere (like in a text doc where you store this .exe).
 2. Now you can run main.exe! You will be prompted for a username, api key, start date and end date.  Be sure to follow the formatting and no typos on your username otherwise the file will most likely crash.  If you do this correctly, the window will show you your progress of downloading the weeks you requested (for several year timeframes, there will be a lot of weeks).  The script will save a csv called "data.csv" in the location where main.exe is located.
 3. There you go, you now have a csv of your weekly charts! Feel free to see this flourish page for an exmaple of what you can do with this data (https://public.flourish.studio/visualisation/1486830/). For this example, I took the data.csv, converted it to an excel file and then added a new page to sum every 4 weeks into one data point for each row (aka creating monthly charts). Feel free to play around and see what you can make. You can hit "Duplicate and Edit" in the top right of my flourish page to make a copy for yourself.
