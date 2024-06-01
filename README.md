# yolov5 - TKO 

## Prerequisites

Make sure you have already on your system:

- Any modern UNIX OS (tested on Monterey 12.12.1)
- OpenCV 4.5.4+
- GCC 11.0+ 

IMPORTANT!!! Note that OpenCV versions prior to 4.5.4 will not work at all.


```bash
git clone https://github.com/any3zing/practice.git
cd practice
g++ -std=c++11 -O3 cpp/yolo.cpp -o yolo_example `pkg-config --cflags --libs opencv4`
./yolo_example
```

To change the example given in code, change a filename in yolo.cpp # practiceETU


Upload your model file (.onnx) to config_files.
