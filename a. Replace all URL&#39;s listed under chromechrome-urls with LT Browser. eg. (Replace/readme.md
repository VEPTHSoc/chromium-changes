# Replacing all urls under chrome://chrome-urls with lt browse

For this I just had to navigate to: 
```
chromium\src\chrome\browser\ui\webui and there edit the about_ui.cc
```
I attached the screenshot below which depicts the changes that I have done.
![Screenshot](https://i.imgur.com/GWshgTV.png)


_Also I figured that I can change the url navigation link but that would have required me to do some more backend chagnes and due to shortage of time I wasn't able to do_

Then while I was looking at the code of related files I found the file webui_url_constants.cc. This file can be used to change the destination of link on the chrome://chrome-urls page. 
this file is at 
```
chromium\src\chrome\common\webui_url_constants.cc
```
