Fetus Heartbeat Detector
-------------------------------

To test the code, you need to have to be able to run the OpenCV app.

When the code is running, you may have to configure the trackbar of the thresholded video.
It is important to configure, because it depends on your configuration.
You will notice the video (Thresholded) will changed by the trackbar.

-------------------------------
Algorithms
-------------------------------
The program outputs fivewindows : Edges, Thresholded, Original, CMD, Frame and HSV windows.

- The Original windows itself shows the original video which is the Ultrasonography video.
- The Edges windows use the canny filter. (Note : it is just for the Non-Functionality Requirements).
- The HSV windows use the HSV filter for the video. (Note : it is just for the Non-Functionality Requirements).
- The Thresholded video is a formatted output file that is used for the detector. 
- The CMD windows is used for finding the coordinate of the video. (Point it with mouse on the video and you will see the coordinates in the CMD).
- Lalu akan menghasilkan 1 lagi windows yang akan mengeluarkan gambar yang diambil berupa frame by frame, sehingga akan
  menghasilkan kesan video yang lebih lama, atau slow motion. (Note : it is just for the Non-Functionality Requirements).
