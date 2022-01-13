# Dacon_tabular_img_classification_model

#데이콘 작물분류대회 참여코드
#csv 시계열데이터 + 이미지를 통해 작물의 상태를 판단한다.
#크게 csv처리모델 + 이미지처리모델 => 분류의 형태로 이루어진다
#오토인코더를 통한 csv차원축소 + Resnet pretrained model을 통한 feature extraction을 하여 최종 XGB로 파인튜닝하여 앙상블모델 제작
