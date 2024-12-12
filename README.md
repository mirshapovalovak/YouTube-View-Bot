# 🚀 YouTube Booster 5.0 - YouTube Views Bot
YouTube Booster is a tool designed to promote your YouTube channel, helping you increase views, engagement, and audience growth.

By simulating views, likes, subscriptions, and comments, it enhances your channel’s metrics and encourages YouTube to recommend and rank your videos more favorably. This creates the appearance of strong audience engagement.

With YouTube Booster, you can scale your view counts as much as you need, customize view retention, and fine-tune every detail—from the probability of likes to the number of rewinds—tailoring the experience to your exact promotional goals.

## 🔗 More info: https://youtube-booster.space 🔗
## 📺 Demo video: https://www.youtube.com/watch?v=xOZqAb5a7Fs 📺

![image](https://github.com/user-attachments/assets/0955f7e8-a86e-445c-a5e7-0a8b6a070a1b)

# Table of Contents

- [💣 Features](#-features)
- [🎯 How View Bot Works?](#-how-view-bot-works)
- [🧑‍💻 Installation](#-installation)
  * [✅ Stage 1: Profile generation](#-stage-1-profile-generation)
  * [✅ Stage 2: Warm Up of Profiles](#-stage-2-warm-up-of-profiles)
  * [✅ Stage 3: Video Boost](#-stage-3-video-boost)
  * [Advanced Settings (DO NOT MAKE CHANGES UNLESS SURE)](#advanced-settings-do-not-make-changes-unless-sure)
- [⚙️ System Requirements](#%EF%B8%8F-system-requirements)
- [❓ FAQ](#-faq)
- [🔗 Useful links](#-useful-links)
- [🗒️ Notes](#%EF%B8%8F-notes)

# 💣 Features

 - Views increase.
 - Ability to boost videos via playlists.
 - Likes increase.
 - Dislikes increase
 - Subscribers increase.
 - Comments increase.
 - Enabling channel notifications.
 - Watching/skipping ads.
 - Monetization (AdSense) clicking.
 - Pre-start warm up (Warming up profiles before watching a targeted video).
 - Ability to rewind the first seconds of a video.
 - Smart video rewinds.
 - Ability to set watch time.
 - Emulating different traffic sources: suggestions, YouTube search, Google search, YouTube homepage, notifications, channel page, direct visits, and from other sites.
 - Support filters in YouTube search.
 - Profiles generator (script included).
 - Warm-up (farming) of profiles and accounts (script included).
 - Multithreading (unlimited threads).
 - Proxy support (http/socks/IPv4/IPv6): Static, Residential (Static and Rotating), Mobile (IP rotating by interval or API).
 - Anonymity and browser authenticity. The software has increased anonymity and leak protection. Some standard BAS functions have been redesigned to ensure maximum security to exclude view drops and bans).
 - Highest emulation of human behavior. The view bot can do smart rewinds (if necessary), move the mouse over the progress bar, read descriptions, and comments, sometimes open suggested videos, copy a link, enable pause, highlight text on a page, and much more. In general, everything is like an ordinary user does.
 - Ability to pass PVA when logging into a Google account.
 - Solving captcha in Google.
 - Support of accounts with 2fa.
 - Scheduler.
 - Ability to set different settings for individual videos.
 - The ability to increase views without Google accounts.

# 🎯 How View Bot Works?

This bot operates by simulating user engagement on your YouTube video. It automatically send views through a network of virtual profiles, effectively mimicking the scenario of multiple devices playing the video simultaneously. By utilizing browser fingerprinting and proxies, each view appears unique, preventing YouTube from recognizing them as coming from a single source. Proxies also enable these views to originate from various geographical locations, making the activity appear more organic. Ultimately, the system behaves like genuine viewers.
Beyond automated views, the bot can also like videos, subscribe to channels, and leave comments, further enhancing the authenticity of its actions.
YouTube Booster offers extensive session customization, allowing you to configure watch times, set probabilities for certain actions, implement smart rewind behavior, manage commenting, and much more.

# 🧑‍💻 Installation

**Attention!** If you created accounts through a [Google Accounts Creator](https://youtube-booster.space/google-accounts-creator/), you do not need to generate profiles. You can immediately go to the next stage (2). Just move the accounts data from the google\_profiles.xlsx file (in the root Google Accounts Creator folder) to the google\_profiles.xlsx file in the /YoutubeBooster/settings/ folder. Also, specify the same path to the folder with the profiles that you specified in the Accounts Creator.

Since promotion should occur as naturally as possible, you need to create an artificial audience of viewers (bots) that will watch your videos. The audience will consist of browser profiles which will be controlled by YouTube Booster. All profiles will have unique fingerprints (browser and system fingerprints). Each profile for YouTube will look like a separate, unique viewer.

**YouTube Booster uses 2 types of profiles:**

- **Profiles with Google accounts.** These are the profiles that are authorized in the Gmail account. Youtube will treat these profiles as users logged into their Google (YouTube) account. Causes more trust from Youtube, allows to increase likes, comments, subscribers, etc.
- **Incognito profiles.** These are simply profiles that are NOT authorized in a Gmail account. YouTube will treat them as regular viewers without a Google (YouTube) account. This type of profile only allows you to watch videos. Likes, subscriptions, etc. will not work. However, this is absolutely normal, because many of us also use YouTube without an account.

For more naturalness, we will use both types of profiles at the same time. I recommend generating profiles in the following proportion: 60-70% Google profiles, 30-40% incognito profiles.

To get started, you need to decide how many profiles to generate. I recommend starting with 500-1000 profiles. In the future, if necessary, you can increase their number.

## ✅ Stage 1: Profile generation

 1. Open the root folder of the program and run YoutubeBooster.exe (the first time the application opens longer, please wait). If the Launcher window freezes for a long time, try disabling all antiviruses, firewalls and enable VPN (in case your ISP can block connection to BAS servers). If all else fails, try to run the program on another PC or server.

![](https://lh7-rt.googleusercontent.com/docsz/AD_4nXc-oTgwxIr1w2ZdAT_KRxcBO5ivL9780n4zzo8K3j4Vckh2ibvGnpH7rFQfk3yPxf5q6NOa6wTLOgBN2BlKdA8XgH7nLCvvKy9k9AM3M8mvMlMp3KaMduMk2DrwAgXzeRXYeWBsF3lL0UZnPdTLylmJYB4?key=7ArAOMbhZmMwzdDyH15Adw)

 2. In the window that appears, select "Run now" and click "OK".
 3. After the main program window opens, select the Working Mode “Profiles Generation”. _(See screenshot below, number 1)_
 4. Choose what type of profiles you want to generate. In our case, you need to check the boxes as shown in the screenshot below _(numbers 2 and 3)_.
 5. If you have enabled the “Generate profiles for Google accounts” option, profiles will be created for all accounts that you have previously entered in the google\_profiles.xlsx file. If you have enabled the “Generate incognito profiles” option, you need to specify how many Incognito profiles to generate. In our case, 300 profiles. _(See screenshot below number 4)_.
 6. All browser fingerprints for profiles are parsed from the [FingerprintSwitcher](https://fingerprints.bablosoft.com/) service. In the free version, each fingerprint is received with a delay of 3 minutes. I recommend purchasing a premium key because sorting prints in the free version will take quite a long time. Then enable the “FingerprintSwitcher Premium” option in the program _(see screenshot below, number 5)_ and enter your key in the field below _(see screenshot below, number 6)_.
DO NOT ENABLE PREMIUM IF YOU DO NOT HAVE THE KEY, IT WILL NOT WORK.

 7. By default, all profiles will be saved to the "profiles" folder in the root folder with the program. But, if you need to specify a different location, this can be done on the “Advanced” tab. _(See screenshot below, numbers 7, 8)_.

![](https://lh7-rt.googleusercontent.com/docsz/AD_4nXfON-nI84iSPSuz01ayrJLyoY3hYHVSsdmZBDnFLoG1byT6cgE4mTyulViMKrq5D4pKTNwpyuxLErhB9q5ydQ7nG11SZy8zw61IHbAakRTNrU8_62Ck28RidCQSSSK4Adci3r7J18UBEhsq1XR1Re-2mthe?key=7ArAOMbhZmMwzdDyH15Adw)

**Ready!** Start generation. Click “OK” and wait for the process to complete, and then proceed to the warm-up phase.

In the process of generating profiles, errors like “Query limit reached” or "Fingerprint is not valid" may occur, you can ignore them, FingerprintSwitcher server is buggy.

After the generation is completed all profiles will be saved in the "profiles" folder in the root folder of the program (or along the custom path that you specified in the settings). The google\_profiles.xlsx file will remain unchanged, and the IDs of all Incognito profiles will be written to the incognito\_profiles.xlsx file. They will be useful to us in the next stages.

**Try not to interrupt the generation process!**

**It is recommended to regenerate profiles every 2-3 months. In order to do this, simply delete all folders with profiles and start the generation, and warm-up again.**


## ✅ Stage 2: Warm Up of Profiles

Profiles warm up is the process of making the profiles look natural. If you try to promote a video with newly created profiles without warming up, Google will consider you a bot and simply will not count the views. That is why profiles need to surf the sites, watch videos, click on different links for some time and the profiles become more realistic, and views no longer arouses suspicion.

In short, by warming up we give history and trust to profiles.

**Notes:**

- Warming up should be done for at least 10 days, at least 4 minutes a day for each profile. Then the profiles can be sent for work. However, if your channel is not very popular, there may be drops of likes, dislikes, comments. In this case, you need to send the profiles for warming up again and increase their trust. This is due to the fact that Youtube is skeptical about young videos and channels, so any activity on them is closely monitored.
- Do not remove headers in configuration files. The script ignores them.
- If you are using mobile proxies, do not try to use them in another script at the same time, as there will be crashes.
- While the script is running, all configuration files must be closed, because the program will not be able to access them.

**Let's start setting up the script:**

1. Open the "settings" folder in the root of the program folder.
2. Fill in the keywords.txt file with search queries that the script will use to google and open sites.
- You have to enter one request per line.
- Search queries should be related to the topic of the video you plan to promote. It is also preferable to mix them with general queries.
3. Fill in the links.txt file with links to various sites that the script will visit.
- You have to enter one site per line.
- Sites should be relevant to the topics of the videos you promote. It is also preferable to mix them with common sites.
4. Fill in the warm\_up\_videos.txt file with links to various videos that the script will use to warm up profiles.
- You have to enter one video per line.
- Videos should be related to the topic on which you promote your own videos. It is also preferable to mix them with videos on general topics.
5. **Proxy purchase and connection.**
**Which proxies to choose (very important)?**
Quality proxies are 80% of success. The script works with all types of proxies, but it is best to choose between mobile and residential.
- Mobile LTE private channel (individual) with IP change on demand (by API link) is the best choice.
- Preferably with the substitution of Passive OS Fingerprint for Windows.
- Do not buy proxies from very popular sellers, there may be heavily spammed IPs. The ideal option would be to make your own proxies through a modem or an [old phone](https://iproxy.online/invite/friend/mAAGVJKtEu).
- Proxy recommendations: <https://youtube-booster.space/#1602704530767-c9f2a000-502a> .
- A proxy is a very important thing, if you want to save money, it can turn against you. Of course, you can try, on a small scale it may work, but my recommendation is above.
**How many proxies should I buy?**
- **Mobile:** 1 mobile proxy per each 1 000 profiles. 1 mobile proxy allows you to support up to 3 simultaneous threads. 2 mobile proxies - 6 threads, etc.
- **Residential:** depends on the type of proxy. If it is with a static IP - then 1 proxy for 1 profile. If with a dynamic IP change, then 1 proxy for 1 000 accounts. The number of threads per 1 residential proxy depends on the number of available ports in your plan, check with your seller.
- **Regular (static IP) proxies:** 1 proxy per 1 profile. 1 proxy - 1 thread.

**Proxy connection:**

**Attention! Carefully use the Excel autofill handle (Auto Fill Options) as an arithmetic progression may be activated and for other profiles, the proxy data will be filled incorrectly. When using an autofill handle, hold down the CTRL key, then the progression will not be applied. Be sure to check the correctness of the proxy in other cells.**

 6. Open the files google\_profiles.xlsx and incognito\_profiles.xlsx and for each profile:
 - In column E, enter a proxy data in the format http\://ip:port\@login:password or socks\://ip:port\@login:password. If you got proxies without a login and password, you can simply enter socks\://ip:port. Sometimes proxies are served in which instead of IP there is a domain - this is normal. Just use it instead of IP.
 - If you have regular proxies with a static IP, you can skip the following two steps.
 - If you have a proxy with automatic IP change or auto restart of the modem by interval, enter this interval in minutes in column F. **Important**: _You just need to enter a number. If the IP of your proxy changes every 10 minutes, then it is better to enter 9 in the file so that the script has time to complete the thread._
 - If you have a proxy with an IP change on request (via an API link), enter this link in column G. Such links are also called “Reset IP links” An example of such a link: http\://proxy-provider.com/change-ip/7932739dh98h23
If you don’t know where to get all this data or don’t know exactly how your proxy’s IP changes and whether it changes at all, contact your proxy provider and ask him for this data.
 7. Run the YoutubeBooster.exe program again and select the “Warm Up” as Working mode. _(See screenshot below, number 1)_
 8. Specify the number of threads. _(See screenshot below, number 2). The maximum number of threads depends on the power of your PC or server, as well as the number of proxies. For example, if you have 1 mobile proxy, then you need to specify no more than 3 threads, if you have 2 mobile proxies - specify no more than 6 threads, if you have a residential proxy with a dynamic IP change for 10 ports, you can specify 10 threads. If you have regular static proxies you can specify the number of threads equal to the number of purchased proxies._
 9. Specify the path to the folder with generated profiles _(See the screenshot below, number 3). If at the stage of generating profiles you did NOT specify a custom path to the folder with profiles, then specify the path to the profiles folder, which is located in the root of the program. For example: C:/YoutubeBooster/profiles/. If you specified a custom path, then enter the same here._
10. Specify the warm-up duration for each profile in minutes. At least 4 mins is recommended. _(See screenshot below, number 4)._
11. Set the warm-up ratio for YouTube and other sites. Recommended 80% warm up on YouTube, 20% on sites. _(See screenshot below, number 5)_. These numbers must add up to 100.
![](https://lh7-rt.googleusercontent.com/docsz/AD_4nXdfQ_1XECFNeg4SgXVuOoM1mxcgRn1wgsE4_fdLRD6VH0Pgst6j-XD4EYj24FhRtYvkufhreJqdY4dVGiWSS2dfaWKpzEjhWUTCj079lpp0c4R5N1-oQNDXO68xVumf5GhEzfftQvuEwWPYH0ElsKggmBC5?key=7ArAOMbhZmMwzdDyH15Adw)
12. Go to the “Proxy” tab.
12. Select the type of your proxies: mobile or regular (residential or static IP). _(See screenshot below, number 1)_
13. If you chose mobile proxies, specify the type of IP change. It is recommended to use a proxy with IP change via API link. _(See screenshot below, number 2)_
14. Specify the maximum number of threads per proxy _(See the screenshot below, number 3)_:
- For mobile proxies, it is recommended to set no more than 3 threads;
- For residential proxies, you need to set the number of threads equal to the number of ports for this proxy;
- For regular proxies with a static IP, you need to set 1 thread.
![](https://lh7-rt.googleusercontent.com/docsz/AD_4nXf8JBlyogP72V95JU0G3E_q6z5TvM3s9DZOPTbVlwO3pVw7Gtit1ELHeLFSL5t_U6Pfsi1A_nrQsJia68jVNZwpZpiSR5tkU6Bst6uKLYP-GGEyFPO6q4dUMO9TWlBtVBYB9nuqWdM7XbpQk7JnENQ0i082?key=7ArAOMbhZmMwzdDyH15Adw)
15. Go to the Captcha tab.
16. Select the captcha solving method (Automatic, Manual, Skip) _(See the screenshot below, number 1)_:
- Automatic (recommended) means that the program will send the captcha to a special service and it will automatically solve it.
- Manually means that the program will ask you to manually solve the captcha each time.
- Skip means that the program will skip the profile when captcha appears.
17. If you have chosen the automatic method of captcha solving, select the service that will solve it. It is recommended to select [CaptchaGuru](https://captcha.guru/en/reg/?ref=109944) (See screenshot below, number 2). 
18. If you chose the automatic captcha solving method, enter the API key for the service that you selected in the previous step. Also, do not forget to replenish your account on the service _(See the screenshot below, number 3)_.
![](https://lh7-rt.googleusercontent.com/docsz/AD_4nXfFxL7A83ewjTsJ-qNj8e4fP0U5108bXr1DM4qJNsme8LLznUP24tGTe-165L-0ZbmEKbJ6KT3B_bnDBJrI0phm7pQNxfacv0B1x6MJ0GGca-NExzgeV0lG3SHMeIHlC-wNuHtCaHEk-L9gFQUM5re1kdU?key=7ArAOMbhZmMwzdDyH15Adw)
19. Go to "SMS" tab.
20. Select the behavior method when the account requests SMS verification _(See the screenshot below, number 1)_:
- Use SMS service (recommended). The script will use a temporary number from a special service and receive an SMS with a code on it.
- Skip means that the program will skip accounts that request SMS verification.
- Delete. The account will be deleted if it requests verification by SMS.
21. If at the previous step you chose to use the SMS service, specify which service to use. I use smshub.org _(See screenshot below, number 2)_.
22. Specify the country of phone numbers. It is recommended to use the same country where your proxies are from _(See the screenshot below, number 3)_.

23. Specify the API key from the SMS service that you selected earlier. _(See the screenshot below, number 4)._ Do not forget to deposit money on the service balance.

24. (Optional. For advanced users.) Specify a custom server for the SMS service. Suitable if the service you need is not in the list of supported SMS services, but your service works using the same API as one of the previously selected ones. _(See screenshot below, number 5)._

25. (Optional. For advanced users.) Cellular carrier. Specify the name of the mobile operator in the form in which it is perceived by your service, for example, vodafone. Only the numbers of this operator will be requested.

![](https://lh7-rt.googleusercontent.com/docsz/AD_4nXcryeTv1C-6qbl0galVGU4RwL54EiBzrCSyBme3v8v1gh1y1Wy4556Po9iQQDDiMn21m9DQZ0sPW-eoS_U-ljQ6TG1nBFMDttwhEKcFnZzBYfTIrR2BGnLr7WcP92xDiL-bJmMDIF0qetComWiqfPGigngW?key=7ArAOMbhZmMwzdDyH15Adw)

26. Go to the "Advanced" tab.

27. If you run the program through the Scheduler, specify the absolute path to the folder with the program, for example: C:/Users/Admin/Desktop/YoutubeBooster/. _(See screenshot below, number 1)_.

28. (Not recommended) Set skip frames. The function is needed if there are not enough system resources. Setting a frame skip means that all rendering, js execution and in general all actions related to the browser will be performed once per frame skip / 30 seconds _(See screenshot below, number 2)_.

29. If there are problems while running with the program, enable “**Detailed log**”, this will help diagnose the problem. It is not recommended to turn it on when everything is ok, it affects performance _(See screenshot below, number 3)_.

30. Specify the behavior if the account requests a code from the backup mail _(See the screenshot below, number 4)_:

- Process Automatically means that the script automatically verifies the account if the google\_profiles.xlsx file contains additional mail and a password for it. Additional mail accounts must have IMAP enabled.

- Process Manually means that you will need to manually receive and enter this code each time.

- Delete means the account will be deleted.

31. Specify the maximum number of attempts to connect the proxy. When the failed attempts limit is reached, the thread will be restarted. _(See screenshot below, number 5)_

32. Specify whether you need to receive new fingerprints for broken profiles _(See screenshot below, number 6)_.

33. If you enabled receiving new fingerprints in the previous step, specify the API key for FingerprintSwitchcer service. This is optional, but if you have too many broken profiles, the script will hang.

34. Delete profile folders of banned accounts. The function helps to save disk space by deleting unnecessary profiles.

35. Specify how often to clear the profile cache. It is recommended to set every 7 days.

36. Click OK and the warm-up process will start.

![](https://lh7-rt.googleusercontent.com/docsz/AD_4nXdBhvaPeq1O-phmyWuI899hO3rpJ_ptp8rvU8leg-mBQqhfLSxoOHtz2BI80Qy_quiuN-x5oq03Wi60MMzsS_yxGKexr37hX5YwQZtOrKUkwRFqOS2NDdOQ5xxPK-w6lJGT3yfAuYs3HfHl1KAv2DQ0Fj6B?key=7ArAOMbhZmMwzdDyH15Adw)


## ✅ Stage 3: Video Boost

1. Open the task-manager.xlsx file in the settings folder. This file allows you to set the settings for each individual task (video). The parameters of each column are described below _(all parameters marked with an asterisk "\*" are required)_. The file is opened via Excel. You can list multiple videos in the file, one per row.

**Description of features:**

- ﻿﻿﻿﻿﻿﻿﻿﻿﻿﻿﻿﻿﻿﻿﻿﻿﻿﻿﻿**Video / Playlist URL\*.** Enter the link to the video or playlist you want to promote. Format: https\://www\.youtube.com/watch?v=DWQp0p26diU. Do not use shortened links or links with parameters.

**_Attention (If you use promotion through playlists)!_** _The script only watch the first video in the playlist, so your video must be the first in it. All the same functions as for regular videos are supported._

- **Pause between executions\*.** The parameter specifies a pause in minutes between job executions for each individual video. Format: 10-50. If no pause is required, set the value to 0.

- ​​**Duration of pre-start warm-up\*.** It means that the script will surf YouTube and watch other videos before watching your main video. This reduces the chances of view drop. The parameter is responsible for the duration of warm-up in minutes. Format: 2-6 (random time from 2 to 6 minutes will be chosen). Recommended values ​​are 2-6. 0 - pre-start warm-up will be disabled.

- **Which channels or videos or search queries to open at the pre-start warm up.** If you enabled warm-up in the previous step, specify which channels, videos or search queries should be used for warm-up. It works as follows: the script will search the home page for the videos or channels videos you specified and, if found, will open them. The search will open a random video for the query you specified. Use ; as a separator. If the cell is empty, the script will open random videos. An unlimited number of targets are supported. It is also worth noting that if during the warm-up the script detects the target video in the suggestions, it will be opened, this will increase the number of real visits from the recommendations. Video links, channels URLs, and search queries are supported. If you want to mix the specified targets with random videos, add the random parameter. Example: _https\://www\.youtube.com/watch?v=qor1ndH0gnQck;https\://www\.youtube.com/@UndergroundSU;youtube bot;random_ 

- **Number of views\*.** The parameter specifies the number of views to be performed. Fill format: 350.

- **Video watch duration %\*.** The parameter sets the duration of video watching in percent. You can specify “from and to”, a random value will be selected. Format: 40-75. Recommended values ​​are 40-70.

- **Rewind on start.** The parameter tells the script how many percent of the video at the beginning should be skipped. Format: 4-10. Leave 0 to disable rewind.

- **Number of smart rewinds.** The script can do smart rewind while watching a video. This parameter sets their number. Format: 1-4. Set to 0 to disable.

- **Like chance %\***. The parameter sets the like chance for the video. 0 means never like, 100 means always. The parameter works only for accounts. Format: 15.

- **Dislike chance %\*.** This parameter sets the dislike chance for the video. 0 means never dislike, 100 means always. The parameter works only for accounts. Format: 15.

- **Subscribe chance %\*.** The parameter sets the chance of subscribing to the channel. 0 means never subscribe, 100 means always subscribe. The parameter works only for accounts. Format: 15.

- **Chance of notification %.** The parameter is responsible for enabling notifications from the channel. 0 means never turn on, 100 means always turn on. The parameter works only for accounts. Format: 15.

- **Comment chance %\***. This parameter sets the comment chance for the video. 0 means never comment, 100 means always. The parameter works only for accounts. Format: 15.

- **List with comments.** The parameter specifies the path to the .txt file with comments. Format: C:\youtube-booster\comments.txt. One comment per line. You can leave the cell empty if the chance was set to “0” in the previous step.

- **Skip ad chance\*.** The parameter sets the chance of skipping ads. 0 means never skip, 100 means always skip. Format: 85.

- **Traffic sources.** This parameter allows you to set the sources of visits as a percentage.

Supported sources:

 - direct,
 - main (visit from YouTube home page, if video will be available there),
 - search (visit from Youtube search, seek up to 100 place in SERP),
 - channel URL (visit to the video from the channel page, specify only the link to the channel with the target (your) video),
 - notifications (visit the video from notifications, if video will be available there),
 - google (visit the video from Google search results, the search goes only on the first page of search results),
 - simulate a visit from suggestions (just specify the URLs of any other videos from which you want to simulate a recommended visits),
 - visit from an external site (specify the URL of any site from which you want to make a visit, the video does not have to be placed there).

Fill format: direct(**30**);search(**20**);main(**10**);https\://www\.youtube.com/watch?v=xxxxxxxxxxx(**5**);https\://www\.youtube.com/watch?v=yyyyyyyyyyyy(**20**);facebook.com(**5**);google(**5**);notifications(**5**).

Use semicolon ";" as a separator. In parentheses specify the chance of using the visit source in %. The total should not exceed 100. You can leave it empty, then all transitions to the video will be direct.

- **YouTube search queries**. (If you specified a visit source "search" in the previous step.) This option allows you to specify the search queries that will be searched for on Youtube to navigate to your videos. Separate requests with a semicolon ";". Can be left blank if you didn't use the search source in the previous step.

- **Search Filters.** The parameter allows you to specify which filters to apply in YouTube search. Can be left blank if you didn't use the search source in the previous step.

**Supported filters:**
|                 |          |                 |                  |             |
| :-------------: | :------: | :-------------: | :--------------: | :---------: |
| **Upload date** | **Type** |   **Duration**  |   **Features**   |   **Sort**  |
|    last hour    |   video  | under 4 minutes |       live       |  relevance  |
|      today      |  channel |  4 - 20 minutes |        4k        | upload date |
|    this week    | playlist | over 20 minutes |        hd        |  view count |
|    this month   |   movie  |                 |   subtitles/cc   |    rating   |
|    this year    |          |                 | creative commons |             |
|                 |          |                 |        360       |             |
|                 |          |                 |       vr180      |             |
|                 |          |                 |        3d        |             |
|                 |          |                 |        hdr       |             |
|                 |          |                 |     location     |             |
|                 |          |                 |     purchased    |             |

For example, you need to find a 4K video 10 minutes long that was uploaded within a month sorted by views. You need to enter the following data in the cell: **_this month,0,4 - 20 minutes,4k,view count_**. You need to enter data exactly as in the table, without extra spaces and other characters. If you want to leave a specific filter as default, just enter 0. If you don't need to apply the filter at all, just leave the cell blank.

- **Google search queries**. (If you specified a "google" visit source in your traffic sources.) This option allows you to specify the search queries that will be searched on Google. Separate queries with a semicolon ";". Can be left blank if you didn't use google source.
* **Chance of SAVE %.** The parameter is responsible for the chance of adding a video to favorites. 0 means never save, 100 means always save. The parameter works only for accounts. Format: 15.
- **Ad click chance %.** From 0 to 100. 0 - monetization clicks are disabled, 100 - always click. It is not recommended to enable it!
- **Simulate activity on the advertiser's website.** If this option is enabled after clicking on an ad, the script will simulate activity on the advertiser's website. Format: "Yes" or "No".

Save the file and close it. The rest of the files are already filled in and configured.

2. Run the YoutubeBooster.exe program again and select the “Video Boost” as Working mode.
3. The rest of the settings can be left as is, everything has already been configured in the previous step. Just click OK and the promotion will start.

## Advanced Settings (DO NOT MAKE CHANGES UNLESS SURE)

1. Enable advanced settings as shown in the screenshot below and switch to the “Developer” tab.
![](https://lh7-rt.googleusercontent.com/docsz/AD_4nXfx1MO6NLUzIJ1-NRRvKdhdF3n5-VJYJomcGqlGPSZtY-iaTCM80gnmkYnAXXbNm8KA62qj_EKD5vpDhKicpDdrkvUGRFNFDLnPZ2eBkUJnVJl4UYXD8Zmi7oyv7qBdmtft3PNZ0vFoHb_ke6oMnrbNfRE?key=7ArAOMbhZmMwzdDyH15Adw)
2. **Disable fingerprint existence check.** The function disables checking for the presence and validity of the profile fingerprint. _Number 1 in the screenshot below\._
3. **Block files downloads.** The function allows you to block the download of certain types of files (for example, jpg). It can be useful if there is not enough bandwidth or tcp proxy connections. Use a semicolon as a separator. Fill format: jpg;png. _Number 2 in the screenshot below\._
4. **Enable all actions.** In “_Video Boost_” mode, the script will execute all available jobs, regardless of the settings in task-manager.xlsx. _Number 3 in the screenshot below\._
5. **Deep log.** More detailed log will be activated. _Number 4 in the screenshot below\._
6. **Method for getting IP info.** Database - internal database is used (less accurate). ip-api.com - specialized service is used (may cause occasional script freezes). _Number 5 in the screenshot below\._
7. **_Enable QUIC support._** __The feature enables QUIC support for proxies. Disable this option if you get problems with the proxy.

![](https://lh7-rt.googleusercontent.com/docsz/AD_4nXfyaiZ_oSchMesMkLG-MBuPx63nO2QOWyIlbfAwt45FBHHTRhdphVYukaAZHZQv44KsQubMpVcM7QE98-6w8if84YNC6KEv_B9Yb12Pnw2hSYSYanMwUEGLwKpx9W3EVT5p7uQIyKOvAAfCEl_NTSnPEpg?key=7ArAOMbhZmMwzdDyH15Adw)


# ⚙️ System Requirements

The bot is designed to run on Windows (compatible with 8.1 or 2016 and above). The program can only be run on regular PCs and laptops or servers (Virtual or Dedicated). It is not a mobile application and cannot be run on a smartphone or tablet. Taking into account the fact that the computer must be turned on while the program is running, it is recommended to use a server (VPS or VDS). Any server will be ok.
Can I run the YouTube traffic generator on MacOS or Linux? Not directly, but using a virtual machine (VMWare, Parallels Desktop, VirtualBox) will not be a problem.
The program is quite efficient in terms of resource consumption. We are constantly working on performance optimization. Minimum system requirements: 2 threads CPU, 8 GB RAM, and at least 200 GB HDD or SSD. A graphical card (GPU) is not required.
It is very difficult to calculate the number of threads that can be run on your system, as all hardware is very different, so you can understand how many views you can get only after tests. Just as it is impossible to calculate the capacity of the server to handle the number of threads you need.
Do I need to install any additional programs, libraries, modules, plugins, or add-ons for the program to work correctly? No, the software to boost YouTube views itself will setup all the necessary software during the installation process.

# ❓ FAQ

## - [What do I need to purchase besides the bot?](#1602704574171-0a04fcc3-89a1)

*   Proxy.
*   Google accounts (not necessary).

## - [What proxy do you recommend and how many do I need?](#1602704530767-c9f2a000-502a)

*   Mobile LTE (private channel, with IP change (rotate) by interval or API request).
*   Residential.
*   Server (with static IP) (IPv4, IPv6).

## - You can buy a proxy here:

**Mobile (recommended):**

Mobile IP addresses are more trusted by Google. Also, mobile proxies allow you to change IP addresses endlessly. Therefore, 1 mobile proxy can serve several thousand profiles (accounts).

[https://iproyal.com](https://iproyal.com?r=youtube_booster)  
[https://mobileproxy.space](https://mobileproxy.space/en/?p=29804)  
[https://proxylink.pro](https://proxylink.pro/youtube-booster)

**Residential:**

[https://proxylink.pro – GET -50% OFF – promocode: YOUTUBE](https://proxylink.pro/youtube-booster)  
[https://www.tabproxy.com](https://www.tabproxy.com/?utm-source=yl&utm-keyword=?sk01) – Start at $0.7/GB  

You can also configure a mobile proxy on an old phone through this service [IProxy.online](https://iproxy.online/invite/friend/mAAGVJKtEu)

## - [Where I can buy Gmail accounts?](#1639087260809-a6ff4354-c066)

*   [accsmarket.com](https://accsmarket.com/?ref=338617)
*   [accfarm.com](https://accfarm.com?ref=MTAwODQ2S3V6aWFDYXQ=)
*   But the better choice will be to use [this software](https://youtube-booster.space/google-accounts-creator/).

## - [Is it possible to work without Google Accounts?](#1602704573345-1fc03058-e075)

Yes, the script allows you to generate incognito (unauthorized) profiles and work with them.

## - [What is "profile warm up" and why is it needed?](#1602704530820-b6a31d6f-920f)

If you start promoting your videos from newly created profiles, Google may consider you a bot. Therefore, you need profiles with history. A separate script (included) will visit sites, and videos, create the appearance of a real person, and make a history for profiles. This is called warming up.

## - [How many threads I can use?](#1602704575070-e29b7c4b-f134)

**Unlimited.** But, it all depends on your PC/server. Hardware with 8 cores, and 16 GB of RAM without a GPU, you can pull up to 10-20 threads (depending on the configuration). On a PC with a GPU, you can launch more threads. Just in case, the script has a built-in feature for skipping frames, forcing the browser to do fewer page renders, and you can boost the performance. But this can affect the quality of the work, so it’s better to take more powerful hardware.

## - [How many views, subscribers, likes, etc. can I send?](#1684060320325-d53b938c-7eb7)

The program is not limited. Depends on the number of accounts, proxies, and PC/server configuration.

## - [How many views can you get per day?](#1684060438106-43b20f44-a57e)

Not limited. Depends on the power of your PC / server, the number of proxies, and the duration of the video. On average, several thousand views per day.

## - [What is the percentage of views drops (write-offs)?](#1602704576139-ec012cf2-301e)

About 5-7%.

## - [How many PC/servers can I run on one license?](#1602704574870-1d24d25f-fe10)
1 license — 1 PC/Server.
## - [What is the monthly subscription charged for?](#1602704574642-d44fcf2c-2446)
Monthly updates, bug fixes, and quick corrections when YouTube makes changes to the interface.
## - [Supported OS?](#1602704574420-f24ab144-6bb1)
Windows 8,10,11. Windows Server 2016, 2019, 2022.
If you use Mac or Linux, you can buy the cheapest VPS on [Contabo](https://contabo.com/en/vps/) and run program there.
## - [Can I run the program on a VPS or VDS server?](#1660648222884-c00894b5-c004)
Sure. I recommend buying VPS [contabo.com](https://contabo.com/en/vps/). You can take the version with 6 cores and 16 GB of RAM.
Recommended server OS: Windows Server 2016, 2019.
## - [What languages and countries does the script work with?](#1602704573911-4fd87d78-6203)
The bot works with any country and language.
## - [Can I get monetization using the program?](#1648712480388-22c31efe-dc12)
Yes, it is possible to get monetization with the help of the program.
## - [How many views can I send using the program?](#1683199730361-91e8462f-8864)
The program is not limited. Depends on the duration of the video, the power of your PC/server, and the number of profiles and proxies. On average, this is several thousand views per day.
## - [Are views paid for by monetization?](#1660678994597-d50c22d8-5d9f)
Sure. YouTube detects views from a bot as ordinary viewers.
## - [Can the program work on API and POST/GET requests?](#1602706586593-d5ad5197-7899)
No. I set myself the task of maximum user emulation.
## - [Is there a manual included?](#1639087139961-44762708-8eda)
Yes, the program comes with a detailed step-by-step tutorial.
## - [It is safe?](#1637311834365-f4f5f53b-fdd5)
Yes. In the worst case, YouTube simply does not count views, otherwise, it would be used to pessimize competitors’ channels.
## - Which server to buy for the program?
I am using [Contabo](https://contabo.com/en/) VPS. Up to 10 threads, you can take the simplest plan.
## - How is the script updated?
The update happens automatically every time you start the program.
## - Profiles are generated for a long time or the message “Query limit reached” is displayed, can I speed it up somehow?
This is an artificial limitation of the third-party service https\://fingerprints.bablosoft.com. You can purchase a premium key, enter it in the script settings and the restriction will be lifted.
## - When warming up, the weight of the profiles constantly increases, is this ok?
Yes, it is normal. Each profile essentially emulates a regular browser profile and stores a cache that grows in size. The weight of the profiles after maximum warm-up will be approximately 40-70 mb. Perhaps in the future it will be possible to clear the cache (it does not depend on me).
## - The script runs, but only a white screen in the browser window.
Most likely a problem with the proxy. Check again the correctness of the entered data and the workability of the proxy. It may also be because you enabled ip-api.com as an IP check method, try returning to "database".
## - Failed to connect proxy
Check that the proxies are entered correctly and that they are working. Also your PC or server may be blocking connections. In 99% of cases the problem is on the client side.
## - The script constantly gives an error: "Failed to restart the modem"
 - Check the correctness of entering the API links for rebooting the modem.
 - Proxy problem. Contact your proxy provider.
## - The script says "Could not find a file with comments on the path ...”
You incorrectly specified the path to the comment file in task-manages.xlsx.
This is not a critical error, the script will continue to work, it will just not leave a comment.
## - The script hangs for a long time on the action “Waiting for IP change”.
Most likely there was some internal failure. Just reload the script. If it does not help, check the proxy and the API link to change the IP.
## - The script does not take new tasks and displays the message “Video is waiting for the pause to end.”
This means that you have set the Pause between execution parameters in task-manager.xlsx. Clear the cell and the script will run without pause.
## - Views, likes, etc. are dropped.
Most likely, you need to additionally warm up the accounts (1-2 weeks). But there can be many reasons, low-quality proxies, accounts, etc.
## - Where can I see until what date the license is valid?
In the lower left corner of the program.

# 🔗 Useful links

**Subscription renewal:** <https://youtube-booster.space/renewing-subscription/>

**Google Accounts Creator:** ​​<https://youtube-booster.space/google-accounts-creator/>

**Binding reset:** ​​<https://youtube-booster.space/binding-reset/>

# 🗒️ Notes

**If you need to move the script to another server or PC**, close the program completely on the current machine, follow this [link](https://youtube-booster.space/binding-reset/), enter the login or email from your license (EXACTLY AS SPECIFIED IN THE LICENSE), then wait 3-5 minutes and you can run the program on new instance.
**If you need to install a new copy of the program.** Be sure to install it from the archive as for the first time, you can’t just copy the folder with the already installed program. The settings and system folders can be moved from a folder with an already installed script.
**To update the script**, it is enough to restart the program, you do not need to download the archive with the files again.
### Errors: "Too many usages", "Too much usages", “Only single instance allowed”, Wrong credentials or no license.
**Possible reasons:**
- You didn't buy a license. You can do it here: https://youtube-booster.space/.
- You accidentally copied an extra space or other character along with the login and password.
- You are trying to run a program on multiple machines at the same time. The program can only run on one machine at a time. If you need to move the script to another, read the information above.
- You have an antivirus or firewall that is blocking the connection to the license server.
- The provider blocks the IP of the license server. Try using a VPN or run the program on a cloud server.
- Too many login attempts. Wait a couple of hours.
- Maybe just some kind of glitch. Try restarting the PC/server.
- If all else fails, try another PC/server.
