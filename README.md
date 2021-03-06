# Image segmentation analysis

## Abstract
When the training data is insufficient, the AI model often has insufficient effect, so I want to make a post-processing algorithm to optimize th character recognition system.

## Introduction
This code can freely divide the image into blocks, rows, or columns and then compare each partition.

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

<img src="https://user-images.githubusercontent.com/56544982/143672428-bab1f323-0afb-4b7a-8b5c-ecbcd3c2e2cf.png" alt="Cover" width="60%"/>

<img src="https://user-images.githubusercontent.com/56544982/143672410-d3edf6f1-6e4a-45f9-85c8-bba129cd8887.png" alt="Cover" width="60%"/>

## What's next?

### You can...
1. Compare histogram

<img src="https://user-images.githubusercontent.com/56544982/143668383-38367311-e909-4053-9e25-68c34882bed3.png" alt="Cover" width="60%"/>

2. Compare similarity

<img src="https://user-images.githubusercontent.com/56544982/143668371-53b4895f-fa0d-4bf3-a19c-9d8490b02316.png" alt="Cover" width="60%"/>

### My method

First compare brightness and then set them into three level. Finally, compare the similarity.

- Brightness classification:

<img src="https://user-images.githubusercontent.com/56544982/143669900-6143bda7-0cf1-4b2c-97eb-ad9626a0502c.png" alt="Cover" width="60%"/>

- Whole algorithm flow chart:

<img src="https://user-images.githubusercontent.com/56544982/143669871-87f53746-273f-4519-a118-4ad24cc5f23b.png" alt="Cover" width="60%"/>



