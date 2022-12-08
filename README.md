# Alzheimer_MCI-CNN_Classifier
- Deep Learning based Alzheimer & MCI Diagnosis Model
- 딥러닝 기반 알츠하이머, 경도인지장애 진단 모델 개발
<br>

- Metadata Dashboard (Looker Studio) : [링크바로가기](https://datastudio.google.com/s/t6TpK5bx214)
<br>

- 블로그 포스팅 [작성완료]
  - (1) 서론과 메타데이터 분석 : [링크바로가기](https://velog.io/@dankj1991/Project-Alzheimer-MCI-Deep-Learning-Diagnosis-Model-1-Intro-Metadata)
  - (2) 모델링 과정 : [링크바로가기](https://velog.io/@dankj1991/Project-Alzheimer-MCI-Deep-Learning-Diagnosis-Model-2-Modeling)
  - (3) 예측 및 결론 : [링크바로가기](https://velog.io/@dankj1991/Project-Alzheimer-MCI-Deep-Learning-Diagnosis-Model-3-Prediction-Conclusion)
<br>

<div align=center>

![image](https://user-images.githubusercontent.com/109939415/205808524-fa40e1c0-88da-4b5b-b71e-b9051e0f77ab.png)

<img src="https://img.shields.io/badge/Visual Studio Code-007ACC?style=for-the-badge&logo=Visual Studio Code&logoColor=white"></a>
<img src="https://img.shields.io/badge/Google Colab-F9AB00?style=for-the-badge&logo=Google Colab&logoColor=white"></a>

<img src="https://img.shields.io/badge/Python-3776AB?style=for-the-badge&logo=python&logoColor=white"></a>
<img src="https://img.shields.io/badge/Jupyter-F37626?style=for-the-badge&logo=Jupyter&logoColor=white"></a>

<img src="https://img.shields.io/badge/NumPy-013243?style=for-the-badge&logo=NumPy&logoColor=white"/></a>
<img src="https://img.shields.io/badge/pandas-150458?style=for-the-badge&logo=pandas&logoColor=white"/></a>
<img src="https://img.shields.io/badge/scikit learn-F7931E?style=for-the-badge&logo=scikit learn&logoColor=white"/></a>

<img src="https://img.shields.io/badge/TensorFlow-FF6F00?style=for-the-badge&logo=TensorFlow&logoColor=white"/></a>
<img src="https://img.shields.io/badge/Keras-D00000?style=for-the-badge&logo=Keras&logoColor=white"/></a>

<img src="https://img.shields.io/badge/Looker-4285F4?style=for-the-badge&logo=Looker&logoColor=white"></a>
<img src="https://img.shields.io/badge/Plotly-3F4F75?style=for-the-badge&logo=Plotly&logoColor=white"></a>

<img src="https://img.shields.io/badge/Microsoft PowerPoint-B7472A?style=for-the-badge&logo=Microsoft PowerPoint&logoColor=white"></a>
<img src="https://img.shields.io/badge/Microsoft Word-2B579A?style=for-the-badge&logo=Microsoft Word&logoColor=white"></a>

</div>

# Project Outline 프로젝트 개요
- 합성곱 신경망(CNN)을 통해 Brain MRI 이미지를 알츠하이머와 경도인지장애(MCI)로 분류하는 딥러닝 모델 개발

![image](https://user-images.githubusercontent.com/109939415/205810768-434e9bef-2131-4547-b96c-c898a23bb407.png)

## Deep Learning Pipeline - 딥러닝 인파이프라인

![image](https://user-images.githubusercontent.com/109939415/205813415-084a1f89-b93b-4e19-847d-1ff512155bfe.png)

# Introduction 서론

## Dementia, Alzheimer's Disease, Mild Cognitive Impairment

![image](https://user-images.githubusercontent.com/109939415/205811620-c540588b-de54-46dc-969b-cac14bcf8348.png)
![image](https://user-images.githubusercontent.com/109939415/205811637-18eb87c9-4d45-4693-85ba-9ab556ac8996.png)

## Need for Research

![image](https://user-images.githubusercontent.com/109939415/205811871-9b338de2-4d27-4d4f-bd7f-4002302d5899.png)

## Goals 목표 및 가설

![image](https://user-images.githubusercontent.com/109939415/205811937-c5c235e7-a729-4991-9c20-ef68ce2fea94.png)

# Metadata Analysis - Looker studio

[링크바로가기](https://datastudio.google.com/s/t6TpK5bx214)

![image](https://user-images.githubusercontent.com/109939415/205814296-595238cf-df08-4c47-a585-1cd9ec3d05ff.png)

# Modeling 모델링

## Modeling Process - Colab

![image](https://user-images.githubusercontent.com/109939415/205814857-c54ab7b5-6de0-431c-a6df-decf279b6f02.png)

## Model Structure - 모델 구조

![image](https://user-images.githubusercontent.com/109939415/205814886-1546f4b9-0107-447c-9482-ccfb0e141f1a.png)

## Model 1 - Vanilla CNN

![image](https://user-images.githubusercontent.com/109939415/205815735-a4f411cf-dcf5-4d3e-82c9-7b0557e39b77.png)
![image](https://user-images.githubusercontent.com/109939415/205815999-6d7175b3-bc23-4a90-a7e8-8a007d50e37d.png)
![image](https://user-images.githubusercontent.com/109939415/205816019-b71ab5a6-d58d-4a35-be01-cb51e94392b6.png)

## Model 2 - ResNet50V2

![image](https://user-images.githubusercontent.com/109939415/205816436-84ab218e-6cac-4f86-b5fd-66bfc110a2f4.png)
![image](https://user-images.githubusercontent.com/109939415/205816506-d0b82c06-b87f-47d8-9c1f-b93fcaad18a0.png)
![image](https://user-images.githubusercontent.com/109939415/205816543-f7bb8d05-3c63-4242-a479-aa0bd38214a4.png)

### Negative Transfer
![image](https://user-images.githubusercontent.com/109939415/205816598-f5f88212-84d1-4d53-90cf-730e3d337652.png)

## Final Model - Hyperparameter Tuning

![image](https://user-images.githubusercontent.com/109939415/205816778-8a4d9186-27ad-40af-99f4-41a2f6e63f3d.png)
![image](https://user-images.githubusercontent.com/109939415/205816788-7e2d4e9b-4a36-476c-a1b3-69ecbf4138f0.png)
![image](https://user-images.githubusercontent.com/109939415/205816848-87e753e0-e3b0-4b53-b005-72fa15438638.png)
![image](https://user-images.githubusercontent.com/109939415/205816868-6e7876db-ae72-4e14-89ac-909bda0eb9a8.png)
![image](https://user-images.githubusercontent.com/109939415/205816887-50747a01-25bc-444f-8b81-1aa7c699caeb.png)
![image](https://user-images.githubusercontent.com/109939415/205817097-fad97b1e-22e8-4ce5-a375-a5f064cb1fb3.png)

# Model Prediction 모델 예측

![image](https://user-images.githubusercontent.com/109939415/205817167-6fd84afb-283b-4a65-ba1a-ae305d653290.png)
![image](https://user-images.githubusercontent.com/109939415/205817193-60163905-947e-4ca0-9622-985afec92b2f.png)
![image](https://user-images.githubusercontent.com/109939415/205817198-5f06bdab-a9c8-4a67-8544-a8aed477d08a.png)

# Conclusion 결론

## Summary 요약

![image](https://user-images.githubusercontent.com/109939415/205817760-2b0e433b-6f40-4fd7-823b-cf0194852f47.png)

## Limitations & Further Research

![image](https://user-images.githubusercontent.com/109939415/205817806-8362528f-2ca4-4c05-be15-e5940cb17b1a.png)

## Takeaways

![image](https://user-images.githubusercontent.com/109939415/205817830-f76450e4-c0ae-4ca5-8da5-67c66a329010.png)
