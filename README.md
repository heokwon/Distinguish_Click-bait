# Distinguish_Click-bait
#### Alpaco NPL mini-project
### Team
* 손보영, 이성준, 옥지성, 전영욱, 허 권   
* [PPT]()
<br><br>
## Introduction
* 기사와 내용일 일치하지않은, 클릭을 유도하는 피시성 기사를 가리기 위해 진행한 프로젝트
* 딥러닝을 이용해 기사의 내용을 간략하게 요약하고, 헤드라인과 비교
<br><br>
## Model and Data
* model : mT5
* 데이터 종류 : 신문기사
* 데이터 형태 : 뉴스 택스트
* 수량 : 원문데이터 30만건
* 출처 : Ai-Hub ( https://aihub.or.kr/aihubdata/data/view.do?currMenu=115&topMenu=100&aihubDataSe=realm&dataSetSn=97 )
<br><br>
## Envs and Requierments
* Google Colab, VScode
* Tensorflow, Hugging Face, transformers, Pandas
<br><br>
## Progress
* 데이터셋 구축
* 데이터셋 정제   
json -> dictionary   
데이터셋에서 제목, 원문, 추출요약, 생성요약 추출   
* transform AutoTokenizer 사용
* Hugging Face 이용하여 모델 구축 - mT5 모델에 fine-tuning
