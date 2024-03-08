# covid19_fake_news
*Hasan Dwi Cahyono, Atara Mahadewa, Ardhi Wijayanto, Dewi Wisnu Wardani, Haryono Setiadi (2024)*


[![IJEECS](https://ijeecs.iaescore.com/public/journals/15/homeHeaderTitleImage_en_US.png)](https://ijeecs.iaescore.com/index.php/IJEECS/article/view/35494)
[![License: MIT](https://img.shields.io/badge/License-MIT-yellow.svg)](https://opensource.org/licenses/MIT)

This repository is dedicated for COVID-19 fake news detection and classification and includes the Python Code in Jupyter Notebook for the paper of [Fast Naïve Bayes classifiers for COVID-19 news in social networks]

The source code presented in this repository is adapted from [https://github.com/parthpatwa/covid19-fake-news-detection] (the original source code).

Thanks.


## Running the code

To run experiments of the paper, take the following steps:

1. Install the dependencies using "./requirements.txt" by running:
```bash
pip install -r requirements.txt
```
2. Download the dataset for this research accordingly from [https://competitions.codalab.org/competitions/26655]. Extract the data into your preferred location such as "/content/drive/MyDrive/UNS/dataset/" and adjust the dataset location in 'PATH'.

3. Now, you can run each experiment of the paper.


## Citation
```bash
@article{Cahyono2024,
abstract = {The growth of fake news has emerged as a substantial societal concern, particularly in the context of the COVID-19 pandemic. Fake news can lead to unwarranted panic, misinformed decisions, and a general state of confusion among the public. Existing methods to detect and filter out fake news have accuracy, speed, and data distribution limitations. This study explores a fast and reliable approach based on Na{\"{i}}ve Bayes algorithms for fake news detection on COVID-19 news in social networks. The study used a dataset of 10,700 tweets and applied text pre-processing, term-weighting, document frequency thresholding, and synthetic minority oversampling techniques (SMOTE) to prepare the data for classification. The study assessed the performance and runtime of four models: gradient boosting (GDBT), decision tree (DT), multinomial Na{\"{i}}ve Bayes (MNB), and complement Na{\"{i}}ve Bayes (CNB). The testing results showed that the CNB model reaches the highest accuracy, precision, recall, and F1 score of approximately 92% each, with the shortest runtime of 0.55 seconds. This study highlights the potential of the CNB model as an effective tool for detecting online fake news about COVID- 19, given its superior performance and rapid processing time.},
author = {Cahyono, Hasan Dwi and Mahadewa, Atara and Wijayanto, Ardhi and Wardani, Dewi Wisnu and Setiadi, Haryono},
file = {:Users/hasandc/Documents/Mendeley Desktop/Cahyono et al. - 2024 - Fast Na{\"{i}}ve Bayes classifiers for COVID-19 news in social networks.pdf:pdf},
journal = {Indonesian Journal of Electrical Engineering and Computer Science},
keywords = {Fake news detection,Fast and reliable,Na{\"{i}}ve Bayes classifiers,Real-time processing,Social media},
mendeley-tags = {Fake news detection,Fast and reliable,Na{\"{i}}ve Bayes classifiers,Real-time processing,Social media},
number = {2},
title = {{Fast Na{\"{i}}ve Bayes classifiers for COVID-19 news in social networks}},
volume = {34},
year = {2024}
}

```
