# CursedCord
Cursedcord aims to swap the default soft and bubbly expereience for a more sharp, almost retro feel. The ability to visually remove many of nitros features brings less noise and clutter to discord's UI. ALong with being able to customize nearly every color you can see, this theme allows you to make the experience you desire.

## Features
  - Custom assets for server bars, user status indicators, and more! (nothing fancy, just enough to keep them in line with the sharp theme)
  - Custom coloring for background colors, text color, ping/mention coloring and more.
  - Toggles for hiding nitro features, such as nameplate banners, profile borders/effects/gradients, username colors/fonts, and more.
  - Ability to change fonts
  - Ability to change the home icon to anything you please! images and gifs supported

## Preview
Here are some screenshots of possible colorations for this theme
![alt-text](https://github.com/CursedElectric/CursedCord---Discord-theme/blob/main/Screenshots/themeshowcase1.png "Colors1")
![alt-text](https://github.com/CursedElectric/CursedCord---Discord-theme/blob/main/Screenshots/Themeshowcase2.png "Colors2")
![alt-text](https://github.com/CursedElectric/CursedCord---Discord-theme/blob/main/Screenshots/ThemeShowcase3.png "Colors3")
![alt-text](https://github.com/CursedElectric/CursedCord---Discord-theme/blob/main/Screenshots/Themeshowcase4.png "Colors4")
footnote: I realized after uploading all of these that I made them all black and/or green. You can make the theme any colors you like, I just seem to have a bias for green.

## Compatability (with plugins)
To my knowlege this should work with most plugins as the border changes and colorings are applied at a root level. Of course this probably is not the case for every plugin out there. If my theme does break a plugin please let me know and I'll try my best to fix it.

## Known issues
### I was not aware the built in css editor for betterdiscord only allowed the user to change colors and not variables. I'm hoping to release a workaround soon, but for now going to your theme folder and opening this theme in a text editor/IDE of your choice will allow you to change said variables
I personally have been using this theme for the past 3 months with minor bugs here and there. If you find any bugs not listed here, please let me know on discord @cursedelectric, or by opening an issue on github
  - the typing indicator on dms (the three dots) is not fully hidden when a user is typing. I have not come up with a clever way to incorporate it into this theme yet
  - when using a custom font, bold and italsized fonts will show as normal text
  - 'invite to server' buttons mask next to the server name is slightly misaligned, resulting in the 'invite to server' popup sometimes not showing when hovering the button
  - 'invite to server' button also becomes more misaligned when a server has a banner image
  - when a custom home image is set, it will also appear behind group dms that have an unread message on the server bar, if the group icon is transparent in areas.
  - in rare cases when betterdiscord is updated, it is impossible to close out the update preview notification in the top left of the client. this has only happened once to me. turning off the theme and closing the window is a workaround for this
  - in rare cases, when hovering past a server channel, it will change between the hover color and the default color until it is selected.
  - when there is a notif blip for unread pinned messages, it will appear as an ugly square instead of something more pleasing. this isnt a bug per say, i just think it doesn't look good
  - again, in rare cases, when clicking off of a server channel and onto another, small bits of the selected coloring will be on the previously clicked on channel
  - nitro users colored names are in some cases not being ovveridden
