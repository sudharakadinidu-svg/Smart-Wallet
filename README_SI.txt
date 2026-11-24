SMART WALLET - Android APK project

මෙය කලින් හදපු Smart Wallet HTML app එක Android WebView app එකක් ලෙස පැකේජ් කරපු Android Studio project එකයි.

APK එක හදාගන්න:
1. පරිගණකයක Android Studio install කරන්න.
2. Android Studio > Open තෝරලා මේ ZIP එක extract කළ folder එක තෝරන්න.
3. Gradle sync ඉවර වෙනකම් ඉන්න. Android SDK Platform 35 ඉල්ලුවොත් install කරන්න.
4. Build > Build Bundle(s) / APK(s) > Build APK(s) තෝරන්න.
5. APK එක app/build/outputs/apk/debug/app-debug.apk යටතේ ලැබේ.
6. APK එක phone එකට copy කර install කරන්න. අවශ්‍ය නම් Android Settings තුළින් මේ source එකෙන් install කිරීමට අවසර දෙන්න.

දැනගත යුතු දේ:
- මෙය Android WebView wrapper එකක්; HTML app එකේ පහසුකම්ම අඩංගුයි.
- දත්ත app එකේ local browser storage තුළ පවතී. App data clear/uninstall කළොත් දත්ත නැතිවිය හැක. Backup එකක් export කර තබාගන්න.
- Gmail login, Firebase cloud sync, online backup තවම සම්බන්ධ කර නැහැ.
- මෙහි APK binary එකක් නොව Android Studio source project එකක් අඩංගුයි; APK එක build කළ යුතුයි.
