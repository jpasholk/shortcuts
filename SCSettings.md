<img alt="Static Badge" src="https://img.shields.io/badge/Download?link=https%3A%2F%2Froutinehub.co%2Fshortcut%2F17931%2F">

![SCSettings](https://i.imgur.com/PAUf9ON_d.webp?maxwidth=1520&fidelity=grand)

Quickly access settings or toggles that are burried under several taps. This Shortcut is inspired by the old-school jailbreak tweak, SBSettings. 

*Toolbox Pro [Premium] required for additional features (Checking VPN & Uptime ).*

*You need to turn on **Allow Sharing Large Amounts of Data** in Shortcuts settings [Settings -> Shortcuts -> Advanced -> Allow Sharing Large Amounts of Data].*

*This Shortcut sometimes repeatedly asks for permissions that have already been granted, I'm not sure how to fix this as I think it's a bug in Shortcuts when sharing large amounts of data.*

***

![SCSettings Screenshots](https://i.imgur.com/MbKpJPl.png)

## Show Information About Your Device

When running this Shortcut it will display some information about your device and the network it is connected to, among a few other useful pieces of information.

### Information Shown When Running The Shortcut

* iPhone hardware version
* iOS Version & build
* Current Wi-Fi network
* IP address
* VPN connection status
* Device storage remaining
* Device uptime

## Turn Off Wi-Fi & Bluetooth

The control center Wi-Fi and Bluetooth toggles only disconnects for 24 hours, which can be annoying if you actually want to just turn them off. The first option that appears will let you completely turn it off, as well as show if Wi-Fi is on or off. Since there's no easy way to track if Bluetooth is connected, it's not a dynamic icon.

## Toggle VPN Settings

Open a menu that allows you to toggle VPN on or off, as well as toggling Connect On Demand.

## Silence Unknown Callers

This setting should be on at almost all times IMHO, but it is buried under four taps and it can't be toggled with Siri. 

Luckily, Shortcuts supports turning it on and off with a native action. Since there's no way to track if it's on or off, Toolbox Pro Global Variables must be used to track its state. Because of that it's best to turn it on before running, and only toggle it via this Shortcut.

## Easily Restart Your Device

Restarting your device takes several taps as well, so it's included just in case.

## Access Settings That Apple Buried

This Shortcut includes several links to useful sections of the Settings app that a lot of power users likely access more than they know.

### Settings Shortcuts:

* Analytics Data
* Privacy Report
* Private Relay (added in 0.7)
* Hide My Email (added in 0.9)
* Screen Time -> Content & Privacy Restrictions (added in 0.9)
* Personal Hotspot (added in 0.8)
* Clear Website Data
* Camera Format added in 0.7)
* iPhone Storage
* Search Passwords
* Battery

> ### Credits:
> 
> * Most of the URL schemes come from [FifiTheBulldog’ GitHub Repo](https://github.com/FifiTheBulldog/ios-settings-urls/blob/master/settings-urls.md).
> 
> * Special thanks for Reddit user /u/theoccurrence for the method of getting device data from a file in:
> `file:////private/var/..`
> (Full file path in Shortcut, if I post it here it overflows the viewport, I reported it on Discord).
>
> * The [Apple Frames Shortcut](https://www.macstories.net/stories/apple-frames-3-1-extending-screenshot-automation-with-the-new-apple-frames-api/) by Federico Veticci of MacStories, to create the iPhone framed screenshots for this page.
>
> * And of course SBSettings, the old school jailbreak tweak that inspired me to make this. *If you know, you know…* 😉

Graphics made with [MediaKit](https://routinehub.co/shortcut/1911).

***

Let me know if there are any other settings or toggles to add to make this more useful.

Thanks for checking it out!