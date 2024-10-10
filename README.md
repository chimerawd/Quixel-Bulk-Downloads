# [Quixel](https://quixel.com/)-Bulk-Downloads
>Note: **There are two steps to this tutorial**

>Note: **Additional software optional for tutorial**

>Note: **F12 Opens DevTools**

## **Step one (add assets to your [libary](https://quixel.com/megascans/purchased) or [purchased](https://quixel.com/megascans/purchased) section**)

>Note: **Script for step one is not produced by me**

1. Sign into [Quixel](https://quixel.com/)
2. Go to section [home](https://quixel.com/megascans/home) in Quixel megascans
3. Open DevTools and go to the console
4. Copy code from [misiewiczradoslaw](https://gist.github.com/misiewiczradoslaw/62d045736fe06e44f16c436c6d898d26)
5. Paste script into console and let the magic happen

**Any errors check on original [github page](https://gist.github.com/misiewiczradoslaw/62d045736fe06e44f16c436c6d898d26)**

## **Step two (bulk download assets to your drive)**

>Note: **Code was testing in Edge**

>Note: **Original Script for this step was created by author Justmilomb. The following changes were introduced by me:**
>- Filename now includes the asset description and tags
>- Selects the 8K download package for each asset
>- Fixed the limiter on the maxDownloads feature
>- Added deley between cycles to mitigate rate limiting
>- Download folder is now only set in browser (or download manager if you have one)**

>Note: **The 8K process is Very slow as it needs to `click` each asset to load the link data via json, and each download package can exceed 700MB in size...so if you're downloading all 18,000 asset packages...I wish you all of the lucks.**

>Note: **An [auto scroller](https://www.softpedia.com/get/Desktop-Enhancements/Other-Desktop-Enhancements/Bahamida-Auto-Scroll.shtml#download) is recommended to quickly find new assets**

>Note: **Running the script multiple times will create duplicates because the script can only write to your drives, not read from them to check if the file is already saved.**

1. Sign into [Quixel megascans](https://quixel.com/megascans/)
2. Go to your [libary](https://quixel.com/megascans/purchased) or [purchased](https://quixel.com/megascans/purchased) section
3. Go to settings of your browser and set download location to chosen folder and do not ask
4. Download [Auto Scroll](https://www.softpedia.com/get/Desktop-Enhancements/Other-Desktop-Enhancements/Bahamida-Auto-Scroll.shtml#download) or a auto scroller of your choice.
   For best results, I found that letting the autoscroller preload the entire run helps it along. While this is not strictly neccessary, I found that after the downloads start, the 'live scroll' data can struggle to load, creating a 'no new downloads found' loop until it eventually pushes through.
5. (OPTIONAL) Start auto scroller and let it finish preloading the asset list
6. Copy code into console and press enter
7. Set desired amount of downloads
8. Start auto scroller to find new assets (not required if preload in step 5 was done)
9. Let script complete downloads
10. Come back in a month if you don't have fibre (like me) :D

## **Script**


  [BulkDownloadQuixel.txt](https://github.com/user-attachments/files/17263692/BulkDownloadQuixel.txt)
