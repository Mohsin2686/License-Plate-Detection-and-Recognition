# License-Plate-Detection-and-Recognition

This project combines YOLO (You Only Look Once) for cars and thlicense plate detection and PaddleOCR for optical character recognition to identify license plate numbers from images or video streams.

### Setup the environment

```bash
conda create -n license-plate-detection python=3.9
```
```bash
conda activate license-plate-detection
```

```bash
git clone https://github.com/Mohsin2686/License-Plate-Detection-and-Recognition.git
```

```bash
cd License-Plate-Detection-and-Recognition
```


```bash
pip install ultralytics
```

```bash
pip install paddleocr
```

For CPU (NON-GPU) user
```bash
pip install paddlepaddle --index-url https://pypi.org/simple
```
For CPU (NON-GPU) user
```bash
pip install paddlepaddle-gpu==2.5.2.post117 -f https://www.paddlepaddle.org.cn/whl/windows/mkl/avx/stable.html
```
For CUDA Version 11.2, change post117 to post112

## Running on input video
-Give the input video path in main.py

```bash
python main.py
```

output video will be stored in output_videos folder
                                                                                            
<video src="output_videos/output_video_license.avi" controls width="640"></video>

output_videos/output_video_license.avi