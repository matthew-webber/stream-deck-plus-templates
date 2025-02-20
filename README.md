# stream-deck-plus-templates
Templates (wallpapers, screensavers, etc.) for the ___Stream Deck +___ brand of Elgato peripheral devices

## Dimensions

For the screensaver, `800x480` seems to be the magic number ([source](https://www.reddit.com/r/elgato/comments/106vdt9/comment/m3b5405/)).

## Template Layers Explained

If you look in the layers window on GIMP (maybe in PS, too, idk), you'll see some layer groups labeled _windows_ and _guides_.  The _windows_ group contains the layers which correlate to the physical space for the windows/cutouts on the device itself while the _guides_ represent various imaginary "borders" that my eye perceived while making this template (see below).  If you don't care about about minute detail in your screensaver or wallpaper or whatever, just ignore the guides and stick with the "windows" layer.  Whatever is in the windows layer group will get you what you need with the device.  But if you do care about precision or you want some guides to help you line stuff up in some other app, you might find the border layers useful.

Here's an explanation of what the colors in the guides are intended to communicate (note: all of these are just based on my own perception and have no real basis in anything other than my own head!)
- **Inner border (green)** - the inner border is the 1px wide line constituting the last visible edge of a given square when looking at it "straight on".  The idea is that, if you stared directly at the physical window/square/whatever, the green line would be just barely visible on all sides.
- **Padding (blue)** - the padding is just the area which lives between the inner border and the outer border -- that is, it's not \*technically\* a border.  It's just a colored representation of the space between actual borders.
- **Outer border (pink/purple)** - the outer border is the 1px wide line constituting the last visible edge of a given square when looking at the device completely at an angle.  Like if you looked at the window/square/whatever with your head on the desk because you fell asleep or something, the line produced by the outer border would be the last illuminated strip of pixels visible to you before the chassis got in the way.

Below is a silly graphic attempting to visually represent how I approached perspective in coming up with the different borders:
---
![border-angle-graphic](https://github.com/user-attachments/assets/2b3e59c3-eb03-4b32-a2eb-b22de9e5607d)
