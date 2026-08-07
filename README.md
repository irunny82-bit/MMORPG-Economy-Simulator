# MMORPG 재화 순환·강화 경제 시뮬레이터

[웹에서 실행하기](https://irunny82-bit.github.io/MMORPG-Economy-Simulator/) · [포트폴리오 허브](https://irunny82-bit.github.io/)

MMORPG의 재화 획득(Source)과 소비(Sink), 강화 성장 비용, 유저 유형별 성장 격차를 검증하기 위한 웹 기반 시뮬레이터입니다.

> 이복희 · Senior Game System Designer  
> 공개용 샘플 데이터 사용 · 상용 프로젝트의 실제 데이터 및 회사 자산 미포함

## 핵심 기능

- 콘텐츠별 플레이 시간·골드·강화석 획득량 편집
- 거래 참여율·수수료·드롭 기대 수량 등 경제 가정 공개
- 초기 보유 재화와 실제 지출 가능 범위를 반영한 365일 시뮬레이션
- Source–Sink 비율, 순발행량, 성장 소비 중단일 자동 계산
- 라이트·코어·헤비 유저의 재화 흐름과 목표 달성 기간 비교
- +1부터 목표 단계까지 누적 강화 비용 계산
- 4,000회 반복 계산을 통한 평균·P50·P90 강화 비용 비교
- 콘텐츠 효율 편중과 재화 과잉·부족 위험 자동 진단
- 설치 없이 브라우저에서 실행 가능한 정적 웹 도구

## 설계 관점

이 도구는 단순한 수지 계산기가 아니라 다음 의사결정 과정을 확인하기 위해 제작했습니다.

`설계 가설 → Source/Sink 모델 → 유저 유형별 검증 → 성장 기간 확인 → 수치 조정`

## 관련 프로젝트

- [JRPG 전투 밸런스 시뮬레이터](https://irunny82-bit.github.io/jrpg-balance-sim/)
- [VBA 전투 밸런스 시뮬레이터](https://github.com/irunny82-bit/VBA-Combat-Balance-Simulator)
- [전체 포트폴리오](https://irunny82-bit.github.io/)
