# People Counter using Object Detection (20201012 ~ 20201106)
- This project is designed to count people in study room images for seat reservation system.
- This repo is maintained by [최우철](https://github.com/choiwoochul), 오서영, [허지혜](https://github.com/jihyeheo), [이수빈](https://github.com/I-SUBIN)  

[[Presentation]](https://github.com/OH-Seoyoung/People_Counter_using_Object_Detection/blob/master/presentation.pdf)  

## Architecture
### CNN | [[Code]](https://github.com/OH-Seoyoung/People_Counter_using_Object_Detection/blob/master/CNN_for_counting_people/People_counter_with_baseline_CNN.ipynb)  
- Simple Classifier with a softmax output layer comprising 11 output nodes.  

### YOLO-v3 | [[Code]](https://github.com/OH-Seoyoung/People_Counter_using_Object_Detection/blob/master/YOLO-v3_test/yolo_opencv.py)  
#### Test with Pretrained Model
- We use the pre-trained YOLO-v3 weights by Ali Farhadi

## Dataset  
- We test YOLO-v3 with 647 real-time cctv images of Department of Mathematics Lecture room

## Reference
```
[1] Counting Objects using YOLOv3, https://github.com/Raj-Shah1/Counting-Objects-using-YOLOv3
[2] YOLO: Real-Time Object Detection by Ali Farhadi, https://pjreddie.com/darknet/yolo/
```
