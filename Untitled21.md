## Python 설치
https://www.python.org/downloads/windows/

Stable Releases

<img src='https://raw.githubusercontent.com/isjo-dit/Lecture/cd511f9e7a2e5194e8c692b022f3111bccca77d2/Screenshot_20250907_204332_Chrome.jpg' width=600>

Add PYTHON to Path 반드시 체크!!!

<img src='https://raw.githubusercontent.com/isjo-dit/Lecture/cd511f9e7a2e5194e8c692b022f3111bccca77d2/Screenshot_20250907_204504_Chrome.jpg' width=600>

---

## Anaconda 설치
https://www.anaconda.com/download/success

<img src='https://raw.githubusercontent.com/isjo-dit/Lecture/cd511f9e7a2e5194e8c692b022f3111bccca77d2/Screenshot_20250907_204721_Chrome.jpg' width=600>
---

## 가상환경 생성

Anaconda Prompt 실행 후 cmd 작성
```bash
conda create -n myenv python=3.11
conda activate myenv
```

## 필수 라이브러리 설치
```bash
pip install numpy pandas matplotlib seaborn scikit-learn
```

## Jupyter Notebook 설치
```bash
pip install notebook
```

## 가상환경을 Jupyter에 등록
```bash
python -m ipykernel install --user --name=myenv 
```

## Jupyter 실행
```bash
jupyter notebook
```

→ 브라우저에서 열림, 커널 선택 시 myenv 사용

## 개발환경 완성!! :)
