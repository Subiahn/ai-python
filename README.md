# ai-python

Python으로 AI 개발자가 되기 위한 공부 기록 저장소입니다.

처음에는 기본 문법을 짧은 summary 형태로 정리하고, Titanic 데이터 분석 프로젝트를 하면서 `pandas`, 시각화, EDA 흐름에 익숙해지는 것을 목표로 합니다.

## Project

### Titanic Data Analysis

Titanic 승객 데이터를 분석하면서 데이터 분석의 기본 흐름을 연습합니다.

- 데이터 불러오기
- 데이터 구조 확인
- 결측치 확인
- 기본 통계 확인
- 컬럼별 생존율 분석
- 시각화
- 분석 summary 작성

## Folder Structure

```text
ai-python/
├─ data/
├─ notebooks/
├─ reports/
│  └─ titanic_summary.md
├─ src/
├─ README.md
└─ requirements.txt
```

## Study Log

| Date | Topic | Summary |
| --- | --- | --- |
| 2026-05-06 | Project setup | GitHub repo and folder structure setup |

## Next Steps

1. `notebooks/01_titanic_eda.ipynb` 실행
2. `head()`, `info()`, `describe()` 결과 직접 확인
3. 성별에 따른 생존율 분석
4. 객실 등급에 따른 생존율 분석

## Environment

```powershell
python -m venv .venv
.\.venv\Scripts\Activate.ps1
pip install -r requirements.txt
jupyter notebook
```
