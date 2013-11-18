macscripts
==========

Quick & Free Photo Resize that you can install on your girl-friend's laptop, or your granny's desktop.


Step 1: Download and install imagemagick from http://www.imagemagick.org/script/binary-releases.php#windows

Step 2: create a resize.bat file on the desktop, with the following line and save it.
    `for %%x in (%*) do convert -resize 800x600 %%x "%%~dx%%~px%%~nx_800x600%%~xx"`

    (OR, you can download resize.bat from this project)

Step 3: now you can drag and drop one or multiple files to this resize.bat, it will create resized photos in the original folder with `_800x600` in the name, say your photo is d:\a.png, the resized will be `a_800x600.png`


That's it!
