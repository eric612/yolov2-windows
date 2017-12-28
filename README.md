# Yolo-Windows v2 - 

**This is an experimental,clone from https://github.com/unsky/yolo-for-windows-v2
and I add following items into project 
1. migrate opencv_2.4.9 to opencv_3_3_0
2. add pre-build opencv library (NO CUDA)

# Testing and Training

the same as [yolo windows](https://github.com/unsky/yolo-for-windows-v2)

# OPENCV 3.3.0

This version is no longer support non optimization on pure [c api](https://github.com/opencv/opencv/issues/10246), this is why this project can't build debug
,if you want set to debug mode , I suggest you use orginal project and OPENCV_2.4.9, or you can just remove define "OPENCV"

