- blablabla...... 여기에 원하는 디렉토리 폴더 만들기
- 이미지 데이터셋 레이블별로 디렉토리 구축
- train, validation, test 8:1:1 비율로 나눔
- 전처리된 데이터셋 학습
~ 기본 200 epoch, validation epoch 개선 20번 동안 없으면 학습 early stop
~ 학습 완료시 ./classification/model_weight/ 디렉토리에 best accuracy, best loss, best F1 score 모델 3가지가 생성된다