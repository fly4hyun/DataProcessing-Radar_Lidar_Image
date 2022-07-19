# DataProcessing-Radar_Lidar_Image
nuScenes 데이터셋 다운로드 필요 : https://www.nuscenes.org/download

nuScenes 데이터셋에서 제공하는 RADAR, Lidar, 카메라 데이터를 목적에 맞게 사용할 수 있도록 전처리 하는 코드
논문 "Radar Ghost Target Detection via Multimodal Transformers"에서 사용된 모델의 입력에 맞도록 데이터를 가공

기존 논문에서는 RADAR와 Lidar 데이터만을 사용하였으나, 본 코드에서는 카메라 데이터를 포함하도록 코드를 작성
생성된 데이터셋을 논문 "다수 자율주행용 센서 기반 멀티모달 딥러닝을 통한 레이더 고스트 표적 탐지"에서 사용
