# Model-Comparision Report:
This Repositry contains a comparision of object detection models (Roboflow, YOLOv8, YOLOv10, Faster R-CNN)
# Model comparison: 
The models were evaluated using standard object detection metrics: mAP, Precision, and Recall. These metrics provided clear comparison of model performance. The following table summarizes the results. including the algorithm name, accuracy metrics, and the outcome of sample test image.

| Algorithm     | Accuracy metrics                                           | Test Image          
----------------|:----------------------------------------------------------:|-------------------
| Roboflow      |  mAP@50: 84.7% <br> Precision: 85.8% <br> Recall: 75.6%    |<img src="rb.png" alt="Roboflow" width="200"/>
|  YOLOv8       | mAP@50: 83.77% <br> Precision: 88.44% <br> Recall: 72.88%  |<img src="y8.png" alt="YOLO8" width="200"/>
| YOLOv10       | mAP@50: 73.86% <br> Precision: 77.12% <br> Recall: 64.25%  |<img src="y10.png" alt="YOLO10" width="200"/>   
| Faster R-CNN  | mAP@50: 80.45% <br> Precision: 37.72% <br> Recall: 47.12%  |<img src="cnn.png" alt="Faster R-CNN" width="200"/>

# best mosel Based on result : 
The Roboflow baseline achieved the best overall performance with balanced Precision and Recall. YOLOv8 was very close and had the highest Precision, but lower Recall. Faster R-CNN achieved an acceptable mAP but showed very low Precision and Recall, while YOLOv10 performed weaker overall. <br>
This means that the Roboflow bassline is the most accurate, followed by YOLOv8. <br> <br>
In conclusion, this comparison highlights each algorithm and the importance of evaluating model using multiple metrics rather than focusing on a single metrics.

      





