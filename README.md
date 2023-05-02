# 재활용품을 분류해주는 이미지 분류 모델 제작 프로젝트

### 1.Skills
Jupytert \
Python \
Numpy \
Pandas \
Selenium \
tensorflow \
ImageDataGenerator \
PIL \
keras

### 2.프로젝트 개요
한 사람이 평생 살아가며, 배출하는 쓰레기는 약 55톤으로 심각한 환경문제를 야기하고 있는 상황이다. \
이 중에서 재활용(Recycle)될 수 있는비율이 가장 높은 자원은 페트병이다. \
페트병은 생태계오염을가장 많이 시키는 1순위 자원이며, 플라스틱 1%만 줄여도연간 640억 절감의 경제적 효과를 가져올 수 있다. \


### 3.프로젝트 목표
이미지를 찍으면스스로 플라스틱 재활용 여부를 판단하는분류예측기를 제작

### 4. 흐름도

### 5.자료구성
0.Crawling.ipynb : 구글이미지, Kaggle를 통해서 크롤링 데이터 수집
1.Data_Augmnetation.ipynb : 부족한 데이터를 늘리기 위한 데이터 증식
2.Preprocessing.ipynb: 데이터의 리사이징 등을 통한 전처리
3.CNN_Model_.ipynb : 이미지를 분류하기 위한 base모델 구축

### 6.프로젝트 팀원 역할 분담
| 이름 | 담당 업무 |
| ------ | ------ |
| 진세용 | 팀장/데이터증식/모델구축 |
| 김소연 | 크롤링 |
| 조영훈 | 모델구축 |
| 김성훈 | 전처리 |

### 7.팀 내 담당 업무

-데이터증식: EDA를 통해 부족한 데이터를 증식하기 위해 Imagegenerator를 사용하여 코드 작성
-모델구축: CNN을 Base로 하여 6개 layer로 층을 구성하여 모델구성하는 코드 작성

### 8. 발표자료
https://pepper29.notion.site/CNN-c0b081eb237a4b6fb365f3c5163bb4e4
