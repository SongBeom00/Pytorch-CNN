### Pytorch CNN 프로젝트 모음

1. dogs vs cats 개와 고양이 이진 분류 미니 프로젝트








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
