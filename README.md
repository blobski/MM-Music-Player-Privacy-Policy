## MM Music Player: Privacy policy

Welcome to the MM Music Player app for Android!

This is an app written in Flutter. It is available to download on Google Play.

I hereby state, to the best of my knowledge and belief, that I have not programmed this app to collect any personally identifiable information. All data (app preferences (like theme, etc.) and music lists) created by you (the user) is stored on your device only, and can be simply erased by clearing the app's data or uninstalling it.

### Explanation of permissions requested in the app

<br/>

| Permission | Why it is required |
| :---: | --- |
| `android.permission.READ_EXTERNAL_STORAGE` and `android.permission.READ_MEDIA_AUDIO` | This is required for the app to read music files from your device and be able to list them to you. Former for Android 12 and lower, and latter for Android 13 and higher. |
| `android.permission.WRITE_EXTERNAL_STORAGE` | For you to be able to delete songs from the app. Used by Android 10 and lower. |
| `android.permission.WAKE_LOCK` and `android.permission.FOREGROUND_SERVICE` | Needed for background playback and system player (the one on the lock screen) to work properly. |
| `android.permission.REQUEST_IGNORE_BATTERY_OPTIMIZATIONS` | Optional. The app works fine without it, but you may grant it to be sure the system won\'t kill app while playing in background.|

 <hr style="border:1px solid gray">

If you find any security vulnerability that has been inadvertently caused by me, or have any question regarding how the app protectes your privacy, please send me an email at mirea2007@yandex.ru or post a discussion on GitHub, and I will surely try to fix it/help you.
