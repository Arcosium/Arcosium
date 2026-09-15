# 김현호 | Finance, Quant & AI Systems

금융 업무를 AI로 자동화하고, 검증한 모델을 실제 전산 시스템과 서비스로 구현합니다.

[포트폴리오](https://kimhyunho.ai-ve.uk)

## 경력

- 現 한양대학교 파이낸스경영학과 22학번
- 現 한양금융공학회(HYFE) 퀀트팀
- 現 KR투자증권 기획팀 인턴 (2026.09.02~)
- 前 한국투자파트너스 투자지원실 인턴 (2026.03.02~2026.08.31)
- 前 한양경제학회(HEA) 학회장

## 업무 경험

### KR투자증권 · 기획팀 인턴

2026-09-02 ~ 현재

회사 전산 시스템에 AI를 도입하는 업무를 맡고 있습니다. 한국투자파트너스에서 인턴 업무 전반을 AI로 자동화하고 프로그램으로 배포한 경험을 바탕으로 일하고 있습니다.

### 한국투자파트너스 · 투자지원실 인턴

2026-03-02 ~ 2026-08-31

인턴 업무 전반을 AI로 자동화하고 다른 인턴도 사용할 수 있는 프로그램으로 배포했습니다. 펀드 운용 현황, IRR·AUM 등 지표 산출, 투자 집계, 주간보고와 회사 소개자료 갱신을 자동화했습니다. 기존 3시간 업무를 5분으로 줄였고, 업무 데이터 처리는 외부 API 없이 내부 PC의 Python에서 실행하도록 구성했습니다.

## 대표 성과

- 2026 HY-PHEN 연합학술제 최우수상 (1위)
- 2026 대학(원)생 재정데이터 분석 경진대회 최우수상 (Voice2Policy 팀장)
- 2026 ICANEWS Summer 논문 공모전 우수상
- 2026 파이낸셜뉴스 대기업 스페셜리스트 공모전 우수상 (토스증권 1팀, 조장)
- 2025 파이낸스경영학과 학술제 학과장상 (팀장, 1위)

## 프로젝트와 연구

아래 구현·검증 수치는 기존 공개 자료의 2026년 8월 기록입니다. 현재 운영 수치와는 다를 수 있습니다.

### 대표 프로젝트

| 프로젝트 | 해결한 문제 | 구현·검증 근거 |
|---|---|---|
| [QuantInSight](https://github.com/Arcosium/QuantInSight) | 여러 시장과 자산을 감시하고 실제 주문까지 이어지는 AI 운용 시스템 | 10개 에이전트, 결정론적 리스크 게이트, KIS 실전·모의 계정, 자체 실거래 원장 |
| [GenomicWQB](https://github.com/Arcosium/GenomicWQB) | 인자를 하나씩 바꾸는 WorldQuant Brain 알파 탐색을 진화 과정으로 자동화 | 700시간 최적화 경험, 적합도 선택·교차·정향 변이·신규성 압력, IS 검사·제출 자동화 |
| [FestiCast](https://tripcast.ai-ve.uk) | 축제를 열기 전 순증 방문객과 혼잡 피크 예측 | 축제 2,360건, 2024–2025 시간분할 검증, 지방 순위상관 +0.500 |
| [PensionIC](https://pensionic.ai-ve.uk) | 연금·세제 질문에 근거가 남는 답변 제공 | 158개 문서 6,654쪽을 8,871개 청크로 색인, 인용 게이트와 역질문 적용 |
| [금융 AI 보안비서](https://aisecurity.ai-ve.uk) | 금융 사기와 프롬프트 인젝션을 한 서비스에서 탐지 | 기존 벤치마크 99.9% 재현 후 지름길 한계 규명, 별도 실전 평가축 구축 |
| [ArkInsight](https://github.com/Arcosium/arkinsight) | 공개자료로 VC 기업분석보고서 작성 | 출처 의무화, `[추정]`·`[미확인]` 분리, 사실성 가드레일 |
| [CryptoBars](https://github.com/Arcosium/CryptoBars) | 파편화된 거래소의 1분봉을 지속적으로 수집 | 6개 거래소 776종목, 증분 수집과 자가 복구, Parquet 장기 보존 |

### 검증과 실패 기록

| 작업 | 핵심 판단 | 확인된 결과 |
|---|---|---|
| 금융 AI 보안비서 | 표준 벤치마크의 99.9%가 실서비스 성능인지 다시 검증 | 정상 금융 문의를 사기로 오인하는 지름길을 발견하고 별도 hard negative 평가축 구축 |
| 축제 기상청 | 축제 효과를 예측하기 전에 실제 신호인지 위약검정 | 실제 축제 신호가 위약의 2.55배, 2024–2025 시간 홀드아웃 지방 순위상관 +0.500 |
| 부산 상권 조기경보 | 조기경보 지수가 단순한 자기상관보다 무엇을 더 잡는지 비교 | 304개 시계열, 홀드아웃·위약·단순 기준선 비교와 재현 파이프라인 |
| BARAM 풍력발전량 예측 | 반복한 홀드아웃 개선이 실제 개선인지 부트스트랩으로 점검 | Public 274위 실패를 통해 검증셋 과사용과 선택 잡음을 실험 기록으로 정리 |
| AI말평 채점 시스템 | 공개된 평가 규칙과 리더보드 실측이 일치하는지 역산 | 11,581편 말뭉치, 3개 채점 모델 앙상블, 근거 생성, Docker API와 리허설 체계 |
| 포용이(Poyong) | 정책을 못 찾은 상담도 버리지 않고 미매칭 사유로 구조화 | 시민용 정책금융 추천과 익명 신호 기반 정부 대시보드를 웹·Android로 연결 |

### 사이트의 현재 프로젝트

- [QuantInSight](https://quantinsight.ai-ve.uk)
- [GenomicWQB](https://iqc.ai-ve.uk)
- [Poyong (Finnect)](https://poyong.ai-ve.uk)
- [FestiCast — 축제 기상청](https://tripcast.ai-ve.uk)
- [PensionIC](https://pensionic.ai-ve.uk)
- [금융 AI 보안비서](https://aisecurity.ai-ve.uk)
- [ArkInsight](https://arkinsight.ai-ve.uk)
- [술게임 시뮬레이터 🍻](https://mtsimulator.ai-ve.uk)
- [VC News 📰](https://vcnews.ai-ve.uk)
- [Image Generator 🎨](https://imggen.ai-ve.uk)
- [아르카's Blog ✍️](https://arka.ai-ve.uk)
- [ShiftProof](https://shiftproof.ai-ve.uk)
- [쏙똑경제 유튜브 📺](https://www.youtube.com/@%EC%8F%99%EB%98%91%EA%B2%BD%EC%A0%9C)

### 사이트의 현재 연구·글

- [KRX 금 시장의 비효율성과 전이 메커니즘 분석(Extended ver.)](https://kimhyunho.ai-ve.uk)
- [환율 쇼크와 KRX 금 시장 비효율성(Original ver.)](https://kimhyunho.ai-ve.uk)
- [급등 속도는 폭락 깊이를 예고하는가](https://kimhyunho.ai-ve.uk)
- [주가 단기 등락 예측을 위한 다중 기술적 지표의 최적 조합 분석](https://kimhyunho.ai-ve.uk)
- [기업의 금융 제약과 통화 정책의 비대칭적 투자 파급 효과](https://kimhyunho.ai-ve.uk)
- [성별 노동 투입에 따른 경제 성장의 정책적 시사](https://kimhyunho.ai-ve.uk)
- [2026년 통화 정책 보고서](https://kimhyunho.ai-ve.uk)
- [트레블월렛 VC 분석 보고서](https://kimhyunho.ai-ve.uk)
- [개인 투자자의 쏠림 거래가 ETF 가격 괴리율에 미치는 영향](https://kimhyunho.ai-ve.uk)
- [금융자산 다각화 결정요인 분석과 교육방법별 효과 추정](https://kimhyunho.ai-ve.uk)
- [Z세대와 밀레니얼 세대의 보상 선호도 차이 및 동기부여 효과 비교](https://kimhyunho.ai-ve.uk)
- [무상증자 공시의 시장반응과 개인투자자 Attention](https://kimhyunho.ai-ve.uk)
- [AI 이후의 개인](https://kimhyunho.ai-ve.uk)

## 자격과 도구

TOEIC 985점 · 투자자산운용사 · 재무빅데이터분석사 2급 · 회계관리 1급 · 컴퓨터활용능력 2급 · ITQ OA Master · 데이터분석 준전문가(ADsP) · AI Business Test 2급 · 데이터분석 전문관리사 1급 · NCS 금융회계능력인증 1급

Python · FastAPI/Flask · TypeScript/React · Kotlin · pandas · scikit-learn · PyTorch · SQLite/PostgreSQL · Linux/systemd
