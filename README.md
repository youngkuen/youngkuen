### 안녕하세요, youngkuen입니다 👋
제조 현장 데이터(PLC·비전·진동 센서)를 다루며 ML/AI 파이프라인을 실무에 적용해 온 주니어 Python 개발자입니다.

![Python](https://img.shields.io/badge/Python-3776AB?style=flat&logo=python&logoColor=white)
![Pandas](https://img.shields.io/badge/Pandas-150458?style=flat&logo=pandas&logoColor=white)
![scikit--learn](https://img.shields.io/badge/scikit--learn-F7931E?style=flat&logo=scikitlearn&logoColor=white)
![Flask](https://img.shields.io/badge/Flask-000000?style=flat&logo=flask&logoColor=white)
![Plotly](https://img.shields.io/badge/Plotly-3F4F75?style=flat&logo=plotly&logoColor=white)
![Git](https://img.shields.io/badge/Git-F05032?style=flat&logo=git&logoColor=white)

---

## 📌 Portfolio

### [LLMops-pipeline](https://github.com/youngkuen/LLMops-pipeline)
정형 데이터를 업로드하면 LLM이 분석 계획을 세우고 ML 코드를 생성 → 방법론 검증 → 실행 → 진단 → 자동 개선까지 수행하는 End-to-End 파이프라인.
- LLM이 생성한 코드의 데이터 누수·교차검증 오류를 정규식이 아닌 **AST 기반 정적 분석**으로 탐지 (변수 별칭까지 추적)
- 검증 실패 시 피드백을 반영해 재생성하는 이중 개선 루프(코드 재생성 ↔ 성능 기준 재시도) 설계
- 이메일·전화번호 등 PII를 LLM에 전달되는 지점에서만 자동 마스킹, 데이터 실행은 로컬에서만 수행

### 제조 현장 AI 3종
자동차 부품 제조 실무 프로젝트를 실데이터·사내 식별정보 제거 후 포트폴리오로 정리했습니다 (각 저장소 README에 처리 내역 명시).
- **[automotive-vision-inspection](https://github.com/youngkuen/automotive-vision-inspection)** — 비전 검사 NG 판정을 PLC·진동 데이터와 시간 기준으로 엮어 원인을 추적하는 파이프라인
- **[automotive-injection-pdm](https://github.com/youngkuen/automotive-injection-pdm)** — 사출성형 설비 실시간 이상탐지 + SHAP·LLM으로 판단 근거를 해석하는 예지보전(PdM) 리포트 시스템
- **[automotive-foam-process-ai](https://github.com/youngkuen/automotive-foam-process-ai)** — 발포 성형 공정의 희소 불량 이상탐지 및 공정조건 최적화 AI

### 그 외
- **[scrubber-monitoring-pro](https://github.com/youngkuen/scrubber-monitoring-pro)** — PDF 계측 리포트를 인터랙티브 Plotly 대시보드로 자동 변환하는 GUI 도구. 하드코딩 스크립트 → 배치 처리 도구로 발전시킨 과정을 [EVOLUTION.md](https://github.com/youngkuen/scrubber-monitoring-pro/blob/main/EVOLUTION.md)에 기록
- **[lecture-transcript-scraper](https://github.com/youngkuen/lecture-transcript-scraper)** — 가상 스크롤 + 중첩 iframe 구조의 자막을 누락·중복 없이 수집하는 크롤러

## 📫 Contact

- Email: ks49347679@gmail.com
