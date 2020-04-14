[//]: # (Image References)

[image1]: ./static/images/xray.JPG "Labeled Healthy Chest Xray"
[image2]: ./static/images/JobLaunch.JPG "Results"

## AI Product Management: Create a Medical Image Annotation Job

![Labeled Healthy Chest Xray][image1]


## General Project Details

Design a data annotation job using Figure-Eight platform that uses non-expert to identify and label cases of pneumonia. 
This data could later be used to build a product that helps doctors quickly identify cases of pneumonia in children. This data would be used to build a classification system that (not done here): 
- Can help flag serious cases
- Quickly identify healthy cases
- And, generally, act as a diagnostic aid for doctors

To be clear, this goal of this project is data labeling, not machine learning. One responsibility of an AI product manager may include obtaining a labeled dataset using third-party software such as Figure-Eight or AWS. 

## Proposal and Final Project Paper

Problem Statement: The aim is label x-ray data as Pneumonia or healthy, using FigureEight platform at https://www.figure-eight.com/. This will allows for instructions, test questions, and overall design.
Evaluation: Accuracy is our test metric for the 16 images that are labeled. We are also looking for accurate results among the distribution of answers for yes/no.

## Requirements
See the requirements.txt file for necessary packages. 

## Data
Original Data: https://www.kaggle.com/paultimothymooney/chest-xray-pneumonia
As, applicable, see directories "static" for supporting data/files, and "templates" for HTML templates.

## Outputs
- A pdf **Proposal**, which is a writeup that details design considerations and strategies for quality assurance.
- A jupyter notebook for exploratory data analysis, reviewing images, and any data science related preparation.
- Instructions_Preview.html designed on Figure-Eight. The file includes instructions, examples, and some sample test questions.
- A pdf **Figure Eight Launch Results**
- **Results.CSV** - the resulting labeled dataset 

![Results][image2]

## Discussion
This experiment stresses the need for testing job launches, and having clear design, instruction, and test questions. 
If a full job had been launched without testing, higher costs would have been incurred (we were 76% over our budget of 25$). 
As such, it is incredibly important to treat this test as a soft-launch to eliminate bugs, and create a great design, iteratively.  

## Motivation
This is to learn AI Product Management, through the Udacity AI Product Manager Nanodegree. 

## Other Related Projects
This repository also contains two additional projects from the same program.
- **AutoML_Modeling_Report**: this is a report documenting model in Google's AutoML, and discussed topics such as imbalances, dirty data, and data size. Discussion of the effects on key metrics are reported.
- **AI Product Business Case - Physical Therapy**: this project is a AI product business case and design, considering users, data source, design practices, and iteration over time.

## License
### The MIT License (MIT)
### Copyright (c) 2020 Ben Jacobson
```
Permission is hereby granted, free of charge, to any person obtaining a copy of this software and associated documentation files (the "Software"), to deal in the Software without restriction, including without limitation the rights to use, copy, modify, merge, publish, distribute, sublicense, and/or sell copies of the Software, and to permit persons to whom the Software is furnished to do so, subject to the following conditions:
The above copyright notice and this permission notice shall be included in all copies or substantial portions of the Software.
THE SOFTWARE IS PROVIDED "AS IS", WITHOUT WARRANTY OF ANY KIND, EXPRESS OR IMPLIED, INCLUDING BUT NOT LIMITED TO THE WARRANTIES OF MERCHANTABILITY, FITNESS FOR A PARTICULAR PURPOSE AND NONINFRINGEMENT. IN NO EVENT SHALL THE AUTHORS OR COPYRIGHT HOLDERS BE LIABLE FOR ANY CLAIM, DAMAGES OR OTHER LIABILITY, WHETHER IN AN ACTION OF CONTRACT, TORT OR OTHERWISE, ARISING FROM, OUT OF OR IN CONNECTION WITH THE SOFTWARE OR THE USE OR OTHER DEALINGS IN THE SOFTWARE.
```