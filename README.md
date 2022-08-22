# TRANSFORMER BASE MODEL

1. 이 레퍼지토리를 clone한다. ```git clone [this repo]```     
2. 가상 환경을 설정한다(다른 토드들과 버전을 혼동하지 않기 위해   
   2.1 ```$ conda create -n 가상환경이름 python=파이썬_버전```     
         즉 이와 같다 ```$ conda create -n transformer python=3.6.2```      
   2.2 ```[y]```눌러준다     
   2.3 가상환경 활성화 ```$ conda activate transformer```      
       이 결과 (base)가 (transformer)로 바뀌었을 것이다.   
 3. ```conda install zipp``` 실핼   
 4. ```conda install idna``` 실핼   
 5. ```python -m spacy download en``` 실행   
 6. ```python -m spacy download de``` 실행
 7. ```python -m spacy download en_core_web_sm de_core_news_sm``` 실행
 8. ```python train.py``` 실행