# WIDS 2025 Brain fmri Data science challenge :  CNN + DNN

Some important file links:
1. Training fmri data: https://drive.google.com/file/d/1FIOq2rt8GuSz5MaERViiHBdncSEYOSsY/view?usp=sharing
2. Testing fmri data: https://drive.google.com/file/d/1Tb3CPr-opZk7qL4Nokzn6FJcjEC4JBZe/view?usp=sharing

## Current model:

My present model acheived an f1-score of 0.75 on test data, which is a decent socre for a multi outcome prediction objective. As the competition organizers provided only the tabular correlation data between brain regions, the max acheivalble score could be anywhere between 0.75-0.85 based on the model used for prediction.

## About the Challenge:

The WiDS Datathon Global Challenge was developed with Ann S. Bowers Women’s Brain Health Initiative (WBHI) in collaboration with Cornell University and UC Santa Barbara. 
Datasets and support are provided by the Healthy Brain Network (HBN), the signature scientific initiative of the Child Mind Institute, and the Reproducible Brain Charts project (RBC).

Neuropsychiatric disorders that occur in development, like anxiety, depression, autism, and attention deficit hyperactivity disorder, or ADHD, often differ in how and to what extent they affect males and females. 
ADHD occurs in about 11% of adolescents, with around 14% of boys and 8% of girls having a diagnosis. 
There is some evidence that girls with ADHD can often go undiagnosed, as they tend to have more inattentive symptoms which are harder to detect. 
Girls with ADHD who are undiagnosed will continue suffering with symptoms that burden their mental health and capacity to function.

## Problem Statement:

Participants were tasked with building a model to predict both an individual’s sex and their ADHD diagnosis using functional brain imaging data of children and adolescents and their socio-demographic, emotions, and parenting information.

Challenge Question and Task:

“What brain activity patterns are associated with ADHD; are they different between males and females, and, if so, how?”

The task is to create a multi-outcome model to predict two separate target variables: 1) ADHD (1=yes or 0=no) and 2) female (1=yes or 0=no).

Why is this important?
Tools of this nature can help identify individuals who may be at risk of ADHD, which can be difficult to diagnose particularly in females. 
Importantly, they help shed light on the parts of the brain relevant to ADHD in females and males, which in turn could lead to improvements in personalized medicine and therapies. 
Identifying ADHD early and designing therapies targeting specific brain mechanisms in a personalized way can greatly improve the mental health of affected individuals.

**Evaluation**

The F1 score is the harmonic mean of the precision and recall. It thus symmetrically represents both precision and recall in one metric. 
The highest possible value of an F-score is 1.0, indicating perfect precision and recall, and the lowest possible value is 0, if precision and recall are zero.

## Data Description

**Additional Info:**

We will analyze diagnostic data, socio-demographic, emotions, and parenting data, and functional MRI data from the Healthy Brain Network (HBN) — the signature scientific initiative of the Child Mind Institute. 
HBN utilizes a community-referred recruitment model by encouraging the participation of families who have concerns about mental health or learning challenges in their children. 
The functional MRI data are used to extract a time series of activity per brain region, and these regions’ time series are correlated to obtain functional MRI connectome matrices.

**The goal:**

The goal is to build a Multi-outcome model to predict both an individual’s sex and their ADHD diagnosis using functional brain imaging data of children and adolescents and their socio-demographic, emotions, and parenting information.
Essentially a transformation of the original geographical coordinates into a new feature form. Submissions that include these types of features will be considered non-compliant and will be disqualified.

**Target Variables**

ADHD_Outcome: Type of Diagnosis (0=Other/None, 1=ADHD)
Sex_F: Sex of participant (0=Male, 1=Female)

