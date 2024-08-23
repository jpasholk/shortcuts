# Shortcuts
Home for my iOS Shortcuts.

## SCSettings

![SCSettings](https://i.imgur.com/PAUf9ON_d.webp?maxwidth=1520&fidelity=grand)

<!-- ![Version Badge](https://img.shields.io/badge/Version-1.0-green?link=https%3A%2F%2Froutinehub.co%2Fshortcut%2F17931%2F) -->
<a href="https://routinehub.co/shortcut/17931/"><img alt="Download on RoutineHub" src="https://img.shields.io/badge/Download_On-RoutineHub-%23ee3535"></a>

Quickly access settings or toggles that are burried under several taps. This Shortcut is inspired by the old-school jailbreak tweak, SBSettings. 

~~*Toolbox Pro [Premium] required for additional features (Checking VPN & Uptime ).*~~

 - Removed Toolbox Pro Dependency as of 2.0

*You need to turn on **Allow Sharing Large Amounts of Data** in Shortcuts settings [Settings -> Shortcuts -> Advanced -> Allow Sharing Large Amounts of Data].*

~~*This Shortcut sometimes repeatedly asks for permissions that have already been granted, I'm not sure how to fix this as I think it's a bug in Shortcuts when sharing large amounts of data.*~~

 - Should only ask for permissions with each Settings url-scheme link.

***

![SCSettings Screenshots](https://github.com/jpasholk/jpshlk-blog/blob/main/src/assets/scsettings–screenshots.png?raw=true)

## Show Information About Your Device

When running this Shortcut it will display some information about your device and the network it is connected to, among a few other useful pieces of information.

### Information Shown When Running The Shortcut

* iPhone hardware version
* iOS Version
* Current Wi-Fi network
* IP address
* ~~VPN connection status~~ Removed in 2.0
* ~~Device storage remaining~~ Removed in 2.0
* ~~Device uptime~~ Removed in 2.0

## Turn Off Wi-Fi & Bluetooth

The control center Wi-Fi and Bluetooth toggles only disconnects for 24 hours, which can be annoying if you actually want to just turn them off. The first option that appears will let you completely turn it off, as well as show if Wi-Fi is on or off. Since there's no easy way to track if Bluetooth is connected, it's not a dynamic icon.

## Toggle VPN Settings

Open a menu that allows you to toggle VPN on or off, as well as toggling Connect On Demand.

## Silence Unknown Callers

This setting should be on at almost all times IMHO, but it is buried under four taps and it can't be toggled with Siri. 

Luckily, Shortcuts supports turning it on and off with a native action. ~~Since there's no way to track if it's on or off, Toolbox Pro Global Variables must be used to track its state. Because of that it's best to turn it on before running, and only toggle it via this Shortcut.~~

## Restart Your Device

Easily restart your device from the main menu.

## Shut Down Device

Easily shut down your device from the main menu.

## Access Settings That Apple Buried

This Shortcut includes several links to useful sections of the Settings app that a lot of power users likely access more than they know.

### Settings Shortcuts:

- Analytics Data
- Privacy Report
- Private Relay (added in 0.7)
- Hide My Email (added in 0.9)
- Screen Time -> Content & Privacy Restrictions (added in 0.9)
- Personal Hotspot (added in 0.8)
- Clear Website Data
- Camera Format (added in 0.7)
- iPhone Storage
- Search Passwords (moved to main menu)
- Battery Settings
- AirDrop Settings

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
>
> @twilsonco for helping me understand recursion.
> * And of course SBSettings, the old school jailbreak tweak that inspired me to make this. *If you know, you know…* 😉


***

## [Skyrim Alchemy Tool](https://github.com/jpasholk/skyrim-alchemy-tool)

<!-- ![Version Badge](https://img.shields.io/badge/dynamic/json?url=https%3A%2F%2Froutinehub.co%2Fapi%2Fv1%2Fshortcuts%2F17843%2Fversions%2Flatest&query=%24.Version&label=Version&labelColor=green&color=%23320932) -->
<a href="https://routinehub.co/shortcut/19465/"><img alt="Download on RoutineHub" src="https://img.shields.io/badge/Download_On-RoutineHub-%23ee3535"></a>

![Skyrim Alchemy Tool Hero Screenshots](https://raw.githubusercontent.com/jpasholk/skyrim-alchemy/master/public/skyrim-alchemy-tool-shortcut-2.3-screenshots.png)

This is a complete rewrite of my Skyrim Alchemy Tool Shortcut I released a while ago.

The first one was several Shortcuts with a central one that called the others. It also relied on Data Jar & Toolbox Pro (Premium) which is a bit of a turn off for most people.

For this version I wanted to create a standalone version that:

✅ Is faster

✅ Didn't need external apps
  - Credit: gluebyte

✅ Uses vCard menus to display the information instead of Toolbox Pro's markdown-ish display text action.

## Features

### Browse Effects A-Z

- Browse effects alphabetically, then select an option to see a nice menu of related ingredients.

### Browse Effects By Value

 - Browse effects by their value.

### Browse Ingredients

- Browse ingredients alphabetically, then select an option to see the properties in a nice menu.

### Ingredient Effects

- After selecting an ingredient, you can tap on `Browse [Ingredient] Effects` to present a menu of its effects. Then after choosing one, you can tap on the first menu option again `Browse Effects A-Z` to see a list of all related ingredients.

### Save To Notes App

- After selecting on option in the Effects menu you can choose to save the results to a note in the Notes app. (This does take a few seconds)

***

## Planned Features

- Select multiple ingredients that you have in your inventory and present a menu showing the potions you can make.

## Credits:

- Thanks to gluebyte for not only helping me solve the multiple ingredient bug, but also completely refactoring the json file and repeat loops.
  - Due to this, it also completely removed the need for the Actions app!!

***

## Credits:

- [Linking to a URL with a shields.io badge](https://stackoverflow.com/questions/66716288/embedding-shields-io-badge-html-in-github-readme-rst)
- [twilsonco](https://github.com/twilsonco) for inspiring me to make this repo!