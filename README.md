데이터 엔지니어를 목표로, 분석 결과를 믿어도 되는 조건까지 검증합니다.

- 육군 의무장교 6년 4개월
- SeSAC 핀테크 데이터 분석가 양성과정 수료(2026.05～10)
- ADsP(데이터분석 준전문가)

## 프로젝트

| 프로젝트 | 무엇을 · 어떻게 검증했나 | 대표 수치 |
|---|---|---|
| [GIS 질의 에이전트](https://github.com/KimInSeok-DA/DA_GIS_Query_Agent) | 서울 법정동·지하철역 데이터를 조회해 답하는 LLM 에이전트(function calling). 정답은 별도 코드로 계산하고, 실행 전 확정한 규칙으로 자동 채점 | 홀드아웃 72문항 중 71문항 정답 |
| [서울 지하철 접근성 GIS](https://github.com/KimInSeok-DA/DA_Seoul_Subway_Access_GIS) · [공개 지도](https://kiminseok-da.github.io/DA_Seoul_Subway_Access_GIS/) | 법정동 467개 접근성 지표 파이프라인. 자동 검증 21개를 통과해야 공개 지도·ArcGIS에 게시 | PostGIS로 다시 계산해 467개 동 완전 일치 |
| [입법예고 의견 자동 분류](https://github.com/KimInSeok-DA/DA_Legislative_Opinion_Coding) | 법안 의견 1,843건을 LLM으로 찬반·주제 분류. 사람이 직접 분류한 표본과 비교하고, 사람 자신과의 일치도를 기준선으로 사용 | 주제 정확도 70%(κ 0.61), 사람 자기 일치 90% |
| [법률안 프로세스 마이닝](https://github.com/KimInSeok-DA/DA_Bill_Process_Mining) | 22대 국회 법률안 21,326건의 이벤트 로그를 공개 API로 구성. 생존분석 방법을 21대 국회로 시험하고, 핵심 수치를 DuckDB SQL로 다시 계산 | 핵심 수치 497개 재계산 일치 |
| [서울 빌라 시세 산정 모델(AVM)](https://github.com/KimInSeok-DA/DA_Seoul_Villa_AVM) | 지번·층·호로 다세대 매매 시세와 80% 구간을 추정(채용 실무 과제). 건물 단위 홀드아웃 632개로 기준선과 비교 | 처음 보는 건물 중앙값 오차 9.4%(기준선 11.1%) |
| [OULAD 중도 이탈 예측](https://github.com/KimInSeok-DA/OULAD_Churn_Prediction-Personal) | 개강 25일 시점 이탈 예측과 조기 경고 등급. 스터디로 시작해 개인 프로젝트로 전환. 마지막 학기를 모델 확정 뒤에만 평가 | 관리자 명단 39.6%로 이탈자 63.8% 포착 |
| [명랑APT](https://github.com/roh-git/mlapt_project) (팀) | 서울 아파트 관리비를 구조가 비슷한 단지끼리 비교하고 1년 뒤 관리비를 예측하는 4인 팀 프로젝트. 담당: 도메인 변수 설계·예측 모델링 | - |
| [금융안정보고서 RAG 챗봇](https://github.com/KimInSeok-DA/LLM_Mini_Project) | 한국은행 금융안정보고서 기반 질의응답 챗봇. 답변마다 출처와 토큰 비용 표시(1일 미니 프로젝트) | - |
| [SeSAC 과정 실습](https://github.com/KimInSeok-DA/DA_Sesac) | Python·통계·크롤링·머신러닝·딥러닝·SQL 실습 기록 | - |

## 기술

- **언어·데이터**: Python, SQL(DuckDB · PostgreSQL/PostGIS · SQLite · Oracle), pandas
- **모델링**: scikit-learn, XGBoost, LightGBM
- **LLM**: LLM API, function calling
- **공간 데이터**: GeoPandas, ArcGIS
- **시각화·화면**: Tableau, Streamlit
- **도구**: Docker, Git

## 연락처

kimis0916@naver.com
