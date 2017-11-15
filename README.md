# Vibration Plugin Demo

This repository contains a simple project which demonstrates how to use the `cordova-plugin-vibration` plugin with Monaca.

The project shows how to vibrate the device for a certain duration, vibrate in a pattern, and stop a vibration that is in progress.

iOS only supports basic vibration. It will ignore the duration specified, and vibrate for its own set duration. It also does not support vibrating in a pattern (it will not vibrate at all), nor cancelling a vibration in progress.

The project has been tested with version 2.1.5 of the plugin on the following devices:

 - iPhone X (iOS 11.1.1)
 - Nexus 5X (Android 8.0)
 - Galaxy S4 (Android 4.4.2)