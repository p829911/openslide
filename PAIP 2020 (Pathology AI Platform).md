### PAIP 2020 (Pathology AI Platform)

#### Aims

paip 2020 challenge의 목표는 전체 슬라이드 이미지 분석을 위해 결장 직장암에서 분자 하위 유형의 자동 분류를 위한 새로운 알고리즘 또는 기존 알고리즘을 평가하는 것이다.
모든 참가자는 임상 시험 없이 디지털 이미지 분석을 수행하여 대장 암에서 분자 발암 성 경로 중 하나, 즉 대장 암에서의 현미부수체 불안정성(MSI)을 예측해야 한다.

##### TASK: MSI-High Classification in Colorectal Cancer

MSI-High 분류는 주요 과제로, 과제 평가에서 최우선 과제로 고려 된다. 따라서 제출을 할 때 전체 종양 영역의 MSI-H 예측 및 분할 결과를 같이 제출해야 한다.

#### Background

Colorectal cancer (CRC, 결장직장암) 는 선진국과 개발 도상국의 암 관련 사망 측면에서 높은 관련성이 있는 암이다. 통계적으로 CRC는 미국과 한국에서 세번째로 만이 진단되는 악성 종양이다. CRC는 유전자 및 후성 유전자 변형의 축적의 결과로 발생하며, 3개의 분자 발암 경로 및 2개의 형태학적 다단계 경로를 갖는 이종성 질병 개체로 알려져있다. 3가지 분자 발암 경로가 있는데 이 챌린지에서는 MSI 탐지에 집중할 것이다.

- MSI-High (instability at >= 2 microsatellite markers)
- MSI-Low (instability at 1 marker)
- MSI-Stable (microsatellite stable or no instability)

#### Dataset

training data: 47 WSI

1. 최초의 WSI
2. 병리학자의 XML 주석
3. 병리학자의 MSI 분류

