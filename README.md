# WeeklyCharts
 Script to output a csv of your weekly last.fm charts

# Instructions
 1. Download the files using the green code download button (most will just want to choose download as zip)
 
 2. ~~You need to go here (https://www.last.fm/api/account/create) and get an api key.  Enter your email, Application name can be "Weekly Downloader", description can just match the description above, no callback url is needed, and you shouldn't need an Application Homepage but you can link this github if you really want to.  When you hit submit, you will be given an api key (as well as a few other things, feel free to copy them all but defintely save your api key somewhere (like in a text doc where you store this .exe).
 API Key is no longer neeeded, I set up a key specific to this program.
 
 3. Now you can run main.exe! You will be prompted for a username and start date.  Be sure to follow the formatting (YYYY.MM.DD as numbers) and no typos on your username otherwise the file will most likely crash.  If you do this correctly, the window will show you your progress of downloading the weeks you requested (for several year timeframes, there will be a lot of weeks). NEW!! You can now create your own "settings.txt" file in the same folder as this exe with your username as the first line and the date (in proper format!!!) as the second line.  For example, my settings file currently looks like this:
 IAmThBlackMetal
 2020.01.01
 
 The script will save several csvs following the format of  "*timeframe*Data.csv" in the location where main.exe is located.  There are currently Weekly, Monthly (4 weeks, there are 13 per year in this format), Quarterly (4 even sections of a year aka 13 weeks), Semester (2 even sections of a year aka 26 weeks), and Yearly (every 52 weeks).  The non-week options simply count from your start date by week so they will not necessarily match calendar dates.  The weekly charts now include human readable timeframes in the header.
 
 4. There you go, you now have a few csv options of your weekly charts! Feel free to see this flourish page for an exmaple of what you can do with this data (https://public.flourish.studio/visualisation/1486830/). For this example (**This was done before the new csv options**), I took the data.csv, converted it to an excel file and then added a new page to sum every 4 weeks into one data point for each row (aka creating monthly charts). Feel free to play around and see what you can make. You can hit "Duplicate and Edit" in the top right of my flourish page to make a copy for yourself. If you choose to simply upload the csv, you will want to add columns for 'Image' and 'Categories' if you choose to use those. Have Flourish select the range of weeks as 'Values'
