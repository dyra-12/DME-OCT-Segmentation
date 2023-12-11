# DME-OCT-Segmentation

In the field of ophthalmology, precise diagnosis is critical, and Optical Coherence Tomography (OCT) imaging plays a pivotal role in identifying conditions such as Diabetic Macular Edema (DME). The objective of this study was to improve the accuracy of DME detection by employing advanced segmentation techniques, specifically U-Net and Mask RCNN.

The investigation focused on the intricate world of OCT images, emphasizing the need for meticulous segmentation to enhance disease identification and monitoring. Early detection of DME is crucial for diabetic patients to prevent vision impairment, making a reliable detection system essential.

In this study, the researchers proposed the use of Mask RCNN and U-Net models for DME detection. A comparative analysis of performance metrics, including IOU score, Dice coefficient, F1 score, and pixel accuracy, revealed a notable trend. The U-Net architecture consistently outperformed Mask RCNN across these metrics, indicating its efficacy in precise segmentation for DME detection.

<h3>Key Performance Metrics (Model 1 vs. Model 2):</h3>
<ul>
<li>Training Accuracy: 0.996 vs. 0.9858</li>
<li>Testing Accuracy: 0.9962 vs. 0.9808</li>
<li>Pixel Accuracy: 0.9905 vs. 0.9828</li>
<li>IOU Score: 0.712 vs. 0.1503</li>
<li>Dice Coefficient: 0.83145 vs. 0.2077</li>
<li>Precision: 0.999 vs. 0.992</li>
<li>Recall: 0.980 vs. 0.722</li>
</ul>
The higher values for IOU score, Dice coefficient, F1 score, and pixel accuracy observed with the U-Net model highlight its effectiveness in precise segmentation for DME detection.
