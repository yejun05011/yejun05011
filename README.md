<div align="center">

# 김예준 · Yejun Kim

**Backend Developer · Java & Spring**

기능 구현부터 API 연동과 검증까지, 서비스가 실제로 동작하는 흐름을 만듭니다.

[Email](mailto:dpwnsl0501@hufs.ac.kr) · [Instagram](https://instagram.com/yejuneeei)

</div>

---

### About

한국외국어대학교 정보통신공학과 · LG CNS AM INSPIRE CAMP 6기

- Java와 Spring을 중심으로 백엔드를 개발합니다.
- 서비스 간 API 계약과 트랜잭션 경계를 고민하고, 실패 상황까지 검증합니다.
- 구현 과정의 의사결정과 문제 해결을 기록합니다.

### Tech

프로젝트에서 사용한 기술입니다.

| 구분 | 기술 |
| --- | --- |
| Backend | Java · Spring Boot · Spring Data JPA · JDBC |
| Database | MariaDB · MySQL · H2 |
| Integration | OpenFeign · Kafka · Spring AI |
| Development | Git · Docker · IntelliJ IDEA |
| Also used | Python · C |

### Selected Projects

#### [HYEJA · 청년 주거 정책 추천 서비스](https://github.com/LGCNS-AM06-Project2-TEAM5/hyeja-msa)

기존 서비스를 마이크로서비스로 전환한 팀 프로젝트입니다. **Policy 서비스 이관과 내부 API, 관심 등록 연동 및 통합 검증**을 담당했습니다.

- 정책 수집·동기화, OpenAI 정책 분석과 정책 조회 기능을 이관했습니다.
- 추천·관심 등록을 위한 내부 API 계약을 조율하고 구현했습니다. 정책 후보와 대상 지역은 일괄 조회하여 **2개 SQL로 조회**하도록 구성했습니다.
- 원격 정책 조회와 로컬 저장의 트랜잭션 경계를 분리하고, 스냅샷·관심 등록의 동시 롤백과 통신 실패 처리를 검증했습니다.
- 정책 저장 트랜잭션에 팀원이 구현한 이벤트 발행기를 연결하고, 실제 Kafka·API·화면의 통합 흐름을 검증했습니다.

[후보 조회 API #57](https://github.com/LGCNS-AM06-Project2-TEAM5/hyeja-msa/pull/57) · [관심 등록 연동 #92](https://github.com/LGCNS-AM06-Project2-TEAM5/hyeja-msa/pull/92) · [통합 검증 #123](https://github.com/LGCNS-AM06-Project2-TEAM5/hyeja-msa/pull/123)

#### [NEURON · 부트캠프 LMS 개선](https://github.com/LGCNS6thHackathon/backend)

LG CNS AM INSPIRE CAMP 6기 해커톤 팀 프로젝트입니다. **출결·소명 권한 정리, 학생 캘린더 API와 검증**을 담당했습니다.

- 기존 출결·소명 관리 API의 권한을 ADMIN으로 통일하고, 본인 기록과 다른 학생의 기록에 대한 접근을 구분했습니다.
- 교육일정·본인 출결·최근 소명 상태·요청 가능한 정정 상태를 반환하는 월별 캘린더 API를 구현했습니다.
- 출결 수정 시 시간 필드의 생략과 명시적 null을 구분하여 기존 입퇴실 시각이 사라지는 문제를 수정했습니다.
- H2 통합 테스트와 격리된 MariaDB 환경의 실제 HTTP 요청으로 권한·소명 처리·시간 보존을 검증하고 API 연동 계약을 문서화했습니다.

[학생 캘린더 #12](https://github.com/LGCNS6thHackathon/backend/pull/12) · [입퇴실 시간 보존 #15](https://github.com/LGCNS6thHackathon/backend/pull/15) · [MariaDB 검증 #16](https://github.com/LGCNS6thHackathon/backend/pull/16)

<details>
<summary>Other Projects</summary>

- [ScholarBee](https://github.com/yejun05011/ScholarBee) — 캡스톤 디자인 프로젝트
- [ICE Studyroom](https://github.com/ICE-STUDYRES/ice-studyroom) — 한국외대 정보통신공학과 스터디룸 예약 시스템
- [VitaCheck](https://github.com/VitaCheck/vitacheck-be) — 팀 프로젝트 백엔드
- [Sporty](https://github.com/livelykitten/inspire_6th_mini_1_sporty) — 공공 체육시설 기반 운동 매칭 서비스

</details>
