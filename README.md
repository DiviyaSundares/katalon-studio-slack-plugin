# Katalon Studio plugin for Slack integration

This Katalon Studio plugin provides Slack integration functions.

The main purpose is to collect and send a summary report of an execution to a channel after the execution has completed.

## Build

Requirements:
- JDK 1.8
- Maven 3.3+

`mvn clean package`

## Develop
- Install the `Katalon Studio v6.0.3 or later`.
- Go to *Plugin* > *Install Plugin* and select the generated jar file.
- Click on *Slack* toolbar button to configure.
- Execute a test suite and wait for a summary message.
- If you want to reload this plugin, please click on `Plugin` menu, select `Uninstall Plugin` then select `Install Plugin` again.
