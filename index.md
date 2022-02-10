<!---
**Project Description:**

I will focus on creating neural network (NNs) that is able to accurately detect breast cancer from tissue images. There are many publicly available datasets of tissue images available online. Each pixel in the tissue image will be classified as "nucleus", "boundary", or "not nucleus and not boundary". After this classification, the neural network will then create a black and white image of only the nuclei. 

After segmenting the nuclei, features need to be computed. I envision using features like the nuclei's shape, area, and perimter. Nuclei in tissue images of an invasive breast cancer lesion will be larger and more distorted than nuclei in normal tissue images. By computing these features, the neural network will be able to predict when a tissue image is normal or when it shows the presence of a breast cancer lesion. 

Here is an example of a benign tissue image. 
<img src="benign.JPG" alt="benign" width="300"/>

Here is an example of an invasive tissue image.
<img src="invasive.JPG" alt="invasive" width="300"/>

The main goal of this project is to create a tool that helps doctors during their diagnoses. Doctors will be able to check their diagnoses of a patient's tissue sample. This tool will be extremely helpful in making sure that doctors do not misdiagnose a patient or even recommend treatment when no treatment is needed. 


**Project Goals:**
1. Create a neural network that segments each pixel into nucleus, boundary, or not nucleus and not boundary.
2. Compute various features.
3. Train the NN to be able to detect invasive vs. benign breast cancer lesions by looking at tissue images. 
-->

**Introduction Outline:**
1. Introductory paragraph: What is the problem and why is it relevant to the audience attending THIS CONFERENCE? Moreover, why is the problem hard, and what is your solution? 

Classifying breast cancer tissue images by hand takes a lot of time and can be inaccurate.

2. Background paragraph: Elaborate on why the problem is hard, critically examining prior work, trying to tease out one or two central shortcomings that your solution overcomes.

3. Transition paragraph: What keen insight did you apply to overcome the shortcomings of other approaches? Structure this paragraph like a syllogism: Whereas P and P=>Q, infer Q.

Many previous attempts only used a few layers, so we hope to improve on their work by using more layers for our neural network. 

4. Details paragraph: What technical challenges did you have to overcome and what kinds of validation did you perform?

Some of the challenges we forsee are time limitations in our algorithm, as well as difficulties in the size of the images. 

5. Assessment paragraph: Assess your results and briefly state the broadly interesting conclusions that these results support. 

We hope our model will be able to achieve a high degree of accuracy, comparable to a human. 

**Ethical Sweep**

General Questions:
1. Should we even be doing this?
2. What might be the accuracy of a simple non-ML alternative?
3. What processes will we use to handle appeals/mistakes?
4. How diverse is our team?

Data Questions:
1. Is our data valid for its intended use?
2. What bias could be in our data? (All data contains bias.)
3. How could we minimize bias in our data and model?
4. How should we “audit” our code and data?

Impact Questions:
1. Do we expect different errors rates for different sub-groups in the data?
2. What are likely misinterpretations of the results and what can be done to prevent those misinterpretations?
3. How might we impinge individuals' privacy and/or anonymity?
