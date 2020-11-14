# Yolov5-Custom-MaskNoMask
Custom yolov5 model to detect masks

Special thanks to Jacob Solawetz at Roboflow.ai. I used this tutorial to train my custom yolov5s model:
https://towardsdatascience.com/how-to-train-a-custom-object-detection-model-with-yolo-v5-917e9ce13208
I chose the Mask Wearing dataset with black padding from Roboflow website:
https://public.roboflow.com/object-detection/mask-wearing/1

Some of the project directories shown in the tutorials are different than the ones I had. For example, I did not have a /content/yolov5/runs/exp_yolo5s_results directory (mine was /content/yolov5/runs/train/yolov5s_results). However, as long as you can navigate the drive directory the tutorial is a very useful reference. If you just want the weights that I attained from training for 1000 epochs and batch_size of 16 those are available here as well.
