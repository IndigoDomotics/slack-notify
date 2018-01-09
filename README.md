## Summary
This plugin extends [Indigo](http://www.indigodomo.com) allowing it to send messages to [Slack](https://slack.com), optionally with attachments and file upload.

## Requirements
* [Indigo 7](http://www.indigodomo.com/index.html) or later, Indigo 6 Pro
* A Slack Team is required. Register for an account at [Slack](https://slack.com) and set up a team
* Optional: Create a Slack channel to be used for Slack Notify (recommended), or use one of the defaults

## Installation
* Download the ZIP file from Releases (above)
* Unzip the file if it doesn't automatically unzip
* On the computer running Indigo, double-click the file "Slack.indigoPlugin"
* Follow the Indigo dialog and enable the plugin
* The plugin should be visible in the Plugins drop-down menu as "Slack Notify"
* Trouble?: Indigo help for the [installation process](http://wiki.indigodomo.com/doku.php?id=indigo_6_documentation:getting_started)

## Configuration
Check out [the wiki for detailed configuration information](https://github.com/IndigoDomotics/slack-notify/wiki).

## Dependencies
Indigo 7 plugins (the IOM and SDK) use Python 2.7, Indigo 6 uses Python 2.5

## Plugin ID
To programmatically restart the plugin, the Plugin ID is: com.bot.indigoplugin.slack

## Uninstall
Remove “/Library/Application Support/Perceptive Automation/Indigo 7/Plugins/Slack.indigoPlugin” (or check in the Disabled Plugins folder if disabled) and restart the Indigo Server

## GitHub Gist
For a simple python script version: [indigotoslack](https://gist.github.com/achterberg/cbd46bc3b9cdb391eed7)

## Ownership
Indigo Domotics does not assume any responsibility for this plugin. We are hosting it here in our repo for the convenience of our users but we will not be making any changes. If you would like to make changes then just fork, change, and submit a pull request on GitHub and we'll get a new release added here and into the Indigo Plugin Store.
