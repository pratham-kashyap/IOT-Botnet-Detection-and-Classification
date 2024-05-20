# IoT Botnet Detection Project

## Overview

This project aims to detect botnet attacks on IoT devices using various machine learning models. The dataset used for this project is the N-BaIoT dataset, which contains benign and malicious data from multiple IoT devices under different types of attacks.

## Dataset

The dataset used in this project is obtained from [Kaggle](https://www.kaggle.com/datasets/mkashifn/nbaiot-dataset/data). It includes the following files:

- `4.benign.csv`
- `4.gafgyt.combo.csv`
- `4.gafgyt.junk.csv`
- `4.gafgyt.scan.csv`
- `4.gafgyt.tcp.csv`
- `4.gafgyt.udp.csv`
- `4.mirai.ack.csv`
- `4.mirai.scan.csv`
- `4.mirai.syn.csv`
- `4.mirai.udp.csv`
- `4.mirai.udpplain.csv`

## Project Structure

1. **Importing Libraries**
2. **Reading Dataset**
3. **Assigning Labels to Dataset**
4. **Concatenating into One Dataset**
5. **Splitting Dataset and Feature Selection**
6. **Model Training and Evaluation**
    - Decision Tree
    - Logistic Regression
    - Naive Bayes
    - LightGBM
    - Neural Network
7. **Visualization**
8. **Conclusion**

## Conclusion

This project demonstrated various machine learning techniques for detecting IoT botnet attacks. Models such as Decision Tree, Logistic Regression, LightGBM, and Neural Network were implemented and evaluated. Visualization techniques were used to interpret the results and the performance of each model. The dataset from Kaggle proved to be a valuable resource for this task. Future work could involve further tuning of model hyperparameters, exploring additional feature engineering techniques, and incorporating more advanced models to improve detection accuracy.
