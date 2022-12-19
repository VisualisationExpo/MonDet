# MonDet
A theme for macOS with a soft color 
![PREVIEW](https://user-images.githubusercontent.com/86615159/208351141-230ee404-6c0e-4542-869b-df1c8f953c9b.png)

Hello again, Good People! 


MonDet theme is meant as a question to me "Mon det kan lade sig gøre?" 

In English it would mean something like "I wonder if it's possible?"


This theme is for Apple's macOS Big Sur in combination with the MacForge plugin; Paintcan

I do this to limit the angst surrounding the changing of themes on macOS Big Sur.

I'll make Paintcan a requirement simply because of it's nature

Theming on macOS Big Sur is not as straightforward as previous macOS versions, such as macOS Mojave and macOS Catalina.

There's no real need for keeping backups of the original .car files when using Paintcan.

Should you however want to edit them and make your own theme the files you need are here:

`/System/Library/CoreServices/SystemAppearance.bundle/Contents/Resources`


> Keep a complete backup of the files in here by copying them(CMD+C) then create a folder somewhere on your disk drive that can keep these files. Paste the files in(CMD+V)
> 
> Duplicate the folder you just made create a ZIP file of the folder you first copied the original .car files to.
> 
> This way you can edit from the duplicated folder and name your **Aqua.car -> NSAppearanceNameAqua.Paintcan.car**

Paintcan will pick up this new file on you pasting it in its Resources folder. Read more about that down below.

Paintcan facilitates an easy method of using themes on macOS Big Sur. In the time of writing macOS Big Sur 11.2.1 is out. Latest macOS Big Sur build number is 2075D.


MacForge is free and Paintcan is free too.

MacForge is maintained by Wolfgang Baird (w0lfschild)
Download MacForge here:
[https://www.macenhance.com/macforge.html]()

Paintcan is maintained by Wolfgang Baird (w0lfschild)
Download Paintcan here:
[https://github.com/MacEnhance/Paintcan]()

MeMiniMe is an optional download - it reduces the toolbar in the Finder and most other places such as;

System Preferences and Safari.

Download MeMiniMe here:
[https://github.com/MacEnhance/MeMinime]()
 

Link to the download is at the bottom of the page.

Both plugins; MeMiniMe and Paintcan is also available within MacForge itself in the Discover section in the sidebar.

Now.. with that out of the way. Let's proceed with getting this theme installed and applied.

If you have Paintcan correctly installed it's located here

`/Library/Application Support/macenhance/Plugins/Paintcan.bundle`

Next, you are to right-click Paintcan.bundle and choose "Show Package Contents" and then dig down through to here:

`Paintcan.bundle/Contents/Resources/`

While in there there's just two files there "NSAppearanceNameAqua.Paintcan.car" and "placeholder"

Don't touch placeholder file - keep that in place.

Instead you copy the "NSAppearanceNameAqua.Paintcan.car" from my uploaded archive within the folder named "Copy the file in here to Paintcan"

The file you need is aptly named
> NSAppearanceNameAqua.Paintcan.car

All theme files are names this. In addition to the abovementioned .car file there's also the Dark variant;

The file you will need for the dark mode is aptly named
> NSAppearanceNameDarkAqua.Paintcan.car

I haven't yet made a dark variant of this theme.

Lastly there's some bits and pieces you ought to be aware of;

I made the discovery that by turning on 
> High Contrast-mode in 'System Preferences -> Accessibility -> Display

It's a better appearance than the non-High Contrast mode.

You can of course decide for yourself on which method you fancy. I will just make the recommendation to use High Contrast mode and the theme preview included in the upload is based on you having turned on High Contrast-mode.

A cDock theme is included too. No icons at this moment, but there’s a small preview here:

## TIPS & TRICKS 1)

I'd like to also add that there are two other small things you can do to make you macOS Big Sur, in general, be more better. One is a terminal command where you change your toolbar to the older macOS(10.15) Toolbar appearance(or similar style)

-

Copy this whole string to a Terminal window:
`defaults write -g NSWindowSupportsAutomaticInlineTitle -bool false`

To return to Big Sur's regular view type:
`defaults write -g NSWindowSupportsAutomaticInlineTitle -bool true`

-

I'll include screenshots within the uploaded archive for the above Terminal command so that you are not doing things blind.

## TIPS & TRICKS 2)

Disabling Library Validation is needed to complete the look of the theme. I forgot to mention this in my initial upload.

Some applications doesn't take on the theme if Library Validation is set to be on. So Disable that.

-

Disable Library Validation for use with MacForge.

`sudo defaults write /Library/Preferences/com.apple.security.libraryvalidation.plist DisableLibraryValidation -bool true`

Re-enable Library Validation for macOS after having used MacForge.
`sudo defaults write /Library/Preferences/com.apple.security.libraryvalidation.plist DisableLibraryValidation -bool false`

-

## PROBLEMS?
There's always a bit of problems or issues with all the mentioned theming. In case you run into issues with anything related to crashing, try adding that particular application to MacForge's blacklist (it's available in the app itself)

I know that VMWare Fusion 12 doesn't take Paintcan too well. That's my experience at least. MacForge yes, Paintcan no.

A thing I learned is that if Safari doesn't work for you on macOS Monterey, then dragging all the files included in this path to MacForge's blacklist:
`/System/Library/Frameworks/WebKit.framework/Versions/A/XPCServices`
 

## TO-DO LIST

I have a plan to revisit this theme with;

1. **At least a menu bar graphic**

1. **Dark mode**

## Please be so kind as to open an issue with your questions 😀

# Thank you for your continued support 😍
