# DataProcessing-Radar_Lidar_Image
nuScenes 데이터셋 다운로드 필요 : https://www.nuscenes.org/download

환경 설정시 버전 확인 중요

nuScenes 데이터셋에서 제공하는 RADAR, Lidar, 카메라 데이터를 목적에 맞게 사용할 수 있도록 전처리 하는 코드
논문 "Radar Ghost Target Detection via Multimodal Transformers" (https://ieeexplore.ieee.org/document/9497756) 에서 사용된 모델의 입력에 맞도록 데이터를 가공
(논문에서 데이터셋을 가공한 방법과 관련된 논문: "Autonomous Driving: Radar Sensor Noise Filtering and Multimodal Sensor Fusion for Object Detection with Artificial Neural Networks" (https://www.researchgate.net/publication/342283221_Autonomous_Driving_Radar_Sensor_Noise_Filtering_and_Multimodal_Sensor_Fusion_for_Object_Detection_with_Artificial_Neural_Networks) )

기존 논문에서는 RADAR와 Lidar 데이터만을 사용하였으나, 본 코드에서는 카메라 데이터를 포함하도록 코드를 작성
생성된 데이터셋을 논문 "다수 자율주행용 센서 기반 멀티모달 딥러닝을 통한 레이더 고스트 표적 탐지"에서 사용

본 코드의 데이터셋을 통해 논문 "다수 자율주행용 센서 기반 멀티모달 딥러닝을 통한 레이더 고스트 표적 탐지" (https://www.dbpia.co.kr/journal/articleDetail?nodeId=NODE11048129) 의 실험을 진행
