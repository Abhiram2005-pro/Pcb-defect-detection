# Pcb-defect-detection
```md
## PCB Defect Detection Using Contrastive Learning for Edge Devices

This research focuses on developing an efficient and accurate automated PCB defect detection system for modern electronics manufacturing. Traditional inspection methods are often time-consuming, error-prone, and difficult to scale for high-volume production environments. To address these challenges, we proposed a lightweight deep learning framework that combines the real-time object detection capabilities of YOLOv11 with SimCLR-based contrastive self-supervised learning.

The proposed approach first leverages contrastive learning to learn rich visual representations from unlabeled PCB images, enabling the model to capture subtle defect-specific patterns such as missing holes, open circuits, short circuits, spurs, mouse bites, and spurious copper. These learned representations are then transferred to a customized lightweight YOLOv11 detector, improving feature discrimination and detection accuracy while reducing computational requirements.

To make the model suitable for deployment on resource-constrained edge devices, the YOLOv11 architecture was optimized by reducing its depth, width, and channel complexity, resulting in a 43.3% reduction in parameters and a 28.1% reduction in computational cost compared to the standard YOLOv11n model. Experimental evaluation on the Peking University PCB Defect Dataset demonstrated that the proposed framework achieved a mAP@0.5 of 98.71%, precision of 98.01%, and recall of 98.08%, outperforming baseline models while maintaining high efficiency.

The results show that integrating contrastive self-supervised learning with lightweight object detection can significantly improve defect detection performance and generalization while enabling real-time deployment in industrial inspection systems. This work contributes toward building intelligent, scalable, and cost-effective quality assurance solutions for next-generation electronics manufacturing.
```
