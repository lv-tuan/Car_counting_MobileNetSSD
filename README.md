# Car counting with OpenCV and Deep Learning

<p align = "center"><img src="./processe_video.gif" width = 1024></p>

## Set up environment
```bash
cd Car_counting
.env\Scripts\activate.bat
pip install -r requirement.txt
```

## Run run the script

Without saving processed footage:
```bash
python car_counting.py -v test_video.mp4
```

Saving processed footage:
```bash
python car_counting.py -v test_video.mp4 -s True
```
## Set of flags

```
optional arguments:
  -h, --help            show this help message and exit
  -v VIDEO, --video VIDEO
                        Path to input video
  -c CONFIG, --config CONFIG
                        Path to the input configuration file
  -s SAVE, --save SAVE  Save processed video (True/False)
```

## Credit
[Adrian Rosebrok-Pyimagesearch](https://www.pyimagesearch.com/2019/12/02/opencv-vehicle-detection-tracking-and-speed-estimation/)

## License
[MIT License](./LICENSE)