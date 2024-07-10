## Inference
classes:
``` shell
0:helmet
1:nohelmet
2:jumpsuit
3:nojumpsuit
4:person
``` 

On video:
``` shell
python detect.py --weights yolov7.pt --conf 0.25 --img-size 640 --source yourvideo.mp4
```

On image:
``` shell
python detect.py --weights yolov7.pt --conf 0.25 --img-size 640 --source inference/images/horses.jpg
```
on specific classes:
``` shell
python detect.py --weights yolov7.pt --conf 0.25 --img-size 640 --source inference/images/horses.jpg --classes 0,1,2,3,4
```
