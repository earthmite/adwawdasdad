To begin installation, you must install NodeJS first. You can find the NodeJS download [here.](https://nodejs.org/en/)

After that, if prompted to restart, it is recommended to do so.

# FFmpeg

After installing NodeJS, you need to download FFmpeg next. If you're on Windows 64 bit, you can use [this.](https://github.com/BtbN/FFmpeg-Builds/releases/download/latest/ffmpeg-master-latest-win64-gpl-shared.zip) If you're on Mac, install FFmpeg from Brew. If none of these fit you, you can search for your own FFmpeg version [here.](https://github.com/BtbN/FFmpeg-Builds/releases)

Unzip the folder, move it to your downloads and then rename it to "ffmpeg".

Right click the folder, select "Cut", direct to This PC, enter your C: drive and paste the ffmpeg folder in there.

After moving the ffmpeg folder into your C: drive, open Command Prompt with administrator and run this: setx /m PATH "C:\ffmpeg\bin;%PATH%"

After you get a success message, type in "ffmpeg" to the command prompt. If you get an error, you need to restart your computer, once finished restarting, run ffmpeg inside of the command prompt window once more, and if you do not get an error you're all set.

