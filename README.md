# 김현호 | Finance, Quant & AI Systems

금융의 실제 문제를 데이터와 AI 시스템으로 바꾸고, 모델 검증부터 웹·Android 배포와 운영까지 직접 완성합니다.

[포트폴리오](https://kimhyunho.ai-ve.uk) · [QuantInSight](https://quantinsight.ai-ve.uk) · [GenomicWQB](https://iqc.ai-ve.uk)

## 대표 성과

- ICANEWS 2026 Summer 논문 공모전 우수상
- 2025 파이낸스경영학과 학술제 1위: 환율 쇼크와 KRX 금 시장 비효율성 연구
- 2025 하나증권 모의투자대회 우수상
- 파이낸셜뉴스 대기업 스페셜리스트 공모전 우수상

## Selected Work

| 프로젝트 | 해결한 문제 | 구현·검증 근거 |
|---|---|---|
| [QuantInSight](https://github.com/Arcosium/QuantInSight) | 여러 시장과 자산을 감시하고 실제 주문까지 이어지는 AI 운용 시스템 | 10개 에이전트, 결정론적 리스크 게이트, KIS 실전·모의 계정, 자체 실거래 원장 |
| [GenomicWQB](https://github.com/Arcosium/GenomicWQB) | WorldQuant 알파 후보를 반복적으로 만들고 검증하는 연구 자동화 | 적합도 선택, 교차, 정향 변이, 신규성 압력, IS 검사·제출 자동화 |
| [FestiCast](https://tripcast.ai-ve.uk) | 축제를 열기 전 순증 방문객과 혼잡 피크 예측 | 축제 2,360건, 2024–2025 시간분할 검증, 지방 순위상관 +0.500 |
| [PensionIC](https://pensionic.ai-ve.uk) | 연금·세제 질문에 근거가 남는 답변 제공 | 158개 문서 6,654쪽을 8,871개 청크로 색인, 인용 게이트와 역질문 적용 |
| [금융 AI 보안비서](https://aisecurity.ai-ve.uk) | 금융 사기와 프롬프트 인젝션을 한 서비스에서 탐지 | 기존 벤치마크 99.9% 재현 후 지름길 한계 규명, 별도 실전 평가축 구축 |
| [ArkInsight](https://github.com/Arcosium/arkinsight) | 공개자료로 VC 기업분석보고서 작성 | 출처 의무화, `[추정]`·`[미확인]` 분리, 사실성 가드레일 |
| [CryptoBars](https://github.com/Arcosium/CryptoBars) | 파편화된 거래소의 1분봉을 지속적으로 수집 | 6개 거래소 776종목, 증분 수집과 자가 복구, Parquet 장기 보존 |

## Research

- 「AI 이후의 개인」 — ICANEWS 2026 Summer 논문 공모전 우수상
- 「환율 쇼크와 KRX 금 시장 비효율성」 — 2025 파이낸스경영학과 학술제 1위
- 「급등 속도는 폭락 깊이를 예고하는가」 — 2026 상반기 KOSPI 횡단면 분석
- 「주가 단기 등락 예측을 위한 다중 기술적 지표의 최적 조합 분석」

논문과 보고서 원문은 [포트폴리오의 글·연구 섹션](https://kimhyunho.ai-ve.uk/#writings)에서 볼 수 있습니다.

## 만드는 방식

- 결과 수치보다 먼저 시간분할, 위약검정, 대조군과 실패 가설을 남깁니다.
- LLM의 판단과 주문·보안·정합성 검사를 분리해 중요한 경계는 결정론적으로 통제합니다.
- 시제품에 그치지 않고 서비스, 모바일 앱, 운영 로그와 복구 경로까지 연결합니다.
- 비밀키와 사용자 데이터는 코드 저장소 밖에 두고 공개 가능한 코드와 문서만 관리합니다.

주요 도구: Python · FastAPI/Flask · TypeScript/React · Kotlin · pandas · scikit-learn · PyTorch · SQLite/PostgreSQL · Linux/systemd · Cloudflare
