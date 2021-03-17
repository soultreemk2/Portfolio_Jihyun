# Portfolio_Jihyun
포트폴리오 정리본


## _[Part 1] AI - Computer Vision_

### **Project 1) Image Classification**

* Background  
Image classification을 사용하여 단일 사물 이미지 분류 / 모델의 architecture 파악

* 최종목표  
kaggle: Plant Pathology 2020    
: 나뭇잎 이미지로 나무의 상태를 4가지로 분류  

* Process

(1) CNN을 기반으로 inception module 구축 & Googlenet architecture 구현

(2) 단일 모델 적용
    Inception v3 model import & Transfer learning    
    --> _accuracy가 84%에 불과_  
    
(3) 다중 모델 적용
    Import various models at once & Compare their performance  
   --> _99.8%의 training accuracy 달성 (val accuracy는 97%)_  
   
 코드: [classification](https://github.com/soultreemk2/Portfolio_Jihyun/tree/master/AI_Classification)
 
 
### **Project 2) Object Detection**

* Background  
Object Detection 모델 적용하여 항공위성 이미지에서 객체 탐지

* Process

(1) 최신 모델 조사 & 비교 (papers with code 참조)

(2) Apply 4 famous models to ariel image  
    --> but 일부 모델에서는 객체를 탐지하지 못하는 문제 발생  
    
(3) OpenCV for image preprocessing  
   --> large image size & small object 문제를 극복하기 위해 image cropping and etc....

 코드: [Detection](https://github.com/soultreemk2/Portfolio_Jihyun/tree/master/AI_Detection)
 
 (4) 기울어진 객체 탐지 (rotated object detection)  
 https://developer.nvidia.com/blog/detecting-rotated-objects-using-the-odtk/
 https://junha1125.tistory.com/21
 
 

## _[Part 2] ML - Structured Data Analysis_

### **Project 3) Bank Marketing**

* Background  
은행 고객 데이터를 기반으로, 고객의 특성 중 어느 부분이 정기예금 가입에 가장 많은 영향을 미치는가를 파악 & 당사의 정기예금에 가입할지 여부를 예측
(변수가 많지 않은 data)

* Process

(1) EDA & Preprocessing
 

(2) Modeling
 
 코드: [Bank-Marketing](https://github.com/soultreemk2/Portfolio_Jihyun/tree/master/ML_bank_marketing)
  
