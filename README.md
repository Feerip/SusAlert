# SusAlert
SusAlert is an alt1 toolkit app for the croesus fight, it keeps track of croesus' attacks and warns you before they happen.

**Please note that this plugin is still in a pre-release state and may contain bugs.**

![SusAlert-MainWindow](/assets/mainscreen.png)

## How to use
SusAlert is very easy to use, simply install and open the plugin in alt1 toolkit. The plugin will automatically detect when the croesus fight starts or ends.

To prevent the timer from drifting mid-fight you can synchronize it by clicking the button that appears on the interface or pressing alt+1 when the mid energy fungus dies, another solution may be to edit the delay after mid in the settings. For finer control you can use the + and - buttons on the timer to 'nudge' the timer forward or back in 1s increments.

Lastly, there's a mushroom button to start & sync a timer for the mushroom path, which makes it easy to see when the mushroom path will change next. You only need to click the button once when the mushroom path changes, from then on it will continue to work for the rest of the instance.

## Requirements
To function SusAlert needs the following:
- Alt1 toolkit must be installed, you can install that [here](https://runeapps.org/alt1).
- Chatwindow MUST be opaque, this can be changed in the RuneScape Settings > 
Interfaces > Appearance > Transparency
- Chat font must be 12 or higher (plugin is tested with fontsize 12).
- The bosstimer must be visible on-screen.
- At least one chat window needs to be on-screen with game messages turned on.

## Installation
To install SusAlert copy & paste this link into your browser:<br/>
[alt1://addapp/https://raphire.github.io/SusAlert/appconfig.json](alt1://addapp/https://raphire.github.io/SusAlert/appconfig.json)

Or go to this URL in the alt1 browser:<br/>
https://raphire.github.io/SusAlert/

## Known issues
- The timer can go out of sync after the mid energy fungus appears. (Can be manually synced by clicking the button that appears or pressing alt + 1 when the mid energy fungus dies)
- Mushroompath timer may go out of sync over time.
- Old messages can sometimes trigger again.

## Credits
Special thanks to [ZeroGwafa](https://github.com/ZeroGwafa) for his chat detection function, and [Skillbert](https://github.com/skillbert) for his help with making the bosstimer detection.