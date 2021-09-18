# Blaseball '99
Blaseball '99 is a site for watching Blaseball games the way they were obviously intended: on a Geocities site in 1999! 
It was created in August 2021 for the SIBR cursed Blaseball viewer hackathon.  
[View it here!](http://davidthelazar.com/blaseball99)

# Design Goal:
The intent was to replicate the blaseball.com "Watch Live" tab while sticking as closely to the aesthetic of a website from 1999 as possible.  Modern tech was obviously required for serving up Blaseball updates and working around some changes in browsers in the last couple decades, but the aim was to keep the appearance as non-anachronistic as possible. 
This meant using simple text formatting, small images, animated gifs, and avoiding emojis or javascript controls.
In order to fit in as many turn-of-the-millenium web staples as possible, we added on side sites that could contain the guestbook, visitor counter, and chatroom. The animated Cool Spot gif was a must-include, since it is my Most Nostalgic Gif.

# Features:
Choosing a date/time on the home page will start fetching game updates and ticker messages from [replay](https://sibr.dev/apis) for all games that were occuring at that time and display them with a 4-sec update rate.  The game displays support arbitrary numbers of balls/strikes/outs/innings, and will display any message text that the site would have displayed. Note that 4th strike is not supported.
The guestbook on Binky's Webmaster page and the AOL Immaterial Messenger chatroom are both fully functional and rely on third-party services. The code for AIM was blatantly stolen from [here](https://www.scaledrone.com/blog/javascript-chat-room-tutorial/) with slight modifications.



