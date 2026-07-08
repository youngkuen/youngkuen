### 안녕하세요, youngkuen입니다 👋
산업 현장 데이터(센서·PDF 리포트)를 분석·자동화하면서, ML/AI로 역량을 넓혀가고 있는 주니어 Python 개발자입니다.

![Python](https://img.shields.io/badge/Python-3776AB?style=flat&logo=python&logoColor=white)
![Pandas](https://img.shields.io/badge/Pandas-150458?style=flat&logo=pandas&logoColor=white)
![scikit--learn](https://img.shields.io/badge/scikit--learn-F7931E?style=flat&logo=scikitlearn&logoColor=white)
![Flask](https://img.shields.io/badge/Flask-000000?style=flat&logo=flask&logoColor=white)
![Plotly](https://img.shields.io/badge/Plotly-3F4F75?style=flat&logo=plotly&logoColor=white)
![Git](https://img.shields.io/badge/Git-F05032?style=flat&logo=git&logoColor=white)

---

## 📌 Portfolio

### [scrubber-monitoring-pro](https://github.com/youngkuen/scrubber-monitoring-pro)
선박 스크러버(배기가스 세정 장치) 계측 리포트(PDF)를 인터랙티브 대시보드로 자동 변환하는 GUI 도구.

- **문제**: 계측값이 표 형태의 PDF로만 쌓여 있어, 이상 여부를 확인하려면 매번 표를 눈으로 훑어야 했음
- **해결**: PDF 표 구조를 역공학해 파싱하고, Plotly 기반 인터랙티브 대시보드(HTML)로 자동 변환하는 배치 처리 GUI 도구를 제작
- **개발 과정**: 하드코딩된 1회성 스크립트 → 파일 선택 다이얼로그 → 파일별 결과 분리 → 다중 파일 일괄 처리 + 개별 파일 에러 격리까지, 실사용 피드백을 반영해 4단계에 걸쳐 반복 개선 ([EVOLUTION.md](https://github.com/youngkuen/scrubber-monitoring-pro/blob/main/EVOLUTION.md)에 기록)
- 포트폴리오화하며 핵심 로직(표 파싱, 대시보드 생성)을 GUI/PDF I/O와 분리한 순수 함수로 리팩터링하고 단위 테스트를 추가

## 📫 Contact

- Email: ks49347679@gmail.com
