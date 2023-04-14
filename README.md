# Toxic_comment_classifier_bow_lstm

## Introduction

Online forums and social media platforms have provided individuals with the means to put forward their thoughts and freely express their opinion on various issues and incidents. In some cases, these online comments contain explicit language which may hurt the readers. Comments containing explicit language can be classified into myriad categories such as Toxic, Severe Toxic, Obscene, Threat, Insult, and Identity Hate. The threat of abuse and harassment means that many people stop expressing themselves and give up on seeking different opinions.

To protect users from being exposed to offensive language on online forums or social media sites, companies have started flagging comments and blocking users who are found guilty of using unpleasant language. Several Machine Learning models have been developed and deployed to filter out the unruly language and protect internet users from becoming victims of online harassment and cyberbullying.

## Problem Statement

To build a multi-headed model that’s capable of detecting different types of toxicity like threats, obscenity, insults, and identity-based hate.

Having worked on an NLP use-case before (“Fake News Classifier to tackle Covid-19 dis-information”), my aim in this project was to focus on data pre-processing and feature engineering and ensure that the data, which will be consumed by my deep-learning models, is as clean as possible. Additionally, I decided to use fastText’s pre-trained word embedding to harness the power of Transfer Learning.

### dataset:
https://www.kaggle.com/datasets/dinbandhusuman/toxic-comment

