# Enhance the quality of a video by upscaling its resolution and reducing noise

Developed for assignment purpose

Step 1: On colab select the "T4 GPU" to work with this notebook.

Step 2: Import the necessary modules by running the first code block.

Step 3: Run the second code block to upload the input video manually into the notebook.

Step 4: Run the third code block to prepare and execute an FFmpeg command to extract frames from the input video and provide feedback about the extraction process.

Step 5: The fouth code block  is responsible for running ESRGAN (Enhanced Super-Resolution Generative Adversarial Network) on the extracted frames from the previous step to enhance the quality of the extracted frames using a specified model and options. The enhanced frames will be used to recreate the video.

Step 6: This final code block is responsible for recreating a video from the enhanced frames generated by ESRGAN

**Other details:**

Input data used: test1.mp4 from **"assignment demos"** drive folder

Frames are extracted form the input video. Total frames present in test1.mp4: _**823 frames**_

The obtained frames are applied with ESRGAN and the time taken to complete this operation is _**43 minutes**_

The processed frames are compiled into final video with **frame_rate=_24 fps_**

The time taken to generate the video is _**6 minutes 49 seconds**_

**Modules, Tools & Packages Used:**
google.colab : drive, files
os
shutil
subprocess
ffmpeg
git
basicsr
facexlib
gfpgan

