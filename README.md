# Old readme

This is a program converting video to the form suitable for [pseudo-hologram projection](http://www.telegraph.co.uk/technology/mobile-phones/11780393/How-to-turn-your-phone-into-a-3D-hologram-projector.html). It has been deployed on [PythonAnywhere](http://tcya.pythonanywhere.com/) for direct use. For details, please see there.


# New readme

This program is forked from [tcya/pseudo-hologram-video-maker](https://github.com/tcya/pseudo-hologram-video-maker). I just implemented threading to buffer frames following amazing [pyimagesearch.com article](https://www.pyimagesearch.com/2017/02/06/faster-video-file-fps-with-cv2-videocapture-and-opencv/). I had to implement FileVideoStream util because longer and heavier video would simply take too much time to process, or either would fail or render with low fps/lost frames.

Just pip install dependencies and go for it!
