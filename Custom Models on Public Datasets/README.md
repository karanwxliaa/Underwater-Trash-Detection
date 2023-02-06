### This folder contains progress of developing models for already existing **Datasets** like
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
#### RESULTS
![image](https://user-images.githubusercontent.com/95328038/216962186-ef6e15d0-28c6-4da1-be5c-832895c6f563.png)


## YOLOv5s
PROS: Good detection, Acceptable Accuracy.
CONS: Training required high amount of GPU RAM (11.8GB) therefore high computation cost.

![image](https://user-images.githubusercontent.com/95328038/216963438-080cd596-7eb3-41c4-836d-3bcdc461bdf6.png)
![image](https://user-images.githubusercontent.com/95328038/216963461-53d66881-dad9-470a-99a6-cb1912ae6a50.png)
#### RESULTS
![image](https://user-images.githubusercontent.com/95328038/216963490-991378d1-cd98-44f0-b4c8-6377a9642eb6.png)

![image](https://user-images.githubusercontent.com/95328038/216963385-51a7b7f0-1d28-4798-8daf-6857fad77df3.png)


## RCNN
PROS: Acceptable Detection of trash but bad segregation.
CONS: Poor Accuracy, Outdated, High train time.

![image](https://user-images.githubusercontent.com/95328038/204123052-6e0a0106-82e5-4804-8600-7549e67226b9.png)
![image](https://user-images.githubusercontent.com/95328038/204123064-2b195c5c-dd84-4aa9-9ce1-10fc1032397e.png)



