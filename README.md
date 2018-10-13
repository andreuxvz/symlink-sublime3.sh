# Creating a symlink for Sublime3 on macOs High Sierra v.10.13.*
As you know sometimes as a developer I'd  like too much to open Sublime v3 from terminal also use other commands... 
I've been reading many posts  trying to create a symlink with any succes, cause many of them told me to create a symlink in forbidden directories
like:
/bin
/usr/bin


and the following folders are free:
/Applications
/Library
/usr/local

here is the command:  \n
<b> ln -s "/Applications/Sublime Text.app/Contents/SharedSupport/bin/subl" /usr/local/bin/subl <b>  

so... what I've done its make my symlink for Sublime in /usr/local/bin directory and it works.
Hoping it helps u GUYS. :)

You can read more about System Integrity Protection on your Mac and Configuring System Integrity Protection.
https://developer.apple.com/library/archive/documentation/Security/Conceptual/System_Integrity_Protection_Guide/ConfiguringSystemIntegrityProtection/ConfiguringSystemIntegrityProtection.html#//apple_ref/doc/uid/TP40016462-CH5-SW1
