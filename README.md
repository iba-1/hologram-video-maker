# Context info

This program is forked from [tcya/pseudo-hologram-video-maker](https://github.com/tcya/pseudo-hologram-video-maker). 
I just implemented threading to buffer frames following amazing [pyimagesearch.com article](https://www.pyimagesearch.com/2017/02/06/faster-video-file-fps-with-cv2-videocapture-and-opencv/) and updated some deprecated/old functions from opencv, now it's all working as intended. 
I had to implement FileVideoStream utils because longer and heavier video would simply take too much time to process, or either would fail or render with low fps/lost frames.

Just pip install dependencies and go for it!
