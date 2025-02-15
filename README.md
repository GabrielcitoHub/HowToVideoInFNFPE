# HowToVideoInFNFPE
This will teach ya how to play a video or something
# So first things first you need ffmpeg installed, download it
ok now open cmd and go to the folder with your mp4 video
name the video 'video' and input this command:
``
ffmpeg -i video.mp4 frame_%04d.png
``

## now that that's done you now have you video on frames, yay! (it may take a while so you just wait until it says something like finished idk)
create a folder for the frames and move it to images on your mod
now place the script above in your song and open it with a codeeditor like vsc or notepad++ (yes notepad works too)
## change the variable videoPath to your actual videoframes path, 'images/<framesfoldername>'
now you can set the variable playing to 1 to play the video, use this script do to the actual coding
enjoy! :)
