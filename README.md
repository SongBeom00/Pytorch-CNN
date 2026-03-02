### Pytorch CNN 프로젝트 모음

1. dogs vs cats 개와 고양이 이진 분류 미니 프로젝트

2. Plant Pathology 식물 병리학 다중 클래스 분류 미니 프로젝트
   잎 이미지를 기반으로 녹병(Rust), 딱지병/곰팡이병(scab), 복합질병(multiple diseases), 건강한 잎(healthy)으로 분류하는 프로젝트입니다.

- 데이터셋: [Plant Pathology 2020 - FGVC7](https://www.kaggle.com/c/plant-pathology-2020-fgvc7/data)
- 성능 평가 지표 : ROC-AUC
- 모델 : EfficientNet B1 및 EfficientNet V2 S,M 모델로 학습


#### 파이썬(Python) uv 환경 세팅 (macOS 기준)

### 1. uv 설치

> curl -LsSf https://astral.sh/uv/install.sh | sh

path 설정 (zsh용)

> export PATH="$HOME/.local/bin:$PATH"

설정 반영 -> 셸 다시 불러오기

> source ~/.zshrc

설치 확인

> uv --version

uv 0.9.5 (d5f39331a 2025-10-21)

### 2. 프로젝트 생성

루트 폴더로 이동

> cd ~/폴더명

> uv init deep_learning_from_scratch

### 3. 가상환경 생성

. venv 폴더 생성

> uv venv

가상환경 활성화

> source .venv/bin/activate

### 4. 기본 패키지 설치

패키지 설치 numpy, pandas, matplotlib, ipykernel등

> uv add numpy pandas matplotlib, ipykernel

설치된 패키지 목록들 확인하기

> uv pip list
