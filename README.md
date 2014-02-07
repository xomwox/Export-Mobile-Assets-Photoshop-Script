Export-Mobile-Assets-Photoshop-Script
=====================================

Flexible and powerful Photoshop script for exporting assets for Android and iOS projects.

// This script outputs iOS & Android PNG assets from XHDPI/RETINA source files in PSD or PNG format. 

// The resulting PNGs will be placed in sub-folders within your target folder.


## Install

1. Download the .jsx file.

2. Move the .jsx file to your Photoshop scripts folder. 


## Usage

1. Open Adobe Photoshop CS6 (32 & 64 bits)
2. Go to File > Scripts > Export Mobile Assets
3. Confirm if you want to delete your source files after process.
4. Select your source PSD or PNG files
4. Wait

## Result

This is the directory structure you will end up with following the instructions in the Usage Guide.

```
/android
    /res
        /drawable-xhdpi/{filename}.png
        /drawable-hdpi/{filename}.png    
        /drawable-mdpi/{filename}.png
        /drawable-ldpi/{filename}.png
    
/ios
    /iphone/{filename}.png
    /iphone_retina/{filename}@2x.png
    /ipad/{filename}~ipad.png
    /ipad_retina/{filename}@2x~ipad.png

