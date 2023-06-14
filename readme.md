# Migrating to the Jetson Nano environment
<p>I have forked the repository from Satwik who added ocr to the Yolov8 models I trained. I have made edits to run on the Jetson nano.</p>

## Pre-requisites
<p> Before cloning the repository make sure that you have set up the Jetson nano environment properly . Follow this repo with step by step instuctions before following this repository:<br>
  https://github.com/Sanjiv-B-N/jetson-nano-setup <br> </p>
  
## Running this on the Jetson Nano

<p>Clone this repository. The move into the directory and run the following on the command line: <br> <br>
  
 pip3 install -r requirements.txt<br>
  
 python3 inference_yolov8n.py<br>
 python3 inference_yolov8s.py<br>
  
  </p>
