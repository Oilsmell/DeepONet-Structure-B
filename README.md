# DeepONet-Structure-B

코드 파일 구성도
01_train_structure_A.py: 구조물 A 데이터로 모델을 학습하는 메인 코드 (Branch Net에 DI 적용 + 비대칭 Loss).

02_verify_structure_A.py: 학습된 모델이 구조물 A의 손상을 잘 복원하는지 확인하는 코드.

03_generate_structure_B.py: 구조물 B의 건강 데이터만 사용하여 가상의 손상 데이터를 생성해보는 코드.

04_validate_structure_B.py: 생성된 데이터와 실제 구조물 B 손상 데이터(48%)를 비교하여 일반화 성능을 검증하는 코드.

05_analyze_raw_diff.py: 두 데이터 파일(건강 vs 손상)의 차이를 시각적으로 확인하는 분석 도구.
