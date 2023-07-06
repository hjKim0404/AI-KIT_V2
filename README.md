# AI-KIT, 월리를 찾아라



<details open="open">
  <summary>Table of Contents</summary>
  <ol>
    <li>
      <a href="#about-the-project">About The Project</a>
      <ul>
        <li><a href="#built-with">Built With</a></li>
      </ul>
    </li>
    <li><a href="#directory">Directory</a></li>
    <li><a href="#usage">Usage</a></li>
    <li><a href="#todo">Todo</a></li>
    <li><a href="#course composition">Course Composition</a></li>
  </ol>
</details>





<!-- ABOUT THE PROJECT -->

## About The Project

해당 교육용 프로그램에는 수많은 객체들 속에서 찾고자 하는 타겟을 찾아낼 수 있는 인공지능이 구현되어 있습니다. 이 프로그램은 인공지능을 배우는데 있어서 필수적인 기술들을 중심으로 구성되어 있습니다. 따라서 해당 프로그램 커리큘럼을 따라 학습한다면 인공지능 프로그램 개발에 대한 전반적인 이해를 얻을 수 있습니다.

<!-- 대표 이미지 추가-->

### Built With

* <a href ='https://www.python.org'>Python</a>기반 프로그래밍
* <a href='https://numpy.org'>Numpy</a>, <a href='https://www.tensorflow.org'>Tensorflow</a> 등의 인공지능 개발에 필수적인 패키지 사용
* <a href='https://keras.io'>Keras</a>, <a href='https://en.wikipedia.org/wiki/CNN'>CNN</a> 을 활용한 전문적인 인공지능 모델 학습 이론 탑재



<a name='directory'><!-- DIRECTORY --></a>

## Directory

```
├── README.md                - README 파일
│
├── data/                    - 학습, 검증, 평가에 사용되는 리소스
│	├── AI-KIT_Deep_manual.pdf     - AI-KIT 활용을 위한 교수자/학습자 가이드
│	│	wally-data/	       - 모델 학습에 필요한 월리를 찾아라 책 1권부터 4권까지 이미지 리소스
│   ├── sample/                           - 1권 ~ 4권까지 촬영된 crop되지 않은 이미지
│   │
│   ├── test/                             - 평가에 사용되는 crop되지 않은 이미지
│   │
│   ├── train/                            - 학습에 사용되는 crop된 이미지
│   │   ├── backgrounds/                     - crop된 background 이미지
│   │   └── wally/                           - crop된 타겟 상반신 이미지
│   │
│   └── val/                              - 검증에 사용되는 crop된 이미지
│   │   ├── backgrounds/                     - crop된 background 이미지
│   │   └── wally/                           - crop된 타겟 상반신 이미지
│ 
├── models/                   		  - 학습이 완료된 인공지능 모델 저장
│   └── sample_model/                        - 예제로 만들어진 인공지능 학습 모델
│ 
├── scripts/                 	    	    - 프로그램을 직접 구동하기 위한 스트립트
│   ├── model_training.ipynb                 - 인공지능의 학습 모델을 제작 및 검증하기 위한 ipynb파일
│   ├── model_test.ipynb                     - 학습이 완료된 인공지능 모델을 불러와 테스트하기 위한 ipynb파일
│   ├── datagenerator.py                     - 리소스 이미지들을 학습 데이터에 알맞은 형식으로 변환 후 활용하기 위한 클래스가 정의된 파일
│   └── helper.py                            - 프로그램 내의 모든 함수들이 정의된 파일
│ 
├── utils/                               - 프로그램을 구성하는 핵심 기능
│   └── datagenerator.py      		     - #삭제
│ 
└── pdf/                 	    	    - AI-KIT 강의 자료

```



<!-- USAGE -->

## Usage

### 타겟 찾기

1. 인공지능의 기초 개념에 대해 학습합니다.
2. 지도학습, 딥러닝, CNN의 구조와 개념에 대해 학습합니다.
3. Azure Lab을 사용해 가상 머신을 활성화하고 Jupyter Notebook에 접속합니다.
4. 6강 강의의 가이드를 통해 학습을 위한 데이터를 수집&가공합니다.
5. AI-KIT에서 제공하는 인공지능 모델을 사용해 학습합니다.
6. 인공지능 모델을 사용하여 월리를 찾아봅니다



<!-- TODO -->

## TODO

- [x] augmentation data 로 옮기기  *datagenerator 대신 helper로 이동 (함수는 함수끼리, 클래스는 클래스끼리 묶기 위함)
- [x] analysis 지우고 helper 로 옮기기 
- [x] directory 구조 변경
- [ ] datagenerator 을 data로 이름 바꾸기
- [ ] package 로 만들어서 pip로 올리기
- [ ] 교육 내용에 package 다운받는 과정 추가



<a name='course composition'></a>

## ↓ Course Composition

### Course 구성
<img width="1476" alt="스크린샷 2022-12-22 14 00 33" src="https://user-images.githubusercontent.com/102505826/209060529-71d32d44-7b3e-448a-afc0-d04844805bb7.png">


해당 Course 에서 아래 내용을 배울수 있습니다. 

1. AI, Machine Learning , Deep Learning 개념 학습 
2. Regression 개념과 Classification 개념 
3. Scikit Learn을 활용해 머신러닝 구현 (Regression, Classification)
4. Tensorflow을 활용해 Deep Neural Network 으로 이미지 분류기 학습해보기 
5. Tensorflow 활용해 Convolution Neural Netowrk (이하 CNN) 으로 학습해보기
6. Tensorflow 을 활용해 Wally Data 학습 시키기





<hr>

Copyright(c) 2020 by Public AI. All rights reserved.
