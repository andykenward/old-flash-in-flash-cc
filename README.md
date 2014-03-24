old-flash-in-flash-cc
=====================

To compile for Flash Player 9 / 10.1 / 10.2 using Flash CC (13.1.0.226)

Thanks to this blog [post](http://blog.teamthinklabs.com/index.php/2013/11/22/compile-for-flash-player-9-using-flash-cc/)

You can download v9 'playerglobal.swc' from [here](http://staging.seven2.net/s2/test/Flash_Player_9.zip) (does adobe host this file anywhere?)

You can download v10.1 & v10.2 'playerglobal.swc' from [here](http://helpx.adobe.com/flash-player/kb/archived-flash-player-versions.html)


For MAC
Go to this folder on your hard drive. Make sure your right click and show package on the '.app' file to get there

'/Applications/Adobe Flash CC/Adobe Flash CC.app/Contents/Common/Configuration/ActionScript 3.0'

Put the relative '.swc' file into the correctly named new folder. Make sure they are named 'playerglobal.swc' in the folder.

'FP9'
'FP10.1'
'FP10.2'

Then go to
'/Applications/Adobe Flash CC/Adobe Flash CC.app/Contents/Common/Configuration/Players'

copy the .xml files which are in this git

FlashPlayer9_0.xml
FlashPlayer10_1.xml
FlashPlayer10_2.xml

You should now be able to compile to these versions.

Be careful when there is a update to Flash CC since you last did this it might overwrite/delete these files.

The structure of the xml files might change over time so this might stop working. Hopefully people will submit issues/pulls to solve the issue or adobe will add this themselves.

I would put the '.swc' files on here but not sure I legally can at the moment.