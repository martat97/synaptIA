# Python Project: synaptIA

In this work, we explore the development of a system capable of categorizing datasets autonomously, aiming to replace the manual categorization typically performed by human analysts within a company.

The objective is to design a solution capable of identifying salient features within datasets of various formats and intelligently assigning them to predefined classes.
We will delve into the methodologies employed to acquire diverse datasets and to standardize them into a unified, non-relational format. Furthermore, it will show the approach adopted to categorize these datasets based on a predetermined set of categories.

It's important to note that this work represents just the initial phase of what could evolve into a more expansive system capable of adapting to diverse categorization tasks and handling an increasingly broad array of dataset formats.

The Main Stages of the work are briefly outlined:
1. **Data Collection**
Initially, datasets are systematically gathered from different sources.
The collected data is carefully curated to ensure accuracy and reliability, with attention paid to checking the presence of noise.
Code: *Scraping.ipynb*
3. **Data Conversion**
The subsequent step involves converting datasets from relational formats to non-relational ones. The key challenge lies in selecting the most suitable NoSQL structure to address the problem effectively.
Code: *Converter.ipynb*
5. **Data Categorization**
This step involves the capability of the system of assigning the most appropriate label from the categorical Y we defined to non-relational datasets.
During the training phase, the system learns from labeled datasets.
Subsequently, in the testing phase, the accuracy is determined by doing a comparison between the classes assigned by the system with the expected ones.
Code: *Categorizer Part A.ipynb, Categorizer Part B.ipynb*
