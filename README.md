Gender Neutral Bathrooms
=========================

Android app that finds gender neutral, unisex, and family restrooms nearby.

Contribute
-------
- Clone repo and then "open existing project" into Android Studio

TODO
-------
- when no gps, find city or state, same for when gps location isn't near bathroom
- text directions temp fix -- remove (textdirectionactivity)
- text directions action bar -- back button, settitle
- navigation drawer icon
- red markers vs blue markers? accessibility
- settings icon shows up on nav drawer open
- style Feedback Form better

- more info in info window, Add bathroom rating to info window
- style text directions section -- directions.html
- better add bathroom section, not as a webview
- get location from wifi when no mCurrentLocation -- also for webview
- Add search function
- actionbar activity depreciated
- contact form without email client -- http://stackoverflow.com/questions/2020088/sending-email-in-android-using-javamail-api-without-using-the-default-built-in-a/2033124#2033124
- nav drawer icons
- Make maps info window appear at bottom of screen, like google maps -- might have to do this as a dynamic text view
- Update text directions while on tab?
- Allow get directions from selecting icon
- Screen rotation reupdates map to beginning location...
- signed keystore for play store?
- enable crash reports
- general UX design

Bugs
------
- Going to text section and then back, messes up location and next
- if too far away from bathroom, response is empty from json call (currently then makes a call nearest location)

Screenshots
----------
![](/app/src/main/res/drawable-hdpi/Screenshots/screen1.png?raw=true)
![](/app/src/main/res/drawable-hdpi/Screenshots/screen2.png?raw=true)
![](/app/src/main/res/drawable-hdpi/Screenshots/screen3.png?raw=true)
![](/app/src/main/res/drawable-hdpi/Screenshots/screen4.png?raw=true)
![](/app/src/main/res/drawable-hdpi/Screenshots/screen5.png?raw=true)

Thanks to refuge restrooms for the bathroom list API