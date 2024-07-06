# 校园霸凌检测与预防系统

## 项目简介

本项目旨在开发一个能够自动识别校园对话中霸凌行为的系统，以帮助学校和教育工作者更有效地预防和干预霸凌事件。系统基于机器学习技术，对学生的日常对话进行监测和分析，当检测到潜在的霸凌行为时，系统将及时发出警告，以便采取相应的措施。

## 技术栈

- **编程语言**：Python
- **机器学习库**：scikit-learn
- **数据处理**：pandas
- **文本处理**：TF-IDF 向量化器

## 功能特性

- **数据收集与处理**：收集校园对话数据，并进行预处理，以便用于机器学习模型。
- **模型训练与测试**：使用多项式朴素贝叶斯模型对对话数据进行训练，并在测试集上进行评估。
- **霸凌检测**：能够识别对话中是否存在霸凌行为。
- **实时反馈**：当检测到霸凌行为时，系统能够提供实时反馈和警告。
- **报告生成**：生成详细的分类报告，以评估模型的性能。

## 使用说明

1. 确保您的环境中已安装 Python 和必要的库（pandas、scikit-learn 等）。
2. 下载或克隆此仓库到您的计算机。
3. 运行以训练模型并进行预测。
4. 根据模型输出的结果，采取相应的措施。

## 注意事项

- 本项目仅供教育和研究目的使用，不应用于实际环境中的霸凌检测。
- 对话数据的真实性和准确性对模型的性能至关重要，请确保数据的质量。
- 需要进一步的工作来优化模型，并考虑更多的霸凌检测特征。

## 许可证

本项目使用 MIT 许可证进行授权。


感谢您的使用，让我们一起为创建一个无霸凌的校园环境而努力！

# Campus Bullying Detection and Prevention System

## Project Overview

This project aims to develop a system that can automatically detect bullying behaviors in campus dialogues, helping schools and educators more effectively prevent and intervene in bullying incidents. The system is based on machine learning technology, monitoring and analyzing students' daily conversations to detect potential bullying behaviors and provide timely warnings for appropriate actions.

## Tech Stack

- **Programming Language**: Python
- **Machine Learning Library**: scikit-learn
- **Data Processing**: pandas
- **Text Processing**: TF-IDF Vectorizer

## Features

- **Data Collection and Preprocessing**: Collect campus dialogue data and preprocess it for machine learning model training.
- **Model Training and Testing**: Train a Polynomial Naive Bayes model on the dialogue data and evaluate it on a test set.
- **Bullying Detection**: Identify whether dialogues contain bullying behaviors.
- **Real-time Feedback**: Provide real-time feedback and warnings when bullying behaviors are detected.
- **Report Generation**: Generate detailed classification reports to assess model performance.

## Usage Instructions

1. Ensure your environment has Python and necessary libraries (pandas, scikit-learn, etc.) installed.
2. Download or clone this repository to your computer.
3. Run it to train the model and perform predictions.
4. Take appropriate actions based on the model's output results.

## Notes

- This project is for educational and research purposes only and should not be used for actual bullying detection in the environment.
- The authenticity and accuracy of the dialogue data are crucial for the model's performance; ensure the quality of the data.
- Further work is needed to optimize the model and consider more bullying detection features.

## License

This project is licensed under the MIT License - see the LICENSE file for details.


Thank you for using this project, let's work together to create a bullying-free campus environment!
