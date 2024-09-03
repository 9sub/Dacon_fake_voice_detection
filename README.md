# Dacon SW중심대학 디지털 경진대회_SW와 생성AI의 만남 : AI 부문


작성중입니다


### Background on topic selection
> 최근 생성 AI 기술의 발전으로 인해 가짜 음성 합성이 점점 더 정교해지고 있습니다. 이러한 가짜 음성은 기존의 텍스트 기반 가짜 정보 유포 문제에 더해 새로운 위협이 되고 있습니다. 가짜 음성을 통해 유명인의 음성을 모방하거나 중요 인사의 발언을 조작할 수 있기 때문입니다. 이는 개인 및 기업의 명예 실추, 금전적 피해, 사회적 혼란 등 다양한 문제를 야기할 수 있습니다.
> 따라서 가짜 음성을 신뢰할 수 있는 수준에서 검출하고 탐지할 수 있는 기술 개발이 시급한 상황입니다. 이를 통해 가짜 음성으로 인한 피해를 예방하고, 생성 AI 기술이 건전하게 활용될 수 있는 환경을 조성할 수 있을 것입니다.
> 또한 가짜 음성 탐지 기술은 음성인식, 스피커 인증, 대화 시스템 등 다양한 분야에서 활용될 수 있어 폭넓은 파급효과가 예상됩니다.
> 따라서 가짜 음성 검출 및 탐지 기술을 발전시킨다면 앞으로 대두될 수 있는 가짜 음성 문제에 선제적으로 대응할 수 있을 것입니다.


### Subject
```
생성 AI의 가짜(Fake) 음성 검출 및 탐지
```


### Problem
> 5초 분량의 입력 오디오 샘플에서 영어 음성의 진짜(Real) 사람의 목소리와 생성 AI의 가짜(Fake) 사람의 목소리를 동시에 검출해내는 AI 모델을 개발해야합니다.
> 학습 데이터는 방음 환경에서 녹음된 진짜(Real) 사람의 목소리 샘플과 방음 환경을 가정한 가짜(Fake) 사람의 목소리로 구성되어 있으며, 각 샘플 당 사람의 목소리는 1개입니다.
> 평가 데이터는 5초 분량의 다양한 환경에서의 오디오 샘플로 구성되며, 샘플 당 최대 2개의 진짜(Real) 혹은 가짜(Fake) 사람의 목소리가 동시에 존재합니다.
> Unlabel 데이터는 학습에 활용할 수 있지만 Label이 제공되지 않으며, 평가 데이터의 환경과 동일합니다.


### directory
```
Dacon_fake_voice_detection 
│ 
├── classification_model 
│  ├── best_classification_model.ipynb 
│  ├── daycon_base_line.ipynb 
│  ├── mixup_with_original.ipynb 
│  ├── randomforest_multilabel.ipynb
│  └── randomforest.ipynb 
├── util 
│  ├── ensemble.ipynb 
│  ├── preprocessing.ipynb 
│  └── util.ipynb 
└── readme.md
```
