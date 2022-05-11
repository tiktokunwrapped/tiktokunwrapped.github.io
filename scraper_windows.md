## Data Scraping Tool - PC

To scrape your own TikTok history and do some sensemaking activities of your own, download the relevant app above on your computer and follow the associated instructions.

### 1. Opening the app

The link about should download a ".app" file to your computer. Right click it and press "Open" to run. A warning should pop up about an unverified developer; this appears when Apple has not taken a look at the app themselves and published it. Click "allow anyways" to continue. It might take a few seconds for the app to load; try again if nothing has happened after 10 seconds.


### 2. Selecting the file

Select the "user_data.json" app that you saved from earlier. If you select the right file, it should display a date range below, from older date to most recent date, as well as a count of how many videos are stored in your watch history. It might be a lot of files!

### 3. Entering a date range

There will be two boxes for you to enter a date in the MM/DD/YY format (M/D/YY works as well). The top date should be older, and the bottom date should be newer. This will allow you to select a "range" of videos to get information for. Be conservative at first - everyone's internet provider is different, and some might not take kindly to you scraping tens of thousands of videos at once.

### 4. Scraping the videos

Click the "scrape videos" button and start downloading videos! Check up on your progress beneath. 

By design, the app will download information for each video *only once*. Every time you try to download information about it again, the app will check to see if you've already saved the information, and if so, will just access the existing saved copy. This allows you to run the app for a while, close it, and come back to it any time - the information you've already saved will still be there.

Some videos will not be scrapable because they have been removed/no longer exist, or have been made private. Likewise, if your internet service provider or TikTok decides to block you, the tool will let you know that it is continually running into such errors.

### 5. Seeing results

Once finished, the results will be saved in the same directory your "user_data.json" file was in. It should look like this:

You can open it with any spreadsheet application such as Microsoft Excel.

*For those interested in running their own analysis:* this apps scrapes *all* available data associated with each video and stores it in the directory where your "user_data.json" file was stored. You can use these files for your own analysis purposes to build data visualizations, machine learning models, other analyses, etc.



