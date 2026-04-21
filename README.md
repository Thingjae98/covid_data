# 🦠 COVID-19 데이터 분석

> 국가별 코로나19 확진·사망 추이를 분석하고 패턴을 시각화한 데이터 분석 프로젝트

## 분석 목적
팬데믹 초기(2020) 대비 백신 보급 이후(2021~2022) 사망률 변화를 국가별로 비교하여
**백신 보급 시점과 사망률 감소 간의 상관관계**를 탐색했습니다.

## 주요 분석 내용
- 국가별 일별 확진자 / 사망자 / 회복자 추이 시각화
- 사망률(CFR) 변화 시계열 분석
- 백신 접종률과 사망률 상관관계 scatter plot

## 기술 스택
`Python` `Pandas` `Matplotlib` `Seaborn` `Jupyter Notebook`

## 핵심 인사이트
> *(분석 후 발견한 가장 흥미로운 인사이트를 1~2문장으로 작성)*
> 예: "백신 접종률이 60%를 넘긴 시점 이후 사망률이 평균 N% 감소하는 패턴을 확인했습니다."

## 실행 방법
```bash
pip install -r requirements.txt
jupyter notebook notebooks/covid_analysis.ipynb
```
