*Please be aware that this application / sample is provided as-is for demonstration purposes without any guarantee of support*
=========================================================

## This repository is out of date - please refer to the updated 'getting started' guide at [https://github.com/darryncampbell/DataWedge-GettingStarted-Samples](https://github.com/darryncampbell/DataWedge-GettingStarted-Samples) 

# DataWedge-Intent-Example-3

This application shows how to receive barcode scans via an Intent through the DataWedge service on Zebra mobile computing devices **with a Xamarin application**.  Compare this with the [Previous example](https://github.com/darryncampbell/DataWedge-Intent-Example-1) which showed how this is done with an Android app.

## Preparation: Configure DataWedge
You need to configure DataWedge on your device to output scans via Intent
1. Launch DataWedge via Applications --> DataWedge
2. Select 'Profile0 (default)'.  Note that this is the default Profile DataWedge uses, if you have configured a profile specifically for this app then select that instead.
3. Ensure:
  * The Profile is Enabled
  * Barcode input is Enabled
  * Intent output is Enabled
4. Configure the Intent output as follows:
  * Intent action: com.dwexample.ACTION (This matches the value defined at https://github.com/darryncampbell/DataWedge-Intent-Example-3/blob/master/DatawedgeIntentExample3/Resources/values/Strings.xml)
  * Intent category: leave blank
  * Intent delivery: Broadcast intent
  * The following image shows the Intent output configuration
  
![Datawedge Configuration](https://raw.githubusercontent.com/darryncampbell/DataWedge-Intent-Example-3/master/screenshots/datawedge_settings.png?raw=true)

##  The application
Launch the application

![Application](https://raw.githubusercontent.com/darryncampbell/DataWedge-Intent-Example-3/master/screenshots/1.png?raw=true)

Scan a barcode.  The read barcode should be shown on the UI

![Application](https://raw.githubusercontent.com/darryncampbell/DataWedge-Intent-Example-3/master/screenshots/2.png?raw=true)

