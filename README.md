## DocumentScanner
* A python3 based Document Scanner that uses multiple computer vision algorithms for result optimizations.
* (The project still has some minor bugs that needs to be fixed. Eg: Correct Resolution of the output window is not yet fixed. An option to save the video scanned is yet to be corrected. DO report errors and bugs if experienced.)

* The audio in the video file used here is removed by this command:
``` bash
ffmpeg -i input_file.mp4 -vcodec copy -an output_file.mp4
```
