# Titanic Data Analysis Summary

## Goal

Titanic 데이터를 분석하면서 데이터 분석 프로젝트의 기본 흐름에 익숙해진다.

## Today I Learned

- `pd.read_csv()`로 CSV 파일을 DataFrame으로 불러올 수 있다.
- `head()`로 데이터의 앞부분을 빠르게 확인할 수 있다.
- `shape`으로 행과 열의 개수를 확인할 수 있다.
- `info()`로 컬럼, 결측치가 아닌 값의 개수, 데이터 타입을 확인할 수 있다.
- `describe()`로 숫자형 컬럼의 기본 통계를 확인할 수 있다.
- `isna().sum()`으로 컬럼별 결측치 개수를 확인할 수 있다.

## Python / Pandas Summary

### DataFrame

- pandas에서 표 형태 데이터를 표현하는 핵심 자료구조다.
- 엑셀 시트처럼 행과 열로 구성되어 있다.

### 자주 쓰는 코드

```python
import pandas as pd

df = pd.read_csv("data/titanic.csv")
df.head()
df.info()
df.describe()
```

## Questions

- `Age`, `Cabin`, `Embarked` 컬럼의 결측치는 어떻게 처리해야 할까?
- 생존 여부와 가장 관련이 커 보이는 컬럼은 무엇일까?

## Insights

- 전체 데이터는 891행, 12열이다.
- `Cabin` 결측치가 687개로 가장 많다.
- `Age` 결측치도 177개로 꽤 많다.
- `Embarked` 결측치는 2개뿐이다.
- 전체 생존율은 약 38.4%다.

## Next

- 성별에 따른 생존율 확인
- 객실 등급에 따른 생존율 확인
- 나이 분포 시각화
