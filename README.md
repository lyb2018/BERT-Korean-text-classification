# My personal project 

## 목적 
- 한국어 사전 학습 모델을 이용한 문서 분류(Text Classification) 구현


## Dataset 
- 저는 특허청의 특허 문서를 이용해서 문서 분류 Dataset을 구성했습니다
- Dataset은 전처리 후 유효한 특허 문서(label : 1) 7,999개와 유효하지 않은 특허 문서(label : 0) 5,068개로 구성하였습니다.
- 제가 만든 Dataset은 제공하지 않습니다. 이곳을 참조하시는 분들은 여러분 각자의 데이터 셋을 만들어서 참조하시길 바랍니다. 

## 사용한 pretrained model
- klue/bert-base

## Fine tuning 
- classifing whether document valid or invlaid.ipynb을 참조하시길 바랍니다

