# YOLOV3 License Plate Detection

License Plate Detection with YOLO v3. Darknet-19 Architecture. With pre-trained weights.

# Setup 

Works only in **Unix** based operating systems.

```
python3 -m venv LicensePlateDetection
source LicensePlateDetection/bin/activate
pip install -r requirements.txt 
```

# Usage

```
# After activating the python virtual env
python predict.py --image demo.jpg
# This will automatically download all required pre-trained weights.
```
