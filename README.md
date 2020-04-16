[//]: # (Image References)

[image1]: ./static/images/x_ray_examples.JPG "Labeled Chest Xray Examples"
[image2]: ./static/images/JobLaunch.JPG "Results"

## AI Product Management: Create a Medical Image Annotation Job

![Labeled Chest Xray Examples][image1]


## General Project Details

Design of a data annotation job using Figure-Eight's platform that uses non-experts to identify and label cases of pneumonia.
This data would later be used to build an AI product that helps health professionals quickly identify cases of pneumonia in children. This data would be used to build a classification system that (not done here):
- Can help flag serious cases
- Quickly identify healthy cases
- And, generally, act as a diagnostic aid for doctors

To be clear, the goal of this project is data labeling, not machine learning. One responsibility of an AI product manager may include obtaining a labeled dataset using third-party software such as Figure-Eight or AWS.

This annotation was launched, and the results and learnings are discussed below, with output objects provided. (Additional project results and modeling are also noted below in **Related Projects**.)

## Proposal and Final Project Paper

**Problem Statement**: The aim is to design a annotation job that labels x-ray data as pneumonia or healthy, using Figure-Eight platform at https://www.figure-eight.com/. This will allows for instructions, test questions, and overall design.

**Evaluation**: Accuracy is our test metric for the 16 images that are labeled. We are also looking for accurate results among the distribution of answers for yes/no for the labeled test cases.

## Data
Original Data: https://www.kaggle.com/paultimothymooney/chest-xray-pneumonia.

As, applicable, see directories "static" for supporting data/files, and "templates" for HTML templates.

## Outputs
- A pdf **Proposal**, which is a writeup that details design considerations and strategies for quality assurance.
- A **jupyter notebook** for exploratory data analysis, reviewing images, and any data science related preparation.
- **Instructions_Preview.html** designed on Figure-Eight. The file includes instructions, examples, and some sample test questions.
- A pdf **Figure Eight Launch Results**
- **Results.CSV** - the resulting labeled dataset

## Job Launch Results Overview
![Results][image2]

## Discussion
This experiment stresses the need for testing job launches, and having clear design, instruction, and test questions.
If a full job had been launched without testing, higher costs would have been incurred (we were 76% over our budget of 25$).
As such, it is incredibly important to treat this test as a soft-launch to eliminate bugs, and create a great design, iteratively, before moving forward with a full-scale annotation job. Also, monitoring the progress is certainly worthwhile to ensure strong results (accurate data labels) and limit costs.

## Related Projects
This repository also contains two additional projects that were completed during this Nanodegree:
- **AutoML_Modeling_Report**: this is a report documenting various models made on Google's AutoML using the X-Ray dataset. Discussed topics such as imbalance data, dirty data, and data size. Discussion of the effects on key metrics are reported.
- **AI Product Business Case - Physical Therapy**: this project is a AI product business case and design, considering users, collaborators, data sources, design practices, AI, and iteration over time.

## Motivation
Learn AI Product Management for a wholistic understanding of successful product management, and its application beyond the data science life cycle.  

## Requirements
See the requirements.txt file for necessary packages.

## License
### The MIT License (MIT)
### Copyright (c) 2020 Ben Jacobson
```
Permission is hereby granted, free of charge, to any person obtaining a copy of this software and associated documentation files (the "Software"), to deal in the Software without restriction, including without limitation the rights to use, copy, modify, merge, publish, distribute, sublicense, and/or sell copies of the Software, and to permit persons to whom the Software is furnished to do so, subject to the following conditions:
The above copyright notice and this permission notice shall be included in all copies or substantial portions of the Software.
THE SOFTWARE IS PROVIDED "AS IS", WITHOUT WARRANTY OF ANY KIND, EXPRESS OR IMPLIED, INCLUDING BUT NOT LIMITED TO THE WARRANTIES OF MERCHANTABILITY, FITNESS FOR A PARTICULAR PURPOSE AND NONINFRINGEMENT. IN NO EVENT SHALL THE AUTHORS OR COPYRIGHT HOLDERS BE LIABLE FOR ANY CLAIM, DAMAGES OR OTHER LIABILITY, WHETHER IN AN ACTION OF CONTRACT, TORT OR OTHERWISE, ARISING FROM, OUT OF OR IN CONNECTION WITH THE SOFTWARE OR THE USE OR OTHER DEALINGS IN THE SOFTWARE.
```
