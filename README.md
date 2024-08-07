# Machine Learning Projects Collection

## Transformer Translation Analysis
https://hub.zenoml.com/project/ac445ff2-d77b-4c4e-b31c-251e437bd9ce/zh-en%20Translation

In this analysis, we specifically focus on Simplified Chinese-to-English translation tasks. We evaluate a subset of the WMT19 zh-en dataset (Foundation, 2019) using the pretrained transformer
model from (Tiedemann and Thottingal, 2020).
We use SacreBLEU, introduced by (Post, 2018),
as the evaluation metric for the generated translations. In the latter part of this report, we will refer
to this metric simply as BLEU. We conduct a detailed analysis of the behavior of the translation
transformer model through a customized project
on the ZenoML platform (Cabrera et al., 2023),
where we can slice the data into categorized subsets and observe the model’s performance.
Our analysis reveals various translation errors,
such as name and term inaccuracies, missing information, overly summarized translations, and issues stemming from the dataset quality. These errors highlight the limitations of the current model,
the impact of noisy data, and the complexities of
the Chinese language. We suggest that employing larger models, cleaner datasets, specialized tokenizers, and fine-tuning techniques could significantly enhance translation accuracy

## Adversarial Example
 In this project, we investigate techniques for creating adversarial examples aimed at neural networks, specifically using the MNIST dataset
 and targeting a pretrained multi-layer percep
tron (MLP) with three hidden layers. Our ex
ploration starts with the Fast Gradient Sign
 Method (FGSM) as a foundational approach.
 Building on this, we examine two variations:
 the Basic Iterative Method and the Target Class
 Method. Additionally, we develop and evaluate
 a novel method inspired by these established
 techniques, adapting the FGSM framework to
 enhance its efficacy

## Coordinate Descent
 In this project, we explore how well different
 coordinate descent methods work for solving
 binary logistic regression, a common type of
 problem in machine learning for classifying
 data into two categories. We compare three
 methods: Random-feature Coordinate Descent
 (RCD), Greedy Coordinate Descent (GCD),
 and Cyclic Coordinate Descent (CCD). Our
 goal is to see how each method chooses coor
dinates and updates them, and then test to see
 which one performs best through experiments.

## Play prediction
In this project, we predict whether players would play certain games and how many hours they would play using the dataset from Steam. We use Bayesian Personalized Ranking and some other similarity metrics as features, and use Logistic Regression to predict whether players would play games (We also explore other models and use the best one). We use Latent Factor Model to predict the time players would play games. 

## Prototype Selection
 In this project, we investigate the efficacy of
 prototype selection methods in enhancing the
 speed of nearest neighbor classification. Specif
ically, we implement and compare three dis
tinct approaches: Random Selection, K-means
 clustering, and Condensed Nearest Neighbor
 (CNN). Our evaluation focuses on their perfor
mance relative to classification accuracy and
 computational efficiency when applied to the
 MNIST dataset. This comparative analysis
 aims to determine the most effective technique
 for reducing computational demands while
 maintaining or improving the accuracy of the
 nearest neighbor classifier

## Stacking
Using
 Stacking to Enhance Model Performances
 on Rating Predictions for Food Recipe.


## Battery Recycling 
https://github.com/haotianxu2021/hackIoT

Finetuning a pre-trained image classification on the battery classification task. Us3data augmentation techniques to generate more samples. Deploy the model on the Streamlit using Python.

## Crop Yield Forecasting
https://github.com/haotianxu2021/EY_Data_Challenge_2023_Crop_Forecast

Process satellite data and turn them into features by calculating various indices. Predict crop yield using RandomForest (also explore other models).

## Emotion Recognition and Recommendation
https://github.com/gridsusc/mindspark-10-team-Renaissaince

 ● Designed and developed an emotion recognition and recommendation system on the web application using Streamlit to
 recognize users’ emotions and recommend music to help them relax.
 
 ● Built a multi-model system to recognize emotions, including an image classification model (Xception) to take photo inputs and a
 speech sentiment analysis model to take audio inputs.
 
 ● BuiltanXGBoostclassifier to assign songs to different emotion labels and give recommendations based on users’ emotions

## Marshall Data Competition 2021
https://github.com/haotianxu2021/Marshall_data_competition_2021

Explore a shipping company dataset, process it, and predict shipping time.

