Girls' Frontline [EN]
Manual Patch

===================== Table of Contents

A. Pre-requisites
B. Instructions
C. Repair Archive
D. FAQ/Others
E. Contact
F. Disclaimer


===================== A. Pre-requisites

Windows: WinRAR v5.0 or later  [https://www.rarlab.com/]

Android: RAR  [https://play.google.com/store/apps/details?id=com.rarlab.rar]

ManualPatch[yyyy-mmdd]  [https://mega.nz/folder/nQFCTRzR#QiQcTkJq_BGY9IZMjrB1Vw]


===================== B. Instructions

1) Open archive in WinRAR.
2) Extract & Replace files to the following common path: (may vary slightly before \data\)

Android\data\com.sunborn.girlsfrontline.en\files\Android\New\


===================== C. Repair Archive

In case part of the archive is damaged, you may attempt to repair the file.
A damaged archive will usually fail to extract some files properly.
This archive file has a Recovery Volume for such cases.

WINDOWS
1) Open file in WinRAR (or select the file inside RAR).
2) Go to "Tools" > "Repair archive".
3) Change the output path if need be, and choose the "Treat the corrupt archive as RAR" radio button.
4) Press OK button to start repairing.
5) When finished, a new file will be created with the prefix "fixed."; this will be the repaired version of the archive file.
   Results log will also show how much damage was repaired, if any.

ANDROID
1) Open file in RAR (or select the file inside RAR).
2) Tap the vertically-aligned three dots on the top-right corner.
3) Tap "Repair archive".
4) Confirm prompt by tapping "OK".
5) When finished, a new file will be created with the prefix "fixed."; this will be the repaired version of the archive file.
   Results log will also show how much damage was repaired, if any.


===================== D. FAQ/Others

1Q) The size of GFL is increasing! (Exceeding 4GB or so)
1A) Delete the temporary downloaded files (*.dat & *.temp) left in the following game file location:

Android\data\com.sunborn.girlsfrontline.en\files\Android\New\

2Q) Am I in the right "New" folder?
2A) The directory tree of the target working folder should look something like the following:

Internal storage (/storage/emulated/0)
- Android
  - data
    + com.app
    + com.some.app
    + com.some.other.app
    - com.sunborn.girlsfrontline.en
      + cache
      - files
        + activity
        + AIHlepSDK
        - Android
          + New        <-- This is the folder we should be working in
        + cartoon
        + il2cpp
        + stc
        + Unity
        + UnityCache
    + com.yet.another.app
  + obb

3Q) I play GFL in an iOS device. Is there a workaround for when I encounter the "Insufficient Memory" error or when the app size bloat up more than 4GB?
3A) Unfortunatley there is no known workaround for iOS devices. You will have to repeatedly Clear Cache in-game after several attempts of patching.


{to add more later}


===================== E. Contact

Girls' Frontline EN Official Discord Server #gf-ask-help  [https://discord.gg/gfen]

Discord Amanie#7511

Twitter @lloyd_dunamis


===================== F. Disclaimer

The latest version of this document will always be in [https://github.com/lloyddunamis/gfl_manualpatch].

Special Thanks:
  Arloste
  GFL EN Discord Helpers
  Ceia


This Girls' Frontline [EN] Manual Patch was made for personal use, and it worked for me like a charm.
It is then provided to the community as-is in case it helps anyone else.
Due to differences in configurations and the like, your mileage may vary.
No warranty provided; Use at your own risk.
Though do let me know, as we might be able to fix or work around what makes it not work.
Worst case possible, you'd still have to Clear Cache/Uninstall anyway.

This is not an official product from, nor is officially endorsed by, Sunborn / MICA Team.
