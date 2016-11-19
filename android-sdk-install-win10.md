android-sdk-install-win10.md  
============================ 
   
### Prereq  
==========  
    # java  
    https://www.java.com/en/download/win10.jsp  
    #  
    
    
    # other
    https://developer.android.com/studio/command-line/adb.html
    http://forum.xda-developers.com/devdb/project/?id=1314#downloads
    http://www.nexus7tablethelp.com/2012/08/adb-full-backuprestore-nexus7-without.html?m=1
    http://www.htcdev.com/devcenter/downloads
    
    
    
    # * How to perform a full system backup.

    # Command parameters format: adb backup [-f <file>] [-apk|-noapk] [-shared|-noshared] [-all] [-system|nosystem] [<packages...>]

    # * Start doing N7 backup by using the command:
    adb backup -apk -shared -all -f C:\n7-full-backup.ab
    # * It should ask if you want to. Touch "Back up my data". 


    # * to restore everything, 
    adb restore C:\n7-full-backup.ab
    # Then tap "Restore my data" on your N7 to start.


