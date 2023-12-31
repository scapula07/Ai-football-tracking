

- Clone the repository


- Install the ultralytics package
```
pip install ultralytics
```

- For macos

  ```
    export PATH="/Library/Frameworks/Python.framework/Versions/3.10/bin:$PATH"
     /bin/chmod +x /usr/local/bin/yolo

  ```

- Do Tracking with mentioned command below
# video 
```
yolo task=detect mode=predict model=yolov8m-football.pt conf=0.25 imgsz=1280 line_thickness=1 source=test.mp4 show=true
```
```
yolo task=detect mode=predict model=yolov8s-football.pt conf=0.25 imgsz=1280 line_thickness=1 source=test.mp4 show=true
```




Get the model files here: https://drive.google.com/drive/folders/1AqfV35JcWXoxOOpAv8O_9wF57xmXbZVZ?usp=share_link
