## Welcome to the TikTok Unwrapped Toolkit!

This is a digital toolkit allowing you to download your TikTok data and make your history with the algorithm more legible and accessible to you. Links below are provided to:

1. Download your TikTok data from the app
2. Anonymize it and retrieve only the relevant portions
3. Scrape your TikTok view history for relevant information


<br/><br/>


### TikTok Data Download

The first step is to request your data from TikTok in a "JSON" format. You can find instructions below. While you don't have to do much, it may take a few days to complete on TikTok's end. Once you click the download button, you will receive a .zip file that downloads to your phone.

[Request your data from TikTok with this guide:](https://docs.google.com/document/d/1ECqOR897-Li5zjiRZcplgkJG86nhst0Isra2h3DxeJE/edit?usp=sharing)


<br/><br/>


### Extracting View History

Now that your TikTok data has been downloaded, you have to extract the relevant portions. You should simply drag the .zip file into our tool, linked below! You can do this on your phone or your computer.

If you're technically inclined, you can do this on your own by unzipping your file and extracting the relevant item from your JSON file. 

(note to Windows users): TikTok provides its data in a format that, surprisingly, *cannot be unzipped correctly on any Windows computer*. We encourage you to just drop the zip file directly into our tool, which can handle that for you.

[Uee this tool to extract your view history from your data](https://tiktokunwrapped.github.io/anonymizer)

<br/><br/>



### Retrieve Relevant Information

Now, you should have a "user_data.json" file containing some data. It should look something like this:

```
{
    "VideoList": [
        {
            "Date": "2022-04-20 23:17:46",
            "VideoLink": "https://www.tiktokv.com/share/video/###########/"
        },
        {
            "Date": "2022-04-20 16:35:40",
            "VideoLink": "https://www.tiktokv.com/share/video/###########/"
        },
        [... list of videos continues...]
        {
            "Date": "2022-04-20 16:35:29",
            "VideoLink": "https://www.tiktokv.com/share/video/###########/"
        },
    ]
}
```

Once you're here, you should send the "user_data.json" file to your computer. Once it's there, you can check out the following guides to retrieve relevant information from your watch history!

[Guide for Mac users](https://tiktokunwrapped.github.io/scraper_mac.html)

[Guide for Windows users](https://tiktokunwrapped.github.io/scraper_windows.html)


<br/><br/>


## Thanks for Unwrapping with us!

Find anything interesting? Have any suggestions? Email us at tiktokunwrapped@gmail.com for any inquiries!

Are you a programmer yourself who would like to build on the code or simply find out how this works?

Check out the code for these associated tools at [our github](https://github.com/tiktokunwrapped/). It's all open source!

Have any ideas for data visualizations or summarization tools? We've explored approaches with data visualization and machine learning. Check out some of this existing work [here](https://ochan1.github.io/info247-sp22-tiktok-unwrapped/dist/)


