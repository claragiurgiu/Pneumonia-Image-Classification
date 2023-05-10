# Pneumonia Image Classification - Neural Network Analysis and Recommendation

**Authors** [Clara Giurgiu](mailto:claragiurgiu@gmail.com), [Vlad Sekiguchi](mailto:vlsekig@gmail.com)

## Overview

For this project we use a Sequential Neural Network model to analyze and recognize pneumonia patterns amongst thousands of patients x-rays. Through an iterative process of enhancing certain features in the images and using a convoluted neural network we were able to improve our model's classification capabilities.

## Business Problem
How can we help doctors and hospitals avoid false negatives in potential pneumonia patients. This most importantly gets the patient to be diagnosed correctly and allows for hospitals to save money in unnecessary treatments.

## Data
This project uses the x-ray images provided by the [University of California San Diego and Guangzhou Women and Children's Medical Center](https://data.mendeley.com/datasets/rscbjbr9sj/3). The images can be found in the chest_xray folder of this project's repository.

## Methods
We transformed the images using ImageDataGenerator and then used a Sequential Neural Network. In order to measure the minimization of false negatives, both accuracy and recall scores were used to reflect the model's success. To analyze the model's improvement, we used a dummy model that evenly picks 50/50 between positive and negative diagnostics. The next steps after the Sequential model were to enhance the images via ImageDataGenerator and retrain the model, and then use a convoluted neural network to further improve the model.

## Results

## 1. Sequential Neural Network
This model to our accuracy from a meager 50% all the way to a 96% which is fantastic for training. Now how does it perform against testing data
- input an image showing results

## 2. Enhance images - Sequential Neural Network

## 3. Convoluted Neural Network


## Conclusion

In conclusion 96% accuracy, and __ % recall scores are a great standard to have for diagnosing. Of course this model is not meant to be a doctor, and should be used in conjunction with a medical professional. In business terms, this accuracy would greatly reduce costs for both patients and health providers.

According to [Khealth](https://www.khealth.com/learn/antibiotics/antibiotics-for-pneumonia/#:~:text=The%20first%2Dline%20treatment%20for%20pneumonia%20in%20adults%20is%20macrolide,bacterial%20pneumonia%20is%20typically%20amoxicillin) Azithromycin is a first-line treatment for adults under 65 with bacterial pneumonia. According to [Enhance Health](https://enhancehealth.com/how-much-do-antibiotics-cost-without-insurance/) this antibiotic has a generic price point of $31.30 and brand name, Zithromax, price point of $152.16. We'll use our baseline dummy model as an example of total savings.

In this model out of 4,184 observations, 514 people were diagnosed as false positives which means that it will end up costing them in total $16,088.20 if the antibiotic were generic and $78,210.24 if the antibiotic were brand name. It could cost the hospital the same or even more, as we don't imagine insurance reimburses hospitals for misdiagnosed treatments. 1,572 people were diagnosed as false negatives which will cost the patients not only in health, but money too as their situation might be more severe and they would have to pay for much longer antibiotic treatements. Health providers would also owe millions in liability.


## Next Steps



## For more Information
See the full analysis in the [Jupyter Notebook]


## Repository Structure

```
├── 
├── 
├── 
├── 
├── 
```