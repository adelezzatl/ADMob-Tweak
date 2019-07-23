# ADMob-Tweak
this project is example for add ADs in WhatsApp

## you must be do this steps in your IPA file before add dylib:
# Update your Info.plist:

 - In your app's ```Info.plist``` file, add a ```GADApplicationIdentifier``` key with a string value of your AdMob app ID. You can [find your App ID](https://support.google.com/admob/answer/7356431) in the AdMob UI.
 
 - You can make this change programmatically:
 ``` plist
 <key>GADApplicationIdentifier</key>
<string>ca-app-pub-3940256099942544~1458002511</string>
```
- Or, edit it in the property list editor:
![](https://github.com/BandarHL/ADMob-Tweak/blob/master/admob_app_id_plist.png)
