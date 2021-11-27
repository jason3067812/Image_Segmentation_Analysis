# Image_segmentation_analysis

## Abstract
When the training data is insufficient, the AI model often has insufficient effect, so I want to make a post-processing algorithm to optimize the model prediction results.
## Introduction
This function can freely divide the image into blocks, rows, or columns and then compare each partition.
## Requirement
1. Python
2. Opencv
3. numpy
4. matplotlib

## Parameter setting
- mode="c" (r: row, c: column, b: block, number=0: preview mode)
- split=5  (How many pieces do you want to cut in total?)
- number=0 (The number of the partition that you want to show and analysis)
- plot="true

## Exhibition
![image](https://user-images.githubusercontent.com/56544982/143668338-29ed4278-5fd5-4b29-8f61-d69e12f92763.png)
![image](https://user-images.githubusercontent.com/56544982/143668344-a06bc8b5-4f39-45aa-b65a-8ed53243cd75.png)

##What next?

###You can...
1. comoare histogram

![image](https://user-images.githubusercontent.com/56544982/143668383-38367311-e909-4053-9e25-68c34882bed3.png)

2. comare similarity

![image](https://user-images.githubusercontent.com/56544982/143668371-53b4895f-fa0d-4bf3-a19c-9d8490b02316.png)


