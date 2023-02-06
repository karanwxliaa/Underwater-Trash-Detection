### This folder contains progress of developing models for already existing datasets like
-TrashCAN 1.0 (instance version & material version)
-Trash_ICRA19
-New-Plastic-Test - v5 final-test-dataset
-Fish.v1-416x416

This subfolder also shows the progress of development of the final model over time (bottom to top)

# Models used
Aiming at the problem of insufficient storage space and limited computing ability of underwater mobile devices, an underwater garbage detection algorithm is proposed.

## Yolo V6s
PROS: Acceptable accuracy, Good detection.
CONS: High Computation time, Couldnt detect properly from real-life unseen data (overfit due to training data's size, captured too much noise from each image)
![ezgif-3-f0d401d26c](https://user-images.githubusercontent.com/95328038/216822228-72bc3f07-26ae-40cd-9aac-05f9b787a606.gif)
![ezgif-3-9af446a05c](https://user-images.githubusercontent.com/95328038/216822609-e710d82a-49a4-49a9-ac3f-4ba785758442.gif)


## YOLOv5s
PROS: Good detection, Acceptable Accuracy.
CONS: Training required high amount of GPU RAM (11.8GB) therefore high computation cost.
![image](https://user-images.githubusercontent.com/95328038/208173120-b0b82a10-3c34-4f2e-bba3-f815c5a2ac67.png)
![image](https://user-images.githubusercontent.com/95328038/208173150-08a04c72-4c7c-420d-bae2-fe404c4af683.png)
![image](https://user-images.githubusercontent.com/95328038/208173203-d620b2b7-1953-4e6f-aaa2-96d0adc95bdf.png)


## RCNN
PROS: Acceptable Detection of trash but bad segregation.
CONS: Poor Accuracy, Outdated, High train time
![image](https://user-images.githubusercontent.com/95328038/204123052-6e0a0106-82e5-4804-8600-7549e67226b9.png)
![image](https://user-images.githubusercontent.com/95328038/204123064-2b195c5c-dd84-4aa9-9ce1-10fc1032397e.png)



